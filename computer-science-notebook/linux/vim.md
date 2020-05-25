# VIM 命令

[TOC]

## 查找

查找 是在命令模式下进行的。
在命令模式下输入" `/ 要查找的子字符串`"

按  `n`  重复上一个搜索模式。

## 跳到文档开头或末尾

跳到文档开头: gg
跳到文档末尾: G
跳到指定行： nG 或 ngg， n 代表行数  或者在命令模式下直接输入行号，然后回车。

## 翻页

```
ctrl + F # 下一页 ctrl + forward
ctrl + B # 前一页 ctrl + backward
```



## 光标移动

    0 光标移动到行首
    $ 光标移动到行末

## 复制 与 粘贴

    yy 复制光标所在行
    nyy 复制光标所在的向下 n 行
    yG 复制光标所在行到最后一行
    p 粘贴在光标下一行
    P 粘贴在光标上一行

## 保存和离开命令

    :q! 不保存修改，强制离开
    :wq! 强制保存后离开

## 删除命令

    dd 删除光标所在的一整行
    ndd 删除光标所在的向下 n 行
    dG 删除光标所在行到最后一行的所有数据
    ggdG 删除所有数据

## 编辑

```
u 撤销
a 在光标所在字符后面追加数据
A 在光标所在行行尾追加数据
x 删除光标所在位置的字符

```
