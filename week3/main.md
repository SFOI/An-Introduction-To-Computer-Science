---
marp: true
theme: gaia
---
<!-- class: lead -->
# Design Thinking

设计思维

Qin Feiran, SIST, ShanghaiTech University

canarypwn@aosc.io

---
<!-- class: default -->
## 为什么要谈论设计思维

- 个人的经验难以推广到普适的经验
- 需要一种系统的方法来指导创新
- Standard Operation Procedure (SOP)
- 但不要被设计思维限制住了，同学上完设计思维之后都觉得这是全校最糟糕的课之一 (因为每次上课都在演讲讨论，变成 PPT 课了，很多项目都被矫正的完美符合了设计思维的要求但是没有人会觉得那是一个好项目)。

---

## 《设计思维》六部曲

- 第一部：感知需要（聚集、发散、反复锤炼）
- 第二部：定义需要
- 第三部：根据需要进行创想
- 第四部：形成潜力型可被测试的解决方案
- 第五部：检测解决方案
- 第六部：总结、归纳、迭代、实施最有效的解决方案

---

## 可行性研究

- 确定这个课题是否值得做
  - 有没有很好的意义和应用
  - 性价比高不高
  - 从备选方案中找到最佳方案
  - 在法律法规，政策，经济的角度考虑后续的发展  （例如`好位搜`）s

---

## 可行性研究

- 操作可行性 Operational Feasibility
  - 假如现在实现了你的想法以后，使用者、相关方会有什么变化
- 技术可行性 Technical Feasibility
  - 能不能做出来
- 进度可行性 Schedule Feasibility
  - 能不能在能接受的时间内用掌握的技术实现
- 其它可行性
  - 财务，市场，监管，组织 ...

---

## 可行性研究需要包括的部分

- 摘要
- 导论 (What's going on now)
- 背景 (How are we doing?)
- 需求 (What's needed?)
- 可行性研究 (Can we do it?)
- 进度安排

---

## 机会识别
机会识别就是发现生活中的值得解决的问题

---
## 机会识别中的问题假设的模板

- 在 XXX 的场景下，我们相信人们都是 [怎么样的] ，他们需要的是 [什么功能]，但不能通过 [已有的方案] 解决，因为已有方案存在 [怎么样的] 缺陷或者 [怎么样的] 限制。

- 通过 [我们的课题]，实现了 [什么功能]，解决了之前的问题。
- 是否定义了一个尚未解决的重要痛点问题？

---
由于版权原因，我无法公开的提供直播时的 slides。

---
# 样例分析
夏老师给我提供了一些计算机方向的课题，我可以提供简单的点评的想法
- 导盲杖
- 语言障碍者的输入输出装置
- 方向盘压力和温度传感器用于安全驾驶
- 计算机广告
- 图书馆进货与推荐

---
## 导盲杖
- 我比较怀疑安装了超声波传感器的导盲杖是否有效，因为它可能没有很强的指向性。
- [Effective navigation for visually impaired by wearable obstacle avoidance system](https://doi.org/10.1109/ICCEET.2012.6203916) 可穿戴设备为视觉障碍者提供了一个有效的导航方法。可以关注它的[引用](https://scholar.google.com/scholar?cites=9883671938242702034&as_sdt=2005&sciodt=0,5&hl=zh-CN)
- 我们社团有一个项目是把 iPhone 反过来挂在胸前，用 ToF 镜头来对前方建模，可以参考一下 (轻巧的可穿戴设备)
- 从设计思维的角度说，现在淘宝上已经有智能导盲杖了(虽然很贵，也就是说做便宜是有优势的)，要想想和它们有创新的地方。

---
## 语言障碍者的输入输出装置
- 我对这方面很不熟悉
- [A wearable fabric-based speech-generating device: system design and case demonstration](https://doi.org/10.1080/17483107.2018.1462860) 用织物代替按钮
- 研究一下现有产品和需求，以及为什么比现在的好

---
## 方向盘压力和温度传感器用于安全驾驶
- 感觉和特斯拉的那个必须要手放到方向盘上有点像
- [Dangerous driving behavior detection using smartphone sensors](https://doi.org/10.1109/ITSC.2016.7795864) 用手机来检测不安全驾驶行为
- [Driver Behavior Analysis for Safe Driving: A Survey](https://doi.org/10.1109/TITS.2015.2462084)
- [Estimating driving behavior by a smartphone](Estimating driving behavior by a smartphone)
- 如果能退一步，用 Arduino 来代替手机实现也是不错的选择

---
## 计算机广告
- [Reinforcement learning based recommender systems: A survey](https://doi.org/10.48550/arXiv.2101.06286) 用机器学习去推荐广告 (熊老师好像是做这个的)
- 不过我看到你的原报告的措辞不是很清楚，可以用 DT 的思想再完整的考虑一下，比如投放广告的公司是不是有这个需求。会影响哪些相关方，用户真的会更喜欢吗，你的基于马斯洛的理论有事实与实验上能量化的依据吗，做一下可行性研究。

---
## 图书馆进货与推荐
- 有一个好处是这个课题很符合高中生的身份
- 也可以拿神经网络去试试有什么结果
- 我觉得在设计思维上可以再考虑一下，比如去做一下可行性研究，研究图书馆的进货是怎么样的，现在想学生想要书有没有什么地方可以提出来，如果有的话是不是可以在这个网页上做一些事情。做几天志愿者，了解一下相关政策。上大附中图书馆我觉得有很大的改进空间。
- 用朴素的排序算法还是深度学习都可以，我觉得重点在管理流程上的改进。

---
## 应对大学学习应该学什么技术？
- Calculus: https://www.wolframalpha.com/problem-generator/?scrollTo=Calculus
- https://www.bilibili.com/video/BV1Qs411y7ma
- 程稼夫物理系列
- 上科大计算机引论 https://space.bilibili.com/510013499/ (这个不全，s或者其它类似物，比如 CSAPP)
- 准备 NOIP 计算机奥赛 (比如去洛谷)


---
<!-- class: lead -->
# All the Resouces can be Found at 

[https://github.com/SFOI/An-Introduction-To-Computer-Science](https://github.com/SFOI/An-Introduction-To-Computer-Science)