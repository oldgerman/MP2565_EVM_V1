# MP2565 评估板 V1.0 

## PCB尺寸

![](https://github.com/oldgerman/MP2565_EVM_V1/blob/master/image/Eagle_brd.jpg)

## B.O.M

| Column1 | Column5   | Column6 |
| ------- | --------- | ------- |
| C1      | 10uF/50V  | 1206    |
| C2      | 22uF/16V  | 1206    |
| C3      | 150pF/50V | 0603    |
| C4      | 100nF/50V | 0603    |
| D1      | SS34F     | SMAF    |
| L1      | 15uH      | L0630   |
| R1      | 210k      | 0603    |
| R2      | 40.2k     | 0603    |
| R3      | 100k      | 0603    |
| R4      | 17.4k     | 0603    |
| R5      | 100k      | 0603    |
| R6      | 200k      | 0603    |
| U1      | MP2565DN  | ESOP8   |
| J1 J2   | KP301-2P  | 3.81mm  |

## 参数

典型输出5V/2.5A, 建议输入电压12-24V，开关频率500KHz

## 适用MP1584

此电路板基本按照datasheet的示例布板，修改R4为24.9k可以Pin to Pin使用MP1584，对于MP2565，R4为17.4k，详见datasheet P15和P16

## MP2565 与 MP1584

MP2565相当于MP1584的高压版本，相比MP1584，MosFet耐压从28V提高到50V，对24V电压降压稳压更保险

