# MP2565 评估板 V1.0 
## PCB正反面
![](https://github.com/oldgerman/MP2565_EVM_V1/image/View.jpg)
## 原理图
![](https://github.com/oldgerman/MP2565_EVM_V1/image/Eagle_Sch.png)
## 参数
典型输出5V/2.5A, 建议输入电压12-24V
## 适用MP1584
此电路板基本按照datasheet的示例布板
修改R4为24.9k可以Pin to Pin使用MP1584，对于MP2565，R4为17.4k，详见datasheet P15和P16
## MP2565 与 MP1584
MP2565相当于MP1584的高压版本，相比MP1584，MosFet耐压从28V提高到50V，对24V电压降压稳压更保险
## PCB尺寸
![](https://github.com/oldgerman/MP2565_EVM_V1/image/Eagle_Brd.jpg)
