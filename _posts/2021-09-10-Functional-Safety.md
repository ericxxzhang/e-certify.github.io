---
layout:     post
title:      07. 功能安全介绍
subtitle:   功能安全学习
date:       2021-09-10
author:     Eric Zhang
header-img: img/Functional-Safety.jpg
catalog: 	 true
tags:
    - 功能安全
    - 学习
---
"🙉🙉🙉 ”


## 什么是功能安全？ 

在公共场所、工厂、办公室或家中， 我们被越来越多的电子电气设备或系统所包围。 如果它们没有内置的安全机制在需要时准确的激活以将潜在风险降低到可容忍的水平，则其中许多可能会对人类、动物或环境造成伤害。

功能安全是系统或设备整体安全的一部分，通常侧重于电子电气设备和相关软件。 它着眼于与设备或系统功能相关的安全方面，并确保它能够正确地响应接收到的命令。 在系统性方法中，功能安全识别可能导致伤害某人或破坏某物的事故的潜在危险条件、情况或事件，并能够采取纠正或预防措施来避免或减少事故的影响。

功能安全系统的一个简单示例可能是带有传感器的家用咖啡机，该传感器可检测咖啡温度或烧瓶中咖啡的体积。如果传感器检测到温度超过阈值，它会关闭加热元件，或者如果体积大于预期，它会停止渗透过程。

---


## 不同行业、不同产品的功能安全性不同
## IEC 61508 – 基本功能安全标准

基本功能安全标准是IEC 61508 ，适用于所有行业。尽管该标准涵盖了所有行业，但每个行业都有其细微差别，因此许多行业根据 IEC61508 制定了自己的标准。在下面的部分中，我们检查了一些特定的行业标准。重要的是要注意，在决定使用哪种安全标准时，最特定于行业的标准有先例。

![](/img/Functional-Safety3.jpg)

## ISO 26262 – 汽车行业
ISO 26262 标准适用于由车辆中的硬件和软件组件组成的电气和电子系统。它定义了系统的安全相关功能以及在开发过程中使用的过程、方法和工具要满足的要求。
该标准提供了汽车安全生命周期，并支持在这些生命周期阶段定制必要的活动。它确定了一种基于汽车特定风险的方法来确定风险等级（汽车安全完整性等级，ASIL），并使用 ASIL 来指定项目的必要安全要求，以实现可接受的剩余风险。最后，确定确认、验证和确认措施的要求，以确保达到足够和可接受的安全水平。

![](/img/Functional-Safety2.jpg)

## ISO 13849 和 IEC 62061 – 制造和机械行业
EN 954-1 于 1996 年首次发布，被用作机器制造商和最终用户控制系统部件的功能安全标准近 15 年。但随着技术的快速发展，该标准不再能够跟上正在开发的系统和组件。2007 年，EN 954-1 被两项新标准所取代——EN ISO 13849-1 和 IEC 62061—— 旨在应对这些不断变化的技术。
EN ISO 13849-1涉及所有系统技术的安全性，包括机械、液压和气动产品。如果安全功能由控制系统的安全相关部件 (SRP/CS) 执行，EN ISO 13849-1 可用于表明符合机械指令 2006/42/EC 的 EHSR。
IEC 62061指的是通用功能安全标准，考虑了电气、电子或可编程电子 (E/E/PE) 系统和产品的整个生命周期。这是 IEC/EN 61508 的机械行业特定实施。通过实施该标准可以证明符合机械指令 2006/42/EC 的 EHSR。



## IEC 60601& IEC 62304 – 医疗设备
IEC 62304 是一项功能安全标准，涵盖软件的安全设计和维护。它提供流程、活动和任务以确保安全。它适用于以下情况下的医疗器械软件的开发和维护：

该软件本身就是一种医疗设备；
或者软件是最终医疗设备的嵌入式或组成部分。
IEC 62304 的九个部分是：

第 1 部分：范围

第 2 部分：规范性参考

第 3 部分：术语和定义

第 4 部分：一般要求

第 5 部分：软件开发过程

第 6 部分：软件维护过程

第 7 部分：软件风险管理过程

第 8 部分：软件配置管理过程

第 9 部分：软件问题解决过程

IEC 60601标准实际上是一系列确保医疗电气设备安全性和有效性的技术标准。它涉及医疗电气设备的基本安全和基本性能要求，并用于确保任何单一的电气、机械或功能故障都不会对患者和/或操作员造成不可接受的风险。
IEC 60601 是针对特定危险的标准。它提供了评估与电子医疗产品相关的常见危害的要求。其范围是防止发生危险的可能性，包括：

触电危险
机械危害
辐射危害
易燃麻醉剂的着火危害
火灾和其他危险
能量输出过多的危险


## EN 5012X – 铁路行业
铁路行业是我们最古老的公共交通形式之一，与早期的蒸汽和煤炭相比，所使用的技术已经有了很长的路要走。它变得越来越复杂、自动化和自主。对这些系统的功能安全性的信心需求也逐步向前发展。
CENELEC EN 5012X系列功能安全标准（或等效的 IEC 标准）旨在确保将由系统故障行为引起的危害导致的安全风险降低到可接受的水平。同系列标准；CENELEC 和 IEC 分别发布的两个标准是：

EN 50126 (IEC 62278) – 可靠性、可用性、可维护性和安全性 (RAMS)

EN 50128 (IEC 622279) – 软件（信号系统）

EN 50129 (IEC 62425) – 系统安全（子系统软件）

与其他功能安全标准一样，EN 5012X 系列是基于风险的标准，进行风险评估以确定所需的安全功能，以及这些功能降低风险所需的性能水平。

## EN 17206 – 娱乐业或舞台安全
EN 17206是娱乐行业的功能安全标准。它于 2019 年发布，是第一个专门为娱乐行业定义功能安全框架的标准。该标准涵盖舞台和其他生产区域（如剧院、展览厅和工作室）的机械。
安全完整性等级 (SIL)

大多数其他功能安全标准都定义了安全完整性级别。但是，SIL 的确定可能因不同标准而异，应注意不要混淆它们。这在 EN 17206 中变得更加有趣，因为安全标准风险评估通常是在考虑制造设备的情况下编写的，而这些不适用于娱乐环境。然而，EN 17206，附录 D 确实提供了“娱乐行业校准”，以帮助提供指导。

## IEC 60335&IEC 60730 – 家用电器安全
IEC 60335是家用和类似用途电器的安全标准。它涵盖了单相电器额定电压不超过 250V 和其他电器额定电压不超过 480V 的电器。IEC 60335 还涵盖了非家庭使用但外行在其他环境（如商店、农场和轻工业）中使用的电器。

该标准包括三个主要部分：

IEC 60730-1家用和类似用途电器的自动电气控制

IEC 60335-1 提供了家用电器和类似设备的一般测试要求、分类、标记和说明

IEC 60335-2 详细说明了特定类型电器的具体要求,列出了 100 多种不同类型的电器。

下面的列表只是一个小样本：

IEC 60335-2-5 洗碗机

IEC 60335-2-6 固定式灶具、炉灶、烤箱和类似器具

IEC 60335-2-7 洗衣机

IEC 60335-2-11 滚筒式干衣机

IEC 60335-2-16 食物垃圾处理器

IEC 60335-2-56 投影仪和类似设备

IEC 60335-2-58 商用电动洗碗机

## IEC 60880 — 核
IEC 60880 是用于核电厂的安全标准。它涵盖了执行安全功能的软件

---


## 后记

功能安全系列文章，待完善。。。


—— Eric Zhang 于 2021.9.10
