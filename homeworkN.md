# 预备课测试题
下载文件test.sh安装到本地并运行

新建文件夹practice并将test.sh移动到practice文件夹中

> ```edzdeMacBook-Air-4:~ edz$ cd practice

> ```edzdeMacBook-Air-4:practice edz$ ls

> ```test        test.sh        test123.txt

使用tree命令
![原始文件](https://github.com/TWH199602/picture1/blob/master/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202020-03-22%20%E4%B8%8A%E5%8D%8812.17.12.png)
## 题目一
在 practice 目录下一行命令删除test文件夹下所有以 .txt 结束的文件

使用：
> ```find ./test -type f -name "*.txt" |xargs rm -r
如图：
![删除.txt文件](https://github.com/TWH199602/picture1/blob/master/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202020-03-22%20%E4%B8%8A%E5%8D%8812.18.33.png)

## 题目二
再使用一行命令删除test1和test2目录下以 .doc 结束的文件

使用：
> ```find ./test -type f -name "*.doc" | egrep "./test1/|./test2/" |xargs rm -r
![删除test1和test2目录下以 .doc 结束的文件](https://github.com/TWH199602/picture1/blob/master/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202020-03-22%20%E4%B8%8A%E5%8D%8812.20.31.png)



