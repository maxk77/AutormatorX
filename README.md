# AutomatorX
使用Mac的Automator和AppleScript提高生产力

这里包含了我现在常用的一些workflow，除了标记“原创”以外均来自网络，感谢愿意编写workflow并具有分享精神的programmers



# Description

<u>包括了以下workflow：</u>

1. 批量修改文件名

   Here is a real use case for me. 
   
   P.S. I suggest you set a shortcut for it.

   ![image](https://github.com/max-yeah/AutormatorX/blob/master/image/cut.gif)

<br>

2. 修复文件名unicode乱码
<br>

3. 自动批量转换PPT -> PDF
<br>

4. 自动批量转换Word -> PDF
<br>

5. 移动选中file(s)去某个文件夹（和Linux “Copy to”功能一样）（Original）

   ![image](https://github.com/max-yeah/AutormatorX/blob/master/image/copy.gif)
   
   可以设置打开时默认位置，我设置在了课程文件夹，编辑方式：用automator打开workflow，可以看到folder position
   
   建议配合快捷键使用。

<br>


6. 把png图像一键转换成icns格式（Original），借鉴了stackoverflow答主代码：https://stackoverflow.com/questions/12306223/how-to-manually-create-icns-files-using-iconutil/20703594#20703594
<br>

7. Retrieve. (Original)

   Will retrieve all files in a folder to upper level, and remove that folder.

   I mainly use it when I download TV series and want to retrieve them from original folder.

   ![image](https://github.com/max-yeah/AutormatorX/blob/master/image/retrieve.gif)
   
<br>
   
8. SHA Checksum. (Original)

   Handy workflow for me to verify the checksum of a download file. Support SHA-1, SHA-256, and SHA-512 algorithm.

   <br>


# Installation

双击workflow文件安装，嫌麻烦的也可以：

<br>

打开finder，按command + shift + G，输入~/Library/Services

就可以进入“服务”文件夹，接下来把这些workflow拖进去就好
![image](https://github.com/max-yeah/AutormatorX/blob/master/image/folder.png)
