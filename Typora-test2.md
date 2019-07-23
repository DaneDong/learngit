# Markdown 学习笔记
#### 1.用#来标记标题，数量表示标题的等级
#### 2.段落，两个空格表示换行
关于字体：  
*关于字体*  
_关于字体_  
**粗体字体**  
***粗斜体***  
分隔线

***
*****
********
* * *
---
------
删除线  
~~要删除啊~~  
下划线
<u>under line</u>  
脚注[^脚注]  
[^脚注]：是的吧 
脚注不会用

列表  
+ 无序列表
+ 没有序号
1. 有序列表
2. 有序号的  

列表嵌套
+ 无序列表
+ 嵌套有序列表
+     1. 常规约定
+     2. 加四个空格
+     3. 好像效果不对啊

区块概念
> 区块引用
>
> > 支持嵌套

markdown代码  
'printf()'代码,不会用

代码区块
用四个空格,或者一个制表符缩进

'''指定一种语言后写代码

markdown链接
本文参考链接<https://www.runoob.com/markdown/md-link.html>  
或者[菜鸟教程](https://www.runoob.com/markdown/md-link.html)

高级链接
链接地址也可以用变量标记  
比如:  
[这个链接][1]先标记为1,在文章结尾或者其他地方在详细标注链接  

[1]:https://www.runoob.com/markdown/md-link.html
好像没用

图片  
![图片名称](https://www.jianguoyun.com/d/openUrlFromClient?un=ds294674420%40126.com&du=%2f%23tab%3dbrowse%3a%3aid%3dc6b76e%3a%3amagic%3d3bbcc9ebfe5585da%3a%3apath%3d%2f%3a%3a&ep=1563859202&sg=ukdp%2b63PwW%2bmEXGZMtWrkEcTGN4%3d&sn=0)
貌似不能直接访问坚果云，![image](https://www.jianguoyun.com/d/openUrlFromClient?un=ds294674420%40126.com&du=%2f%23tab%3dbrowse%3a%3aid%3dc6b76e%3a%3amagic%3d3bbcc9ebfe5585da%3a%3apath%3d%2f%3a%3a&ep=1563859202&sg=ukdp%2b63PwW%2bmEXGZMtWrkEcTGN4%3d&sn=0)

![换个图片](https://image.baidu.com/search/detail?z=0&word=%E6%91%84%E5%BD%B1%E5%B8%88%E5%BC%A0%E9%93%8E&hs=0&pn=2&spn=0&di=0&pi=63814538342&tn=baiduimagedetail&is=0%2C0&ie=utf-8&oe=utf-8&cs=3798940318%2C1852883529&os=&simid=&adpicid=0&lpn=0&fm=&sme=&cg=&bdtype=-1&oriquery=&objurl=http%3A%2F%2Fg.hiphotos.baidu.com%2Fimage%2Fpic%2Fitem%2F86d6277f9e2f07084eacbbebe724b899a801f2b4.jpg&fromurl=&gsm=0&catename=pcindexhot&islist=&querylist=)
百度的图片也显示不出来呀

表格  
| 表头    |    表头 |   表头   |
| :------ | ------: | :------: |
| 单元格1 | 单元格2 | 单元格3  |
| 左对齐  |  右对齐 | 居中对齐 |

高级技巧  
支持HTML


学习完成,入门还是很简单,需要解决一些问题,图片怎么插入