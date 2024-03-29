# 4.1.1.概览

超级管理员在“资源管理”菜单下选择左侧“概览”的导航菜单，即可看到概览界面：

![image-20210127105245683](zone_summary.assets/image-20210127105245683.png)

主页主要对选定区域的数据中心资源实时状态进行直观的展示。

用户可以点击总览上方的“区域选择”下拉框选择相应的区域查看资源的利用率以及主要资源的使用情况。

主页界面主要分为“资源使用总览”、“资源概览”、“虚拟机数量趋势”和“组织资源消耗TOP5”这四个部分。

## 资源使用总览

#### ![1597746993057](zone_summary.assets/1597746993057.png)

根据当前所选区域的全部主机CPU、内存、磁盘、GPU资源的使用情况进行统计分析。

用环形图实时显示当前区域CPU、内存、主存储、二级存储、GPU资源已用量和可用量的占比情况。

其中用白色显示资源可用量，根据使用情况用蓝色、橙色、红色显示资源使用量：

- 蓝色：用量占比在0%-60%的状态下使用量显示为蓝色；
- 橙色：用量占比在60.01%-80%的状态下使用量显示为橙色；
- 红色：用量占比在80.01%-100%的状态下使用量显示为红色。

> *注：
>
> - 若当前区域下没有该资源，则显示灰色圆饼图，标记暂无资源。
>
>   ![1597747084726](zone_summary.assets/1597747084726.png)

## 资源概览

![image-20210127105324437](zone_summary.assets/image-20210127105507731.png)

实时显示所选区域中主机、虚拟机、虚拟磁盘等8大资源的概览情况。

- 主机：左侧显示所选区域中的主机总数，右侧分别显示运行中、关闭和其他（离线和报警）状态的主机数量；
- 虚拟机：左侧显示所选区域中的虚拟机总数，右侧分别显示运行中、关闭和待销毁状态的虚拟机数量；
- 虚拟磁盘：左侧显示所选区域中的虚拟磁盘总数，右侧分别显示已挂载和未挂载状态的虚拟磁盘数量；
- 公网IP：左侧显示所选区域中的公网IP总数，右侧分别显示剩余和已用状态的公网IP数量；
- 快照：左侧显示所选区域中的虚拟机快照总数；
- 备份：左侧显示所选区域中的磁盘备份总数；
- 镜像：右侧分别显示所选区域中社区、精选和私有镜像的数量；
- 网络：左侧显示所选区域中的网络总数，右侧分别显示隔离、共享和专有网络（VPC）的数量。

> *注：
>
> - 点击蓝色数值，将会跳转到相应的管理页面。

## 虚拟机数量趋势

<img src="zone_summary.assets/1597747841838.png" alt="1597747841838" style="zoom:50%;" />

实时显示所选区域中近六个月虚拟机的月初存量、当月新增和月末存量趋势图。

> *注：
>
> - 鼠标悬停时，可以查看选定时间节点虚拟机的月初存量、当月新增和月末存量。

## 组织资源消耗TOP5

<img src="zone_summary.assets/image-20210127105718545.png" alt="image-20210127105718545" style="zoom:50%;" />

实时显示所选区域中内各个公司的各个部门资源消耗的TOP5，默认统计的是虚拟机消耗数量的排名，也可选择查看各个部门CPU、内存、存储消耗数量的TOP5排名。

> *注：
>
> - 此处统计以部门为维度进行统计，即根据所有公司下的所有部门进行数据对比排名。