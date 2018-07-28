# GA_tsp
TSP问题是指假设有一个旅行商人要拜访n个城市，他必须选择所要走的路径，路径的限制是每个城市只能拜访一次，而且最后要回到原来出发的城市。路径的选择目标是要求得的路径路程为所有路径之中的最小值。使用遗传算法解决att48问题，即48个城市的旅行商问题，该问题目前的最优解是10628，受个别参数影响，所设计的算法所得到的最优结果是10648，相对误差为0.18818216%。

att48.txt ----- 48个城市的坐标

CalDist.m ----- 计算个体的总路径

cro.m --------- 交叉函数

drawTSP.m ----- 根据坐标作图

GA.m ---------- 主函数

mut.m --------- 变异函数

objf.m -------- 适应度函数

pro.m --------- 判断是否需要变异、交叉

sel.m --------- 选择函数

tsp.m --------- 读取att48坐标，并计算每两个城市之间的距离
