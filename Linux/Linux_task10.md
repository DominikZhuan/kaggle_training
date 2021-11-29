**任务10：使用find和locate定位文件**

任务要点：文件搜索

[https://www.runoob.com/linux/linux-comm-find.html](https://www.runoob.com/linux/linux-comm-find.html?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2MzgxOTg3MzcsImciOiJkdW1yc2V4VFJKa3FTZ0lDIiwiaWF0IjoxNjM4MTk4NDM3LCJ1c2VySWQiOi0xMzE3MTI1Njc3fQ.OH8XpVb_lAeKozBPOozvbLejgUzqLaC3GDBR2D-coGM)

[https://www.cnblogs.com/linjiqin/p/11678012.html](https://www.cnblogs.com/linjiqin/p/11678012.html?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2MzgxOTg3MzcsImciOiJkdW1yc2V4VFJKa3FTZ0lDIiwiaWF0IjoxNjM4MTk4NDM3LCJ1c2VySWQiOi0xMzE3MTI1Njc3fQ.OH8XpVb_lAeKozBPOozvbLejgUzqLaC3GDBR2D-coGM)

- 步骤1：使用find统计文件系统中以py为后缀名的文件个数
  - $find / -name "*.py" | wc -l
  - ![image-20211129235241611](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211129235241611.png)
  - ![image-20211129235250515](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211129235250515.png)

- 步骤2：使用find寻找/home/文件夹下文件内容包含coggle的文件
  - ![image-20211129235525755](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211129235525755.png)
  - $find /home/ -type f | xargs grep "coggle"

- 步骤3：时候用locate寻找到python3.preinst文件
  - 

