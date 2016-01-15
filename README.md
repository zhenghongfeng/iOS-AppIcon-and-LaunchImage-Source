# iOS-AppIcon-and-LaunchImage-Source
Set the size of App icon and launchImage
Launch Image 启动图片 不显示问题
第一步：设置工程的通用栏中Launch Screen File 为空。
第二步：取消自动生成的[LaunchScreen.storyboard]文件的属性栏中：Use as Launch Screen的勾勾。
第3步：勾上LaunchImage中的IOS8.0 And later的勾勾。
好了。clean一下，然后重新运行一下就可以看到效果了。
注意：如果没有实现，请把原来的app删掉，在运行试试。
