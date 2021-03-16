\>[Wiki](/zhcn.md)>[方块](/zhcn/blocks.md)>[电力](/zhcn/blocks/power.md)>能量节点
# 能量节点
[![能量节点](/images/block-power-node-xlarge.png)能量节点](power-node.md)  
[![大型能量节点](/images/block-power-node-large-xlarge.png)大型能量节点](power-node.md)  
[![波动能量塔](/images/block-surge-tower-xlarge.png)波动能量塔](power-node.md)  

通过能量激光将设备并入电网,用于传输电力.  

建造前会预览将自动连接的目标,但此预览不一定准确: 蓝色标记表示将连接该设备; 绿色标记表示自动连接被该方块阻挡  

点击可手动配置连接: 点击范围内其他电力设备可连接/断开该设备, 此状态下再次点击可断开所有连接(如未连接任何设备,则尝试自动连接)  

### 共享属性

| 属性 | 数值 |  
| ---- | ---- |  
|阻挡地面单位|是|
|发光|仅能量激光|
|可超速|否|
|enabled参数|无效|  
|config参数|无|

## 能量节点
[![能量节点](/images/block-power-node-xlarge.png)能量节点](power-node.md)  

>向连接的节点传输电力.该节点将从任何相邻的块接收电力或向其供电.

### 属性

| 属性 | 数值 |  
| ---- | ---- |  
|ID|power-node|
|生命值|40|  
|尺寸|1x1|
|建造时间|0.04秒|
| 建造花费 | [![铜](/images/item-copper.png)](/zhcn/items/copper.md)x1 [![铅](/images/item-lead.png)](/zhcn/items/lead.md)x3 |
|连接范围|6|
|连接数|10|

## 大型能量节点
[![大型能量节点](/images/block-power-node-large-xlarge.png)大型能量节点](power-node.md)  

>具有更大范围的高级电源节点.

性价比低下,尽量少用.

### 属性

| 属性 | 数值 |  
| ---- | ---- |  
|ID|power-node-large|
|生命值|160|  
|尺寸|2x2|
|建造时间|0.24秒|
| 建造花费 | [![铅](/images/item-lead.png)](/zhcn/items/lead.md)x10 [![钛](/images/item-titanium.png)](/zhcn/items/titanium.md)x5 [![硅](/images/item-silicon.png)](/zhcn/items/silicon.md)x3 |
|连接范围|9.5|
|连接数|15|

## 波动能量塔
[![波动能量塔](/images/block-surge-tower-xlarge.png)波动能量塔](power-node.md)  

>可用连接较少的远程电源节点.

由于连接数少,建议相邻放置其他电力设备接收其他节点的连接以节约自身的连接数.

### 属性

| 属性 | 数值 |  
| ---- | ---- |  
|ID|surge-tower|
|生命值|160|  
|尺寸|2x2|
|建造时间|0.73|
| 建造花费 | [![铅](/images/item-lead.png)](/zhcn/items/lead.md)x10 [![钛](/images/item-titanium.png)](/zhcn/items/titanium.md)x7 [![硅](/images/item-silicon.png)](/zhcn/items/silicon.md)x15 [![巨浪合金](/images/item-surge-alloy.png)](/zhcn/items/surge-alloy.md)x15 |
|连接范围|40|
|连接数|2|
