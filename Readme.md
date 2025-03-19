# 备赛规划
## 一、小组信息及分工

| 姓名 |  核心职责 | 辅助职责 |
| :-------:|  :------: |:------: |
| 成员A  |项目整体架构设计<br>团队管理与进度控制<br>视觉系统设计 | 协助硬件制作<br>参与软件代码Review|
| 成员B  |电路设计与焊接<br>元器件选型与采购<br>硬件调试与故障排查| 辅助软硬件联调 |
| 成员C | 软硬件通信协议对接<br>程序设计与实现| 协助硬件测试 |

### 成员技术栈

| 姓名 | 类别 | 技术栈明细 | 
| :-------:| :-------: | :------: | 
| 成员A| 编程语言 | C语言 |
|  | 嵌入式视觉 | OpenMV Cam |  
|| 嵌入式基础 |HAL库/标准库|
| 成员B | 编程语言 | C语言 | 
|  | 硬件开发 | 嘉立创（PCB设计） |  
||调试工具|示波器/万用表|
| 成员C | 编程语言  | C语言 |
||嵌入式基础 | 标准库<br>HAL库配置<br>Arduino |


## 二、方向选择

控制类题目

### 两道备选题分析

#### （1）2023 年全国大学生电子设计竞赛试题----运动目标控制与自动追踪系统（E 题）

##### 题目

[E题_运动目标控制与自动追踪系统.pdf](./E题_运动目标控制与自动追踪系统.pdf) 

##### 关键点/核心需求

- 动态目标识别与定位（视觉）

- 实时运动控制（电机/舵机）

- 自动追踪算法设计（预测与反馈）

##### 难点

- 目标丢失

- 两装置配合

- 复杂光照干扰


##### 所需技术栈

- 云台使用

- 视觉模块

- 电路板设计

- 代码编程

#### （2）2021 年全国大学生电子设计竞赛试题----智能送药小车（F 题）

##### 题目

[智能送药小车（F题）.pdf](./智能送药小车（F题）.pdf) 

##### 关键点/核心需求

- 循迹

- 数字识别和路径规划（算法）

- 任务调度优化（多目标决策）


##### 难点

- 道路径规划

- 多车协同调度

- 实际调车



##### 所需技术栈

- 嵌入式开发
  
- 电路板设计

- 代码编程

- 视觉模块


## 三、设备清单

### （一）工具

#### （1）硬件工具

##### 焊接工具

- 电烙铁

- 焊锡丝（含松香芯）、吸锡器/吸锡线

- 助焊剂、镊子

##### 测量与调试设备

- 万用表

- 示波器

- 可调直流稳压电源

##### 电路搭建工具

- 面包板、洞洞板（万能板）

- 杜邦线（公对公、母对母、公对母）

- 螺丝刀

- 鳄鱼夹、排针、排座

- 电源模块（如LM2596降压模块、升压模块）

##### 其他工具

- 斜口钳、压线钳

- 热熔胶枪（固定元件）


#### （2）软件工具

##### 电路设计与仿真

- PCB设计：嘉立创

##### 嵌入式开发

- 编程环境：Keil（ARM）、Arduino IDE、STM32CubeIDE、VSCode

##### 辅助工具

- 版本控制：Git + GitHub

- 文档编写：Markdown


### （二）硬件材料

- 舵机云台×2
- 总线舵机(SG90入门 随后换)×4
- 红色激光笔×1
- 绿色激光笔×1
- 视觉模块(openMv H7)×2
- 电源18650 ×2
- STM32F103c8t6系统板×2
- 电机驱动TB6612 x6
- 小车底盘×4
- 310电机×8
- 红外感应模块
- 灰度循迹模块




## 四、学习计划

- 3.16 ----  4.11   基本完成题目一

- 4.14 ----  5.09    基本完成题目二（依据进度完善题目一）

### 成果提交方式

- github 代码开源
- 实物展示

### 精确到周

#### 项目规划阶段（第1周）

- 成员A：制定时间表

- 成员B：制定硬件需求清单，完成初步电路框图

- 成员C：搭建软件开发环境，确定主控板

#### 设计与开发阶段（第2-4周）

- 成员A：整理测试用例，完成视觉方面的任务

- 成员B：完成PCB制版、焊接与硬件功能验证

- 成员C：编写核心代码模块（如传感器驱动、通信协议）

#### 调试与优化阶段（第5周）

- 

- 每周开展15分钟进度短会，同步问题
