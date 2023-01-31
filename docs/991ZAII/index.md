---
layout: default
title: 115ES PLUS 2nd & 991ZA PLUS II
nav_order: 2
has_children: false
has_toc: false
---
# [fx-ES PLUS(2nd edition)简评] 115ES PLUS 2nd & 991ZA PLUS II

## 阅读须知
1.  除非另有声明，本文的文字、图片等均为本人创作及拍摄，未经许可不得以任何形式对本文的全部或部分内容进行转载、复制、改编、发布至其他平台等。
2.  文中的信息均基于发帖日期所能获取到的最新信息，当阅读时信息可能已有变化，一切均以最新消息为准。
3. 文中对计算器的描述等均属本人的主观感受，部分表述可能不够准确，若有疑惑欢迎指出。
4. 文中出现的所有产品均为本人自费购买，本文不构成任何购买建议。
>注：部分阅读须知内容来自[@喜羊羊](https://tieba.baidu.com/home/main?id=tb.1.2062eec0.FwWcq4rwt0_gRZlb9o1EWA)

## 写在前面
在2019年开始陆续更新上市的ES PLUS 2nd edition中，只有南非的fx-82ZA PLUS II以及fx-991ZA PLUS II相对于原ES PLUS型号有所升级；而在旗舰型号中仅仅只有fx-991ZA PLUS II和fx-115ES PLUS 2nd edition的颜色为白色，其他的旗舰型号只有黑色~~（好丑）~~。

于是我在成功买到越南型号后萌生了购买这两款机型的想法，fx-115ES PLUS 2nd edition在淘宝和亚马逊全球购均能很方便的购买，于是我便开始了漫长的寻找南非代购的路程。正如图片所示，买确实是买到了.jpg

而原型号fx-991ZA PLUS实在是没啥吸引力就不浪费钱买了（
~~别问花费了多少，问就是心痛.jpg~~

## 简要介绍
正如2nd edition的意思一样，fx-115ES PLUS 2nd edition是fx-115ES PLUS的更新型号。而旗舰型号的fx-991ZA PLUS II却产生了特例，并非单纯换壳更新，对比fx-991ZA PLUS增加了部分功能。

根据维基百科的说明，在1925年前南非的官方语言一直是荷兰语(Dutch)，南非(South Africa)在荷兰语中是Zuid-Afrika，这也便是ZA的由来， 在ISO 3166中，也是规定了ZA为南非的Alpha-2 code。

介于贴吧内已有@喜羊羊对fx-115ES PLUS 2nd edition的[相关简略评测](https://tieba.baidu.com/p/7591156428)，本文将不会再对两机型中fx-115ES PLUS 2nd edition已存在的功能做过多评测。

![fx-ES_PLUS_2nd_edition_list](/assets/images/fx-ES_PLUS_2nd_edition_list.png "fx-ES PLUS 2nd edition的全部型号列表")
上方图片为fx-ES PLUS 2nd edition的全部型号（应该是全部吧）（部分信息来源：[fx-ES PLUS Emulator Subscription](https://edu.casio.com/products/classroom/es_plus/)）

## 包装与外观
如图所示，两者均使用塑封包装，拆开之后便无法复原。

### 正面
很显然，升级后的fx-991ZA PLUS II使用了逗号(comma)作为小数分隔符，而在原型号fx-991ZA PLUS使用的是点号(decimal point)，具体原因后文会详细说明。

### 背面
均为泰国制造。

### 入门说明
从2019年开始的卡西欧大部分计算器生产线都仅附带了简要的入门说明来取代了原有的说明书（什么，环保.jpg），这两款机型也是如此。

### 保护壳
在@喜羊羊对fx-880BTG的[相关评测](https://tieba.baidu.com/p/8088620034)中已有详细介绍，可以做到从下方或上方扣上。

## 拆机
后期至今的泰国产的机型在太阳能面板背部和显示屏背部都用一张透明胶粘贴在了一起，猜测是为了更牢固。~~无情撕掉.gif~~

## 自检
ES PLUS 2nd Edition开始引入第三自检，`[SHIFT]` `[7]` `[AC]`+`[ON]`后接着按`[6]`即可进入。

## 开始（Get Started）
按下`[MODE]`后再按下`[0]`，会出现如下的画面

## 精度测试
内部精度保持在15位。

浮点运算的精度保持在40位。

不含π的算式结果含π的BUG依然可以复现。

## 模式
从键盘按键功能印刷也可猜测fx-991ZA PLUS II和fx-115ES PLUS 2nd edition均为11模式，实际也是如此，除了fx-991ES PLUS基础的八模式和分布计算、不等式计算外，fx-991ZA PLUS II和fx-115ES PLUS 2nd edition的区别在于fx-991ZA PLUS II配备了比例计算，fx-115ES PLUS 2nd edition配备了验证计算。~~虽然这俩都是鸡肋模式就是了~~

fx-991ZA PLUS II相比fx-115ES PLUS 2nd edition少了大π（累乘）、Int、Intg函数
fx-991ZA PLUS II相比fx-991ZA PLUS增加了GCD、LCM、÷R函数，小数分隔符由点号(decimal point)改为了逗号(comma)，具体原因后文会讲。

![fx-991ZA_PLUS](/assets/images/fx-991ZA_PLUS.png "fx-991ZA PLUS")

注：由于未购入fx-991ZA PLUS，fx-991ZA PLUS的图片来自南非销售网站[JAMES RALPH (PTY) LTD](https://www.casio.jamesralphedu.co.za/worksheets/p/casio-fx-991za-plus-complex-numbers-binary-decimal-angle-conversations)。

### 矩阵运算(MATRIX)
Ref/Rref函数两款机型均拥有

### 其他模式没啥好讲的（摆烂

## 常数(CONST)
大部分的fx-ES PLUS和ClassWiz X系列机型的常数值均基于CODATA(2010)推荐值，而fx-991ZA PLUS II和fx-115ES PLUS 2nd edition的常数值均更新至基于CODATA(2014)推荐值。

（fx-115ES PLUS的图片由@喜羊羊 提供）

注：fx-991DE PLUS的常数值基于CODATA(2007)推荐值；fx-991CE X的常数值基于CODATA(2014)推荐值；fx-991RS X的常数值基于CODATA(2018)推荐值；fx-ES PLUS 2nd edition系列的机型的常数值应该均更新至基于CODATA(2014)推荐值。

## 系统设置
### 显示格式-常规(Norm)
fx-991ZA PLUS II和fx-82ZA PLUS II的显示格式初始默认（缺省）值均为Norm2，而包括fx-115ES PLUS 2nd edition在内的其他型号和旧型号fx-ZA PLUS基本均为Norm1。

### 自动关机时间(APO: Auto Power Off)
fx-991ZA PLUS II和fx-991ZA PLUS一样具有自动关机时间的设置菜单，在fx-ES PLUS系列中，拥有自动关机时间的设置菜单的为DE PLUS、ID PLUS、ZA PLUS、fx-92 College 2D+共4个地区的型号。fx-115ES PLUS 2nd edition和fx-115ES PLUS一样并不具备自动关机时间的设置菜单。

### 循环小数设置(Rdec: Recurring Decimal Format)
fx-115ES PLUS 2nd edition跟fx-115ES PLUS一样有循环小数的功能，设置菜单内自然存在。

## 南非ZA型号计算器小数分隔符变动
fx-991ZA PLUS II和fx-82ZA PLUS II相较于fx-991ZA PLUS和fx-82ZA PLUS将小数分隔符由点号(decimal point)改为了逗号(comma)，国内有关南非的小数分隔符变动的讨论或资料极少，下文我将引用外网公开文献&讨论进行初步分析，不感兴趣者可以直接跳过。~~我怎么写个评测写出了论文的感觉~~

在[StackOverFlow（IT技术问答网站）](https://stackoverflow.com/questions/3321096/)中提到，在2010年，微软的开发人员平台版本由.NET 3.5升级至了.NET 4.0，在en-ZA语言环境下的小数分隔符由点号(decimal point)改为了逗号(comma)，但根据fx-991ZA PLUS的说明书可得知fx-991ZA PLUS是在2014年左右上市的（具体时间不可考），并不能看出明显关联。

在南非的一个[科技产品交流论坛上](https://mybroadband.co.za/forum/threads/decimal-comma.193076/)，讨论人员在2009年的一次iOS更新中发现小数分隔符由点号(decimal point)改为了逗号(comma)，下方也有网友指出"Using a decimal is with a comma its a South African standard"。

而软件开发者Robert MacLean注意到了规则变动并进行了深入研究,并撰写了一篇[博客](https://www.sadev.co.za/content/how-correctly-format-currency-south-africa)。

南非的The Legal Metrology Act, 2014 (Act 9 of 2014)（法定计量法）和The Measuring Units and Measuring Standards Act, 2006 (Act 18 of 2006)（计量单位和计量标准法）中都描述了国际公制(the International Metric System)(SI)在南非的使用方法："The comma is the only recognised decimal indicator for all numbers, including amounts of (currency) money."

即：南非的法定小数分隔符自1974年7月5日SI在南非引入以来一直都是逗号(comma)。

那么为什么2014年左右上市的fx-991ZA PLUS和2010年.NET 4.0推出之前所使用的.NET 3.5都是使用点号(decimal point)作为小数分隔符？

楼主的观点是卡西欧及各大开发人员之前的本体化不完善，在大量消费者的反馈下开发者意识到了错误并将其修正。

## 异常相关
~~由于fx-ES PLUS 2nd edition已将大部分异常修复，并且fx-991ZA PLUS II并没有稳定且价格合适的购入渠道（我也不推荐购买），所以咕了（喜~~