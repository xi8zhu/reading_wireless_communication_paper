## A Survey of Recent Advances in Optimization Methods for Wireless Communications

OPTIMIZATION PROBLEMS IN WIRELESS COMMUNICATIONS: STRUCTURES AND CHALLENGES

Optimization Problems in Wireless Communications

+ Optimization Problems with Continuous Variables: Beamforming
  + Downlink Beamforming
    + 单基站多天线，每根天线给一个用户发消息
  + Hybrid Beamforming
    + Massive MIMO，多天线为射频链路和DA转换模块提出更高的要求，大天线阵列仅由有限数量的射频链路驱动。
  + RIS Beamforming
    + RIS会带来一次反射，这条链路和以前的直射链路相加为最后结果，优化波束成形矢量和相位偏移
  + Joint BS Clustering and Beamformer Design
    + 多基站被视为一个具有MB天线的虚拟基站。优化时保证不同基站到同一用户的稀疏性，及同一基站的功率。
    + 所有的B基站被允许共享数据并充分合作
  + Joint Downlink Beamforming and Fronthaul Compression
    + 用户与中继之间通过噪声无线信道相连，而中继与中央处理器之间则通过具有有限容量的无噪声前传链路相连。
+ Optimization Problems with Integer Variables
  + MIMO Detection
    + 根据信道矩阵 H 的知识，从接收信号向量 y 中恢复传输符号向量 s。x是用户终端传输符号的向量
  + Symbol-Level Precoding
    + 下行链路，设计发射信号，使得期望接收信号与星座点对齐
+  Optimization Problems with Mixed Variables
  + Joint Admission Control and Multicast Beamforming
    + 发射器同时向K个用户进行多播传递公共信息。那么每个接收端就没有干扰
    + 当发射器无法同时支持所有用户（例如，由于用户数量过多），则需要进行接入控制 [42], [43] 以选择一个用户子集，以满足其信噪比目标。
  + Joint Uplink Scheduling and Power Control





| 英文                | 中文                       |
| ------------------- | -------------------------- |
| impinge             | 冲击；碰撞；入射           |
| electromagnetic     | 电磁的                     |
| conjugate transpose | 共轭转置                   |
| depicted            | 用图像形式呈现的           |
| overhead            | 头顶上的。经费开销         |
| Fronthaul           | 前传                       |
| context             | 背景                       |
| constellation       | 星座                       |
| is admitted to be   | 被认为是，被允许           |
| admission           | 接入                       |
| incorporation       | 公司，引入                 |
| sporadic            | 零星的                     |
| paradigm            | 范例范式                   |
| paramount           | 首要的；至高无上的         |
| elucidate           | 阐述，说明                 |
| devise              | 设计，发明                 |
| tractability        | 温顺；驯良；易处理；可解的 |

共轭转置符号如下：\dagger
$$
A^\dagger
$$
[Latex常用数学符号总结_latex数学符号-CSDN博客](https://blog.csdn.net/wsj_jerry521/article/details/112665789)