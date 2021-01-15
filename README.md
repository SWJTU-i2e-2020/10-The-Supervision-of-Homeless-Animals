# 项目名称和作者
> 项目名称：流浪动物保护监测(The Supervision of Homeless Animals for Production)

> 作者：汪世季(Shiji-Wang)，沈之航(ZHShen7)，雷芸嘉(chlorine27)，何彪瑞(hbr-111)，王新雨(Xinyu-Wang28)，刘博雅(Chenanyee)

# 问题定义
> 本次设计旨在监测这些流浪动物们的位置及其生命体征，例如体温、心率等，当流浪动物身体出现状况时，方便一些保护它们的人或组织更方便地进行救助。

> 需求分析：

> 动物保护是人类社会发展下随处可见的永恒性话题，而其中集于聚光灯下的大多是珍稀动物。固然，保护珍稀野生动物十分重要，但对于身边流浪动物的保护与监测同样不可忽视。据调查显示，自2014年以来，中国养宠家庭数量的年增速便保持在10%以上且呈现持续加快的态势。而到2018年，中国养宠用户已高达7355万人并仍在持续提速增长。

> 虽然养宠人士数量激增，但爱宠人士的数量并不可观。由于种种原因，大量宠物遭受遗弃，沦落街头成为了流浪动物。在全球大约有6亿只狗狗，但其中流浪狗就占了三分之一，而在中国，每年都有会不少于4000万只狗狗在流浪，明是拥有13亿人口的大国，却难以为这小小的4000万流浪狗找到一个家，不仅如此，狗狗的数量通常与人口数量成正比，人口增长得越快，意味着狗狗的数量越多，随之而来是更严峻的流浪狗数量大增的问题。

> 流浪动物的问题不仅出现在社会生活中，在我们的校园里也很常见。在偌大的校园内，有许许多多无家可归的小动物。每当刮风或是下雨，酷暑或是寒冬，我们不知道他们是否会生病，是否会感受到炎热与寒冷。也许我们无法保证让每一个流浪动物都有一个家，但我们应该在它们有困难的时候向它们施以援手，让每一个小动物都感受到爱与温暖。对于很多喜爱动物的同学来说，流浪的猫猫狗狗们的日常情况以及身体状况就犹为牵人心肠。为了改善流浪动物的生存现状，校园里许多热心的同学愿意主动提供一些帮助，但又多次无奈于想提供帮助时，很难准确找到流浪动物的位置，有时可能带好了一些帮助物资，却因无法确定小动物的位置而无功而返。于是，我们根据此背景，确定了课题的大致方向。

> 具体需求分析：

> 1、 同学们想要实时得到校园里的流浪动物的位置，能够在有限的时间里完成高效而有用的帮助。

> 2、 同学们希望可以能够监测小动物的体征以确认它们的安全并了解它们的身体健康状况，防止某些意外事故发生。

> 3、 对于学校而言，无法避免流浪动物的出现，那么更好的选择就是有序管理流浪动物，保证在校人员与流浪动物和谐共处。

> 需求列表(含特点和指标)

| 技术指标	 |Demand	 | Wish |
| --------------- | --------------- | --------------- |
| 技术指标 | 覆盖校园（半径1km） | 在城市范围监测 |
| 位置监测距离 |体温、心率	| 综合分析健康状态|
| 生命体征监测 |6小时	   |  缩短周期，实现连续性监测和分析|
| 续航 | 1星期 | 一个月 |

> 根据需求，打算设计一个产品，附着在动物身上。可以实现测量动物生命体征(如心率、体温等)，还要获取动物的位置，以找到他们。

# 概念设计

> 一，动物项圈，通过项圈上一个小密封盒子，在其中存放测量生命体征（如体温、心率等）和定位等模块

> 二，动物衣服，通过在衣服靠近心脏位置缝合一个密闭的口袋，在其中存放实现各种功能的模块

> 概念草图

| 功能/概念	| 动物项圈 | 动物衣服 |
| --------------- | --------------- | --------------- |
| 定位 | [项圈定位](http://m.qpic.cn/psc?/V10g6WxY2ZUSCt/TmEUgtj9EK6.7V8ajmQrEF8YGrkylDVoUOi.i.GVzZj.Sqi70LDCp*n9h0lP4jjyJB7azxkq5WlEQUYtjNZlrpxgQJY5tY6.g2UY3lVaiqE!/b&bo=AQYACAEGAAgBGT4!&rf=viewer_4) | [衣服定位](http://a1.qpic.cn/psc?/V10g6WxY2ZUSCt/bqQfVz5yrrGYSXMvKr.cqYGHI9d3ABTgttll7GVjuA5hiIWbshYvDslAFf6cVoxKjlswk9tpC3ja58ykuu*7YmlwOmUZZKNdDkEOSwsiJb0!/b&ek=1&kp=1&pt=0&bo=AQYACAEGAAgBGT4!&tl=3&vuin=693763009&tm=1607317200&sce=60-4-3&rf=viewer_4)| 
|  体温监测 	| [项圈体温监测](http://m.qpic.cn/psc?/V10g6WxY2ZUSCt/TmEUgtj9EK6.7V8ajmQrEF8YGrkylDVoUOi.i.GVzZj.Sqi70LDCp*n9h0lP4jjyJB7azxkq5WlEQUYtjNZlrpxgQJY5tY6.g2UY3lVaiqE!/b&bo=AQYACAEGAAgBGT4!&rf=viewer_4) | [衣服体温监测](http://a1.qpic.cn/psc?/V10g6WxY2ZUSCt/bqQfVz5yrrGYSXMvKr.cqYGHI9d3ABTgttll7GVjuA5hiIWbshYvDslAFf6cVoxKjlswk9tpC3ja58ykuu*7YmlwOmUZZKNdDkEOSwsiJb0!/b&ek=1&kp=1&pt=0&bo=AQYACAEGAAgBGT4!&tl=3&vuin=693763009&tm=1607317200&sce=60-4-3&rf=viewer_4) |
|  心率检测 	| [项圈心率监测](http://m.qpic.cn/psc?/V10g6WxY2ZUSCt/TmEUgtj9EK6.7V8ajmQrEF8YGrkylDVoUOi.i.GVzZj.Sqi70LDCp*n9h0lP4jjyJB7azxkq5WlEQUYtjNZlrpxgQJY5tY6.g2UY3lVaiqE!/b&bo=AQYACAEGAAgBGT4!&rf=viewer_4) | [衣服心率检测](http://a1.qpic.cn/psc?/V10g6WxY2ZUSCt/bqQfVz5yrrGYSXMvKr.cqYGHI9d3ABTgttll7GVjuA5hiIWbshYvDslAFf6cVoxKjlswk9tpC3ja58ykuu*7YmlwOmUZZKNdDkEOSwsiJb0!/b&ek=1&kp=1&pt=0&bo=AQYACAEGAAgBGT4!&tl=3&vuin=693763009&tm=1607317200&sce=60-4-3&rf=viewer_4)	|
|  数据传输 	| |	   |  |

[效果图](http://m.qpic.cn/psc?/V10g6WxY2ZUSCt/TmEUgtj9EK6.7V8ajmQrEPR11fjkMoc4YdD*hSwi6VQo6mKpRGakPy9JMY*Zvu1CCvKdhmJAyDbZl4T.eRETEzbTHP8gjTosrn*9GdG0MXA!/b&bo=QAZUCIUGsAgDeX0!&rf=viewer_4)

> 概念评估

|评估标准| |		动物项圈||	动物衣服||
| --------------- | --------------- | --------------- | --------------- | --------------- | --------------- |
| |权重|	评分|	权重 × 评分|	评分|	权重 × 评分|
|舒适度|	0.35|	85|	29.75|	70|	24.5|
|耐用性|	0.18|	90|	16.2|	65|	11.7|
|续航能力|	0.17|	75|	12.75|	85|	14.45|
|体积重量|	0.12|	85|	10.2|	70|	8.4|
|稳固性|	0.08|	85|	6.8|	80|	6.4|
|成本|	0.07|	90|	6.3|	75|	5.25|
|美观|	0.03|	80|	2.4|	90|	2.7|
|总计|	1|  |		84.4| |		73.4|

> 综合比较下，选出动物项圈作为最后的设计产品

# 详细设计
> 物料清单（BOM单）

|序号 |名称 |型号/规格 |用量 |品牌|
| --------------- | --------------- | --------------- | --------------- | --------------- |
|1|	ESP32开发板| ESP32	 |1| 安信可	 |
|2| Lora接口板|	 |1| 安信可	 |
|3| 北斗模块|	BG01-T |1| 安信可	 |
|4| 磷酸铁锂5号|	3.2V1000mah |1| 佰力	 |
|5| 塑料盒|	8.5*6.5*3.5cm |1|其他 	 |
|6| 项圈|	30cm |2|其他 	 |
|7| 温度传感器|MCP9701A	 |1|其他 	 |
|8| 天线|  其他	 |2|其他 	 |

# 性能指标

> 供电方式：磷酸铁锂充电放电电池

> 续航：3天

> 功耗：约4W

> 定位误差：10米内

> 测温误差：5%内

# 代码

> Lora_gateway: 接收项圈发出的信息

> Lora_node: 测量温度

> GPS: 测量位置

# 代码如何运行
> 环境搭建：

> 解压压缩包，以管理员身份运行get.exe，结束后打开Arduino可以看到ESP系列开发板。导入代码，如果发现缺少对应的库，只需在软件中查找并下载就行。
