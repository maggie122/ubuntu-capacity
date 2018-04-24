# ubuntu-capacity


1. windows分出空闲区域

	计算机 → 管理 → 磁盘管理，选择要压缩的磁盘，右键压缩卷，输入要压缩的容量，会得到绿色的可用空间

2. gparted合并分区

	下载ISO文件 http://gparted.sourceforge.net/download.php
	
	安装 LinuxLive USB Creator 2.9.4.exe，制作启动U盘
	
	重启电脑进入U盘，在gparted中选择扩容的分区，右键选择resize/move，可通过拖动滑块调整大小
	
	最后点击apply进行修改
	
	完成后关闭电脑，拔出U盘
      
3. grub修复

	再次启动电脑可能会出现以下情况
	
	error:unknown filesystem
	
	grub rescue>
	
	具体解决方法可参考 http://www.cnblogs.com/zengyonggang/p/3582172.html
