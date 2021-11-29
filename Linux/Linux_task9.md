**任务9：在目录下创建zip和tar压缩文件，并进行解压**

任务要点：文件压缩

[https://www.cnblogs.com/wxlf/p/8117602.html](https://www.cnblogs.com/wxlf/p/8117602.html?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2MzgxOTg3MzcsImciOiJkdW1yc2V4VFJKa3FTZ0lDIiwiaWF0IjoxNjM4MTk4NDM3LCJ1c2VySWQiOi0xMzE3MTI1Njc3fQ.OH8XpVb_lAeKozBPOozvbLejgUzqLaC3GDBR2D-coGM)

- 步骤1：在/home/coggle目录下在你英文昵称（中间不要有空格哦）的文件夹中，下载[https://mirror.coggle.club/dataset/jaychou_lyrics.txt.zip](https://mirror.coggle.club/dataset/jaychou_lyrics.txt.zip?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2MzgxOTg3MzcsImciOiJkdW1yc2V4VFJKa3FTZ0lDIiwiaWF0IjoxNjM4MTk4NDM3LCJ1c2VySWQiOi0xMzE3MTI1Njc3fQ.OH8XpVb_lAeKozBPOozvbLejgUzqLaC3GDBR2D-coGM)
- 步骤2：使用zip 压缩/home/coggle目录下在你英文昵称（中间不要有空格哦）的文件夹
  - zip pixel.zip /home/coggle/pixeldog/
  - ![image-20211129234358284](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211129234358284.png)

- 将步骤3：步骤3：将 /home/coggle目录下在你英文昵称（中间不要有空格哦）的文件夹，打包为tar格式。
  - ![image-20211129234525284](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211129234525284.png)
  - $tar czvf pixel.tar /home/coggle/pixeldog/

- 步骤4：将 /home/coggle目录下在你英文昵称（中间不要有空格哦）的文件夹，打包为tar.gz格式。
  - ![image-20211129234639212](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211129234639212.png)
  -  $tar czvf pixel.tar.gz /home/coggle/pixeldog/