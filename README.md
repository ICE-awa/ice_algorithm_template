**当前最新普通版发布版本为v1.0.0-alpha.1，最新打印版为v1.0.0-alpha.1(总词数约2.5w(含代码))**

成品为 `template_v1.0.0-alpha.1.pdf` (请移步至[release](https://github.com/ICE-awa/ice_algorithm_template/releases/tag/v1.0.0-alpha.1)中下载)

<span style="text-decoration:line-through">5月份之前应该都不会更新模板，要备战武汉邀请赛</span>

<hr/>

## 模板简介

这是一份适用与算法竞赛的 C++ 代码模板集合。目前版本为本人总结的之前已经学习的算法，并且部分算法有自己基于算法的理解以及网上优秀教程总结出的教程，但不是所有的算法都拥有教程，并且许多基础的内容并未收录。

大部分算法都有对应的例题链接。

有部分模板使用了class封装，有一些因为时间仓促还未进行封装。

此模板除了特殊说明，一般下标**都是从1开始(1-based)**

本模版用时一周半制成，因时间仓促，难免出现纰漏以及错误之处，如果您发现了任何错误之处或者对本模板有改进建议，欢迎您提出！！

本模板参考了<a href="https://codeforces.com/profile/jiangly"><span style="font-weight:bold">jiangly</span></a>封装的模板以及<a href="https://github.com/lr580" style="font-weight:bold">lr580的模板库</a>



## 参考目录

```markdown
🧊's Algorithm Template
	数学
		排列组合
			排列
			组合
	数论
		加性函数和完全加性函数
		积性函数和完全积性函数
		费马小定理
		欧拉函数
			欧拉反演
		欧拉定理
		扩展欧拉定理
		素数
			判断素数
			欧拉筛
		快速幂
	计算几何
		扫描线
	字符串
		KMP
		字典树(Trie)
	图论
		基本概念
			二分图是什么
			匹配
			最大匹配
			增广路
			网络
			残量网络
		匹配问题
			匈牙利算法(二分图最大匹配)
		建边
			邻接表
			链式前向星
		拓扑排序
		tarjan实现缩点
		最小生成树
			Prim
			Kruskal
		单源最短路
			Dijkstra
			SPFA
			Bellman-Ford
		全源最短路
			Floyd
			Johnson算法
		最近公共祖先(LCA)
			倍增法求LCA
			Tarjan求LCA
		网络流
			最大流
				EK算法
				Dinic算法
			最小费用最大流
				SPFA+EK实现
				Dijkstra+EK实现
	数据结构
		并查集
		线段树
			不带LazyTag的普通线段树(Info)
			带LazyTag的懒线段树(Info, Tag)
		平衡树
			Splay
		树状数组
			模板
			单点修改和区间求和
			区间修改和单点求和
			使用树状数组求逆序对
		ST表
		二叉树
	动态规划
		背包
			01背包
			完全背包
			多重背包
			分组背包
			二维01背包
	杂项
		__int128的使用
		快读&快写
			整数类型通用模板(int, long long, __int128)
			浮点数快读
		随机数以及对拍
			随机数生成
			随机数生成代码
			对拍脚本
				Linux/MacOS(check.sh)
				Windows(check.bat)
		前缀和
			一维求和前缀和
			一维异或前缀和
			二维求和前缀和
		差分
			一维差分
			二维差分
		滑动窗口
		二分
			手写二分
			STL二分写法
		STL函数
			max_element
			min_element
			next_permutation
			prev_permutation
			greater
			less
			unique
			reverse
			shuffle
		STL
			vector
			stack
			array
			set
			multiset
			map
			queue
			priority_queue
			deque
			list
```



## 更新日志

* 2025/04/08 (v1.0.0-alpha.1)

​	发布了v1.0.0-alpha.1版本的模板