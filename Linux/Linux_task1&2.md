![image-20211103000333933](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211103000333933.png)



**任务2：在目录下创建文件夹、删除文件夹**

任务要点：创建文件夹、创建文件、删除文件、删除文件夹

- 步骤1：学习[Linux的目录结构](https://www.runoob.com/linux/linux-system-contents.html)

- 步骤2：学习[Linux的文件和目录管理](https://www.runoob.com/linux/linux-file-content-manage.html)

- 步骤3：

- 在/home/coggle目录下，新建一个以你英文昵称（中间不要有空格哦）的文件夹A

  - mkdir pixeldog

    ![image-20211103000515677](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211103000515677.png)

- 在文件夹A内部创建一个以coggle命令的文件夹B

  - cd pixeldog
  - mkdir coggle

  or :

  - mkdir -p pixeldog/coggle

  

  ![image-20211103000629634](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211103000629634.png)

- 步骤4：在B文件夹内创建一个空txt文件
  - touch test.txt
  - ![image-20211103001350722](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211103001350722.png)

- 步骤5：删除步骤4创建的文件
  - rm test.txt
  - ![image-20211103001437466](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211103001437466.png)

- 步骤6：删除文件夹B，然后删除文件夹A
  - rm -r pixeldog/
  - ![image-20211103001538851](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211103001538851.png)
  - rmdir -p pixeldog/coggle/
  - ![image-20211103002005554](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211103002005554.png)







