**任务6：在目录下创建py目录，并进行import导入**

任务要点：python代码模块化

- 步骤1：学习python模块化，https://www.runoob.com/python3/python3-module.html

- 步骤2：在/home/coggle目录下在你英文昵称（中间不要有空格哦）的文件夹中创建affairs文件夹。

- 步骤3：编写test6.py和affairs.py完成以下功能：

  - 功能1：affairs.py代码完成https://mirror.coggle.club/dataset/affairs.txt文件的读取，这里可以直接pd.read_csv('https://mirror.coggle.club/dataset/affairs.txt')来完成。这一部分建议写为函数。

  - 功能2：test6.py可以导入affairs.py代码

  - 功能3：test6.py可以进行命令行解析，输出[affairs.txt](https://mirror.coggle.club/dataset/affairs.txt)具体的第几行内容。

```python
/home/coggle/
    你英文昵称命名的文件夹/
       test6.py
       affairs/
            affairs.py
```

```python
实现要求：
在/home/coggle/你英文昵称命名的文件夹/目录下，可以执行：

python3 test6.py 10
没有bug，并完成第十行内容的输出。
```

- ![image-20211107231245104](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211107231245104.png)
- ![image-20211107231309391](C:\Users\ZHUAN\AppData\Roaming\Typora\typora-user-images\image-20211107231309391.png)
  - **注意 sys.argv[0] 是脚本的名称**

