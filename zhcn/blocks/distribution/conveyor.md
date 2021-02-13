\>[Wiki](/zhcn.md)>[方块](/zhcn/blocks.md)>[运输](/zhcn/blocks/distribution.md)>传送带
# 传送带
[![传送带](/images/block-conveyor-xlarge.png)传送带](conveyor.md)  
[![钛传送带](/images/block-titanium-conveyor-xlarge.png)钛传送带](titanium_conveyor.md)  
[![装甲传送带](/images/block-armored-conveyor-xlarge.png)装甲传送带](armored_conveyor.md)  
将物品向前输送.优先接受后方的输入.  
启用且未堵塞时,也会移动大部分地面单位.  
注意:[塑钢传送带](plastanium_conveyor.md)和[载荷传送带](payload_conveyor.md)不属于传送带.

### 共享属性

| 共享属性 | 数值 |  
| ---- | ---- |  
|尺寸|1x1|
|物品容量|4 任意物品(实际往往为2~3物品)|
|阻挡地面单位|否|
|发光|否|
|可超速|是|
|enabled参数|控制是否运输物品|  
|config参数|无|

## 传送带
![传送带](/images/block-conveyor-xlarge.png)  
> 将物品向前输送.

### 属性

| 属性 | 数值 |  
| ---- | ---- |  
|ID|conveyor|
|生命值|45|  
|建造时间|0.01秒|
|移动速度|4.1 物品/秒|
| 材料消耗 | ![铜](/images/item-copper.png)x1 |


## [钛传送带](titanium_conveyor.md)
![钛传送带](/images/block-titanium-conveyor-xlarge.png)  
> 将物品向前输送.快于初级传送带.

速度与[装甲传送带](armored_conveyor.md)相同.  

### 属性

| 属性 | 数值 |  
| ---- | ---- |  
|ID|titanium-conveyor|
|生命值|65|  
|建造时间|0.03秒|
|移动速度|11 物品/秒|
| 材料消耗 | ![铜](/images/item-copper.png)x1 ![铅](/images/item-lead.png)x1 ![钛](/images/item-titanium.png)x1 |

## [装甲传送带](armored_conveyor.md)
![装甲传送带](/images/block-armored-conveyor-xlarge.png)  
> 向前方移动物品.不接受边上的输入.

速度与[钛传送带](titanium_conveyor.md)相同.  
两侧只接受[传送带](conveyor.md),[钛传送带](titanium_conveyor.md)和装甲传送带的输入,后方可接受任何输入.  
可用于阻止来自相邻方块的不需要的输入,便于建造紧凑的生产线.

### 属性

| 属性 | 数值 |  
| ---- | ---- |  
|ID|armored-conveyor|
|生命值|180|  
|建造时间|0.06秒|
|移动速度|11 物品/秒|
| 材料消耗 | ![钢化玻璃](/images/item-metaglass.png)x1 ![钍](/images/item-thorium.png)x1 ![塑钢](/images/item-plastanium.png)x1 |
