# Soft-course-design-III
 ***软件课设三***

按照老师的要求，把那个项目编译工具链之后写好程序编译，然后刷到固件上。

我是用的有breed的路由器，所以能方便一些，如果路由器没有breed，自行搜索方法。

仓库里的那个trx文件是把内核模块独立出来的，有ko文件生成，要想把内核模块嵌入，就把内核模块的**Kconfig**和**Makefile**里面的**obj-m**改成**obj-y**，**==注意看目录，不要写错了==**

