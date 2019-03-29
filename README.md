第一步下载：patch-edid.rb

链接:https://pan.baidu.com/s/1ZbCkZNmc0mAr8T3EBVjecg  密码:1x91
git中已经有些文件
第二步：运行行 patch-edid.rb

#cd Downloads

#ruby patch-edid.rb
运行完成后在Downloads目录中生成一个DisplayVendorID-4c2d文件夹
第三步：拷贝文件
sudo cp DisplayVendorID-4c2d   /System/Library/Displays/Contents/Resources/Overrides   #如果重名提前备份

第四步：重新连接显示器查看效果

第五步：可安装RDM管理显示器分辨率
