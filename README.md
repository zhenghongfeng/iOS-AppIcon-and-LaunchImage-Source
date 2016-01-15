# iOS-AppIcon-and-LaunchImage-Source   
Set the size of App icon and launchImage    

Launch Image 的尺寸    
将规定尺寸的图片从你的文件中拖动进到固定位置.   
系统	尺寸	分辨率   
ios8	Retina HD5.5	          1242x2208     
      Retina HD4.7	          750x1334      
      Landscape Retina Hd 5.5	2208x1242     
ios7		                      640x960      
      Retina4	                640x1136       

1.遇到过的坑：Launch Image 启动图片不显示       
解决办法：   
第一步：设置工程的通用栏中Launch Screen File 为空。  
第二步：取消自动生成的[LaunchScreen.storyboard]文件的属性栏中：Use as Launch Screen的勾勾。  
第三步：勾上LaunchImage中的IOS8.0 And later的勾勾。   
好了。clean一下，然后重新运行一下就可以看到效果了。    
注意：如果没有实现，请把原来的app删掉，在运行试试。   

