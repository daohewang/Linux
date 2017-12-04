# Linux基础 
## 常用的快捷键  

| 按键            | 作用                    |
| ------------- | --------------------- |
| ctrl+d        | 键盘输入结束或退出终端           |
| ctrl+s        | 暂停当前程序，暂停后按下任意键恢复     |
| ctrl+z        | 将当前程序放到后台运行，恢复到前台命令fg |
| ctrl+a        | 将光标移动至输入行头，等同于Home键   |
| ctrl+e        | 将光标移动至输入行尾，等同于end键    |
| ctrl+k        | 删除从光标所在位置到行末          |
| Alt+Backspace | 向前删除一个单词              |
| shift +PgUp   | 将终端显示向上滚动             |
| shift +PgDown | 将终端显示向上滚动             |

## 常用命令行  

**ls**   

- 功能描述：显示目录文件  

- 原意: list  

- 所在路径：/bin/ls  

- 执行权限：所有用户   

- 语法：ls  选项-ald   [文件或目录]  

  - -a （all） 显示所有文件，包括隐藏的文件  
  - -l   详细信息显示  
  - -d  查看目录属性     
  - -lh   可以把数据单位B转化为KB，便于阅读  

  **mkdir**    

- 功能描述：创建新目录   

  ​                   -p  递归创建（可以连续创建目录）

- 原意：make  directories  

- 所在路径：/bin/mkdir  

- 执行权限：所有用户  

- 语法： mkdir   -p   [目录名]  

- 例子：mkdir  -p  /tmp/haizei/lufei     

**cd**   

- 功能描述：切换目录

-  原意： change   directory  

- 所在路径： shell内置命令  

- 执行权限： 所有用户  

- 语法：cd [目录]    

- 例子： $cd  /tmp/haizeiwang/lufei      切换到指定目录  

  ​             $cd  ..                                           回到上一级目录    

**pwd**  

- 功能描述： 显示当前目录  
- 英文原意：print  working  directory  
- 所在路径： /bin/pwd  
- 执行权限：所有用户     

**rmdir** 

- 功能描述：删除空目录  
- 英文原意：remove   empty  directories  
- 所在路径 ：/bin/rmdir  
- 执行权限：所有用户  
- 语法：rmdir [目录名]  

**cp** 

- 功能描述： 复制文件或目录  

- 英文原意：copy

- 所在路径：/bin/cp  

- 执行权限 ：所有用户 

- 语法 ：cp  -rp  [原文件或目录]   目标目录] 

  ​                   -r    复制目录  

  ​                  -p    保留文件属性

**特殊情况**  

1.显示以**.**   开头的隐藏文件，但是不包含第二个点字符

> ls  -d  .[! .]?*    

