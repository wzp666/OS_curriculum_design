# OS_curriculum_design
## a virtual file system
指令 | 释义
-----------------|-----------------------------------
ls	|	查看当前目录下的文件情况
mkdir	|	创建子目录
mkdirs xxx	| 创建多级子目录
cd xx	|	进入子目录
cd ..	|	退出子目录
cd 	|	跳转到根目录
pwd 	|	查看当前路径
touch 	| 当前路径下创建文件
rm (-rf) xx |	删除文件(目录)
rm xxx	|	删除多级子目录(删掉的是路径的最末端节点)
cp from to |	拷贝文件/目录(初始的存在)
move from to	| 移动文件/目录(初始的不存在)
find xx |	路径下查找文件/目录
state	|	查看内存块占用情况
rename file name | 文件/目录重命名
cat file |	查看文件内容(只能看)
chuser	|	切换用户(默认admin)
crateuser (-rwap) |	新建用户，权限是(读写删)
link -h/s from to | 在目标路径下创建源文件/路径的链接,-h是硬链接,-s是软链接
open xx	|	打开文件(另起一行,类似于vim)
