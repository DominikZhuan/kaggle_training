**任务8：使用grep和awk从文件中筛选字符串**

任务要点：字符筛选

- 步骤1：下载周杰伦歌词文本，并进行解压。

[https://mirror.coggle.club/dataset/jaychou_lyrics.txt.zip](https://mirror.coggle.club/dataset/jaychou_lyrics.txt.zip?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2MzgxOTg3MzcsImciOiJkdW1yc2V4VFJKa3FTZ0lDIiwiaWF0IjoxNjM4MTk4NDM3LCJ1c2VySWQiOi0xMzE3MTI1Njc3fQ.OH8XpVb_lAeKozBPOozvbLejgUzqLaC3GDBR2D-coGM)

- ![image-20211129231144543](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211129231144543.png)

- 步骤2：利用grep命令完成以下操作，并输出到屏幕

[https://blog.csdn.net/baidu_41388533/article/details/107610827](https://blog.csdn.net/baidu_41388533/article/details/107610827?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2MzgxOTg3MzcsImciOiJkdW1yc2V4VFJKa3FTZ0lDIiwiaWF0IjoxNjM4MTk4NDM3LCJ1c2VySWQiOi0xMzE3MTI1Njc3fQ.OH8XpVb_lAeKozBPOozvbLejgUzqLaC3GDBR2D-coGM)

[https://www.runoob.com/linux/linux-comm-grep.html](https://www.runoob.com/linux/linux-comm-grep.html?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2MzgxOTg3MzcsImciOiJkdW1yc2V4VFJKa3FTZ0lDIiwiaWF0IjoxNjM4MTk4NDM3LCJ1c2VySWQiOi0xMzE3MTI1Njc3fQ.OH8XpVb_lAeKozBPOozvbLejgUzqLaC3GDBR2D-coGM)

- 统计歌词中 包含【超人】的歌词
  - ![image-20211129231345286](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211129231345286.png)

- 统计歌词中 包含【外婆】但不包含【期待】的歌词
  - ![image-20211129231835359](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211129231835359.png)

- 统计歌词中 以【我】开头的歌词
  - ![image-20211129231920199](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211129231920199.png)

- 统计歌词中 以【我】结尾的歌词
  - ![image-20211129231958415](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211129231958415.png)

- 步骤3：利用sed命令完成以下操作，并输出到屏幕

[https://www.cnblogs.com/JohnLiang/p/6202962.html](https://www.cnblogs.com/JohnLiang/p/6202962.html?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2MzgxOTg3MzcsImciOiJkdW1yc2V4VFJKa3FTZ0lDIiwiaWF0IjoxNjM4MTk4NDM3LCJ1c2VySWQiOi0xMzE3MTI1Njc3fQ.OH8XpVb_lAeKozBPOozvbLejgUzqLaC3GDBR2D-coGM)

- 将歌词中 第2行 至 第40行 删除
  - ![](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211129233321975.png)

- 将歌词中 所有【我】替换成【你】
  - ![image-20211129233937254](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211129233937254.png)
  - $grep '我' jaychou_lyrics.txt | sed 's/我/你/g'