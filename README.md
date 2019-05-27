# MayaCheck
Maya检查函数

1:查询比例尺(1:10)

2:面的法线（face normal）方向朝外

3:查询模型的点信息是否冻结清零 

4:判断是否有重叠的面（lamina faces）

5:groupID是否清理干净

6:unkonwn节点是否清理干净

7:资产文件内所有物体是否包含动画（keyframe）信息

8:检查UV重叠（个别种类如瓦片，树叶等除外）

9:UV是否反向

10:每个象限的uv是否有uv点超出象限范围

11:"贴图的大小是否是512的倍数（1024,2048,8192...）"

12:yetinode的display output提交文件时候是否关闭

13:maya的文件保存时是否关闭了swatchs render
14:maya的文件保存时是否关闭了所有窗口
15:uv与uv之间不能相离太近
16:置换贴图（displacement）需要单独输出32位版本
17:最终提交贴图需要提供photoshop的psd文件
18:psd文件内部层（layer）需要按照输出到shader的属性相对应打组
19:毛发模型需要提交nurbs和poly两个版本
20:毛发的nurbs方向必须一致
21:maya打开文件时的默认视图应该为标准视图，必须能一眼看到资产全貌（个别大场景除外）
22:模型之间没有穿插，尤其是需要simulation的物体
23:清理灯光连接的垃圾节点
24:poly的角色模型请做成全封闭的，不能有洞（face hole
25:多uv象限的请从0,0开始从左到右，从下到上排列
26:没有非流型面（nonmanifold face），一条边有三个及以上的面共用
