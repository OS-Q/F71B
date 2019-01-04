# M5：[无线终端](https://github.com/OS-Q/M5) 

[![sites](OS-Q/OS-Q.png)](http://www.OS-Q.com)

#### 归属边缘通信：[Q2](https://github.com/OS-Q/Q2)

#### 关于系统架构：[OS-Q](https://github.com/OS-Q/OS-Q)

## [节点描述](https://github.com/OS-Q/M5/wiki) 

M5无线终端节点，作为终端设备集成通信和控制功能，处理各种控制事件

### [共用资源](OS-Q/)

#### [数据处理](IO/)

各种数据组帧和处理

#### [系统化层](OS-Q/)

系统开发归一化接口

---

- 边缘设备命名规则：体系 Q:[1,4] -> 节点 M:[1,12] -> 平台 W:[1,52] -> 设备 D:[1,365]

- naming patterns：system Q[1,4] -> node M[1,12] -> platform W[1,52] -> device D[1,365]

## [包含平台](https://github.com/OS-Q/M5/wiki) 

#### W18：[被动通信](https://github.com/OS-Q/W18)

被动触发唤醒进行相应的交互

#### W19：[定时通信](https://github.com/OS-Q/W19)

用于低频次定时数据通信控制

#### W20：[实时通信](https://github.com/OS-Q/W20)

用于实时的无线数据交互控制

#### W21：[智能组网](https://github.com/OS-Q/W21)

通信节点间智能策略组合通信

#### W22：[交互控制](https://github.com/OS-Q/W22)

基于人机交互的无线通信控制

## [同级节点](https://github.com/OS-Q/Q2/wiki)

#### M4：[桥接管道](https://github.com/OS-Q/M4)

作为上下层级设备控制的通信管道

#### -> M5：[无线终端](https://github.com/OS-Q/M5)

集成无线通信和边缘控制终端设备

#### M6：[数据网关](https://github.com/OS-Q/M6)

数据中转节点，数据的汇集和处理

---

####  © qitas@qitas.cn
###  [OS-Q redefined Operation System](http://www.OS-Q.com)
####   @  2019-1-4
