# Q1：[边缘控制](https://github.com/OS-Q/Q1) 

[![sites](OS-Q/OS-Q.png)](http://www.OS-Q.com)

#### 归属边缘设备：[Edge](https://github.com/OS-Q/Edge-Q)

#### 关于系统架构：[OS-Q](https://github.com/OS-Q/OS-Q)

## [体系描述](https://github.com/OS-Q/Q1/wiki) 

Q1边缘控制体系，用于对底层设备实施监控和管理，设备主要面向物理世界，处于数据的生产和消费的最前端，通过通信和计算协同接入系统其他资源。

### [共用资源](https://github.com/OS-Q/Q1/wiki)

#### [通信协同规范](Q2/)

Q1控制体系和Q2通信体系协同相关规范

#### [计算协同规范](Q3/)

Q1控制体系和Q3计算体系协同相关规范

---

- 边缘设备命名规则：体系 Q:[1,4] -> 节点 M:[1,12] -> 平台 W:[1,52] -> 设备 D:[1,365]

- naming patterns：system Q[1,4] -> node M[1,12] -> platform W[1,52] -> device D[1,365]

## [包含节点](https://github.com/OS-Q/Q1/wiki/) 

#### M1：[输入控制](https://github.com/OS-Q/M1)

控制外接信号输入，完成数据采集过程

#### M2：[输出控制](https://github.com/OS-Q/M2)

控制对外信号输出，完成数据消费过程

#### M3：[集成控制](https://github.com/OS-Q/M3)

集成相关资源，组合完成预定控制逻辑

## [设备体系](https://github.com/OS-Q/Edge-Q/wiki/)

#### [Q1：边缘控制](https://github.com/OS-Q/Q1) 

用于执行Q系统数据生产消费的边缘设备体系

#### Q2：[边缘通信](https://github.com/OS-Q/Q2)

用于执行Q系统数据转移运输的边缘设备体系

#### Q3：[边缘计算](https://github.com/OS-Q/Q3)

用于执行Q系统数据处理加工的边缘设备体系

#### Q4：[弹性计算](https://github.com/OS-Q/Q4)

用于支撑Q系统临时资源需求的边缘设备体系

---

####  © qitas@qitas.cn
###  [OS-Q redefined Operation System](http://www.OS-Q.com)
####  @ 2018-12-31
