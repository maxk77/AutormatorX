# AutomatorX
Use the crazy Automator and AppleScript to improve efficiency on Mac.

Here are some of the workflows I frequently used. Except for the ones market as "Original", others are from some blogs or forum posts.



# Description

<u>包括了以下workflow：</u>

1. 批量修改文件名/Rename filename in batches

   Here is a real use case for me. 
   
   P.S. I suggest you set a shortcut for it.

   ![image](https://github.com/max-yeah/AutormatorX/blob/master/image/cut.gif)

<br>

2. URL decode
<br>

3. Automatically export PPT -> PDF (Need MS PPT)
<br>

4. Automatically export Words -> PDF (Need MS Words)
<br>

5. “Move to”（Original）

   ![image](https://github.com/max-yeah/AutormatorX/blob/master/image/copy.gif)
   
   You can change the default location by opening this workflow with Automator
   
   I'm using this with shortcut cmd+ctl+m. It is actually more useful than I originally assume.

<br>


6. Transform .png image to .icns icon for Mac apps（Original），借鉴了stackoverflow答主代码：https://stackoverflow.com/questions/12306223/how-to-manually-create-icns-files-using-iconutil/20703594#20703594
<br>

7. Retrieve. (Original)

   Will retrieve all files in a folder to upper level, and remove that folder.

   I mainly use it when I download TV series and want to retrieve them from original folder.

   ![image](https://github.com/max-yeah/AutormatorX/blob/master/image/retrieve.gif)
   

<br>

8. SHA Checksum. (Original)

   Handy workflow for me to verify the checksum of a downloaded file. Support SHA-1, SHA-256, and SHA-512 algorithm.

   <br>

9. Fix Chinese wrong Encoding (Original)

   On macOS when handling chinese file from windows, the characters could be in wrong encoding. This workflow can transfer gbk format --> utf8

   ![image](https://github.com/max-yeah/AutormatorX/blob/master/image/chinese_encode.gif)


# Installation

Double click the workflow to install

<br>

Open Finder，Press command + shift + G，Enter ~/Library/Services

Draw the workflows to it
![image](https://github.com/max-yeah/AutormatorX/blob/master/image/folder.png)
