## pycharm配置服务器

查看服务器的cuda版本

cat /usr/local/cuda/version.txt

https://blog.csdn.net/Alina_M/article/details/105901297?spm=1001.2101.3001.6650.4&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-4.pc_relevant_antiscanv2&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-4.pc_relevant_antiscanv2&utm_relevant_index=6

## Linux操作

cd p  查找有p的文件

cd pytorch_project/ 进入文件

cd STFGNN/

ls 查看文件中目录

pip install -r requirements.txt 安装配置



## Vim命令

# vim编辑保存退出

## 命令

```
vim 要打开的文件名字
比如要打开test.log
命令为：vim test.log
```

注意：如果不存在test.log则会自动创建

1. 进入编辑器后按 字母“i”即可进入编辑状态（此时左下角会出现 “插入”）
2. 退出的时候分为4种情况：保存退出、正常退出、不保存退出以及强制退出
    2.1：保存退出：按“Esc”键后 此时的“插入”会消失，然后按Shift+zz 就可以保存修改内容并退出
    2.2：不保存退出：当修改修改了一部分内容后发现修改错了，此时就会进行不保存退出
                 按“Esc”键后，再输入“：”之后在输入命令时直接输入“q!” 
    2.3：强制退出： 按“Esc”键后，再输入“：”之后在输入命令时直接输入“!”
    2.4：正常退出：按“Esc”键后，再输入“：”之后在输入命令时直接输入“q”



source .bashrc   生效配置文件



## 如何跑深度学习代码



