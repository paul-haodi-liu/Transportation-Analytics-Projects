# Transportation-Analytics-Projects

This is the group project of the course IEOR 4418 Transportation Analytics and Logistics at Columbia. I collaborated with my 
classmates Eric Chang, Zhuangzhuang Jia, Madeline Temares and Sijie Wang to complete the uploaded materials.

In this project, we studied different morning setups of shared scooters in Louisville and examined their performances in capturing(satisfying) arrived demands of customers. We built a simulation system to simulate the movements of the scooters in Louisville as well as the arrivals of customers’ demands based on the data published by companies running the business (such as Lime and Bird). The underlying mathematical model involved concepts such as discrete-time Markov Chain and Poisson Process. Equipped with the simulation system, we were able to gain better insights into scooters’ movements, demand arrivals and demand captures. I believe that the companies running the business of scooters could utilize our system to experiment with different morning setups on top of their abundant business experience and data. While working closely with my teammates, I was mainly in charge of the design of the mathematical model supporting our simulation system. I tried to incorporate some concepts of stochastic process into our system and wrote a report to justify their usages. 

这是我们在哥大课程 IEOR 4418 交通/物流分析中所做的团队项目。整个项目由我和我的队友 Eric Chang, Zhuangzhuang Jia, Madeline Temares 和 Sijie Wang 一起共同完成。

我们的项目建立了一个针对肯塔基州路易斯维尔市内共享滑轮车的流动以及用户需求的到达的仿真系统，数学模型里利用了随机过程中离散时间马尔可夫链，转移概率矩阵来仿滑轮车的流动，利用泊松过程来仿用户需求的到达，用python语言和pandas包裹来实现数据分析和仿真。 通过仿真系统以及随后的数据分析，我们能够洞悉出滑轮车流动和用户需求被满足情况的规律和特征。运营公司能够利用我们的仿真系统试验不同的滑轮车在早晨的区域分布方法，以避免实际试验中的一些成本昂贵，过程冗长等等障碍因素。最终目的是找出一个区域分布方法使得尽量多的到达的需求被满足。

我在此项目里扮演的角色主要是帮助设计支撑仿真系统的数学模型，尝试将随机过程中的一些理论概念应用进去并写报告以证明其正当性。我同时还跟组员一起全程参与对项目问题的思考和仿真系统的设计建造。

Louisville Scooters.pptx是我们项目的展示幻灯片。
Scooters Data Analysis.ipynb 是我们项目的源代码。
report.pdf 是我们项目的书面报告。
其余的csv文档是我们项目用到的数据，export中是根据数据生成出来的路易斯维尔市内的滑板车流动的分布图。

