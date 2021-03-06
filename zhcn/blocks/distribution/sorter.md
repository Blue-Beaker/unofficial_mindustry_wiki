\>[Wiki](/zhcn.md)>[方块](/zhcn/blocks.md)>[运输](/zhcn/blocks/distribution.md)>分类器
# 分类器
[![分类器](/images/block-sorter-xlarge.png)分类器](sorter.md)  
[![反向分类器](/images/block-inverted-sorter-xlarge.png)反向分类器](sorter.md)  

将标记的物品与其他物品分离.  
物品瞬间完成传输,且不会发生堵塞.  
每个方向的输入输出互相独立,互不影响.  

以下情况会阻止物品输入:
* 即将输入的物品所有可能的输出方向均堵塞时  
* 即将输入的物品会连续经过总计超过两个(反向)分类器或(反向)溢流门时

进阶技巧:合理利用分类器可以节约工厂占地面积.

### 共享属性

| 共享属性 | 数值 |  
| ---- | ---- |  
|生命值|40|  
|尺寸|1x1|
|建造时间|0.12秒|
|物品容量|无|
|移动速度|无限|
|最大连续|2|  
| 建造花费 | ![铜](/images/item-copper.png)x2 ![铅](/images/item-lead.png)x2 |
|阻挡地面单位|是|
|发光|否|
|可超速|无意义|
|enabled参数|控制是否运输物品|  
|config参数|选定物品种类|

## 分类器
![分类器](/images/block-sorter-xlarge.png)  
> 如果物品与所选种类相同,则允许其通过.否则,物品将从左边和右边输出.  

### 属性

| 属性 | 数值 |  
| ---- | ---- |  
|ID|sorter|

## 反向分类器
![反向分类器](/images/block-inverted-sorter-xlarge.png)  
> 像分类器一样处理物品,但是却向两侧输出选定的物品.  

进阶技巧:在一些情况下未配置的反向分类器可以代替连接器,更快且不会堵塞.

### 属性

| 属性 | 数值 |  
| ---- | ---- |  
|ID|inverted-sorter|
