**任务3：在目录下下载文件、阅读文件**

任务要点：下载文件、移动文件、阅读文件

- 步骤1：

- 在home目录下，新建一个以你英文昵称（中间不要有空格哦）的文件夹A

- 在文件夹A内部创建一个以coggle命令的文件夹B
  - mkdir -p pixeldog/coggle/
  - ![image-20211103002727798](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211103002727798.png)

- 步骤2：使用wget命令下载https://mirror.coggle.club/dataset/affairs.txt，到文件夹B

- wget教程：https://www.cnblogs.com/pretty-ru/p/10936023.html
  - wget https://mirror.coggle.club/dataset/affairs.txt
  - ![image-20211103002920977](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211103002920977.png)

- 步骤3：使用head、cat、tail命令阅读下载的文件。
  - head affairs.txt
  - ![image-20211103003103416](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211103003103416.png)
  - tail affairs.txt
  - ![image-20211103003158184](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211103003158184.png)

- 阅读文件基础教程：https://www.cnblogs.com/jixp/p/10833801.html

- 步骤4：在命令行使用ipython进入python3环境，并使用pandas读取下载的文件。

  - ![image-20211103003657504](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211103003657504.png)

  
