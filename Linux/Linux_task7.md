**任务7：在Linux系统中后台运行应用程序，并打印日志**

任务要点：程序后台运行，进程管理

- 步骤1：在/home/coggle目录下在你英文昵称（中间不要有空格哦）的文件夹中创建一个sleep.py文件，该文件需要完成以下功能：

  - 程序一直运行
  - 每10秒输出当前时间
  - ![image-20211128175841941](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211128175841941.png)
  - 如果直接获取当前时间在 + 10  会出现出现很久没有输出，因为，计算这个+10 也会耗费时间，这样下一次获取的时间并不能对齐。
- 步骤2：学习 & 和 nohup后台执行的方法

  - [https://blog.csdn.net/a736933735/article/details/89577557](https://blog.csdn.net/a736933735/article/details/89577557?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2MzgwODk1MzUsImciOiJkdW1yc2V4VFJKa3FTZ0lDIiwiaWF0IjoxNjM4MDg5MjM1LCJ1c2VySWQiOi0xMzEwMjY3NTc2fQ.5lAMZHGnPDlW1hvwq-Kd2UJkD8TgitRQrzk96hKRkeU)

  - [http://ipcmen.com/jobs](http://ipcmen.com/jobs?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2MzgwODk1MzUsImciOiJkdW1yc2V4VFJKa3FTZ0lDIiwiaWF0IjoxNjM4MDg5MjM1LCJ1c2VySWQiOi0xMzEwMjY3NTc2fQ.5lAMZHGnPDlW1hvwq-Kd2UJkD8TgitRQrzk96hKRkeU)
- 步骤3：学习tmux的使用，将步骤1的程序进行后台运行，并将输出结果写入到txt文件。
  - ![image-20211128232626224](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211128232626224.png)
  - [tmux 教程](https://www.ruanyifeng.com/blog/2019/10/tmux.html)
  - 可能会遇到 unset TMUX 问题：https://blog.csdn.net/blackmanren/article/details/48243671


- Linux终端中将命令的输出保存到文件中：https://linux.cn/article-12920-1.html

- 为什么运行了 这个命令**nohup python3 sleep.py > sleep_out.txt 2>&1 &** 之后，sleep_out.txt 还是没有呢，文件里面存进去的是 **nohup: ignoring input**：
  - ![image-20211129004455788](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211129004455788.png)
  - 原来是 程序反应慢额。。
