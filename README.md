#第四次作业  

##人口增长模型  

##背景

简易的人口增长模型可以由微分方程给出，dN/dt=aN-bN^2，N表示人数，aN表示出生的人口数量，bN^2表示死亡人数随着资源的消耗。

##数值解微分方程

首先忽略bN^2对人口总数的影响，b=0，a=10,N(0)=1000,dt=1,情况下的图像  

[程序](https://github.com/Wangzhengwhu/Homework-4/blob/master/%E4%BA%BA%E5%8F%A3%E7%A8%B3%E5%AE%9A%20b%3D0.py)

![b=0人口增长模型](https://github.com/Wangzhengwhu/Homework-4/blob/master/%E4%BA%BA%E5%8F%A3%E7%A8%B3%E5%AE%9Ab%3D0.png)  

其次我们考虑bN^2对人口增长的模型影响，其它参数如上，b=0.02模型下计算的结果，画出图像

[程序](https://github.com/Wangzhengwhu/Homework-4/blob/master/%E4%BA%BA%E5%8F%A3%E7%A8%B3%E5%AE%9A%20b%3D0.02.py)  
![b=0.02人口增长模型](https://github.com/Wangzhengwhu/Homework-4/blob/master/%E4%BA%BA%E5%8F%A3%E7%A8%B3%E5%AE%9Ab%3D0.02.png)   
从图像上我们看出当b=0.02时人口成负增长，当我们改变参数，将b=0.01的情况下，我们可以看到人口呈稳定趋势。  

##致谢
感谢刘星辰同学和遥大仙的帮助




