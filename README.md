Macbook外接显示器开启1080 hidpi方法

第一步:下载patch-edid.rb
链接:https://pan.baidu.com/s/1nkj2dooZHg5eHRB7kRCz6g  密码:johi

git中已经有这个文件

第二步：运行行 patch-edid.rb

#cd Downloads

#ruby patch-edid.rb
运行完成后在Downloads目录中生成一个DisplayVendorID-4c2d文件夹
第三步：拷贝文件
sudo cp DisplayVendorID-4c2d   /System/Library/Displays/Contents/Resources/Overrides   #如果重名提前备份

第四步：重新连接显示器查看效果

第五步：可安装RDM管理显示器分辨率


原贴地址：https://bbs.feng.com/forum.php?mod=viewthread&tid=7742433
