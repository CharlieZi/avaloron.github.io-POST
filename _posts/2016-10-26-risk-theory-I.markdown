---
layout: post
title:  "风险论（一）"
date:   2016-10-26 20:52:59 +0800
categories: 原创
author: 何绪纲
---

1987年10月19日，星期一，全球经历了上世纪最大的一次金融市场危机。美国金融市场经历了有史以来最大的单日跌幅：道琼斯工业股票指数 (DJIA) 一天之内，跌落 508点，-22.61%。当时美国已经很大程度上推广了自动化交易，但是当天正常交易时段结束之后半个多小时，交易员们才清算完一天的交易数据。在金融界，这被称为黑色星期一（Black Monday），令无数金融圈人士永远无法忘怀—很多资深投资人血本无归，交易员直接下岗。。。

可是在这之前的半年，美国股市却还在全民狂欢中，狂飙了44个百分点（从当年年初到8月）。进入了十月之后，风云突变，美联储发布了前一季度美国糟糕的贸易逆差，吹风记者会上声称考虑美元贬值。市场风云涌动，但并未立刻崩盘，原因很简单，这些之前早已有所预见（特别基于各投行，研究机构的预测报告），于是绝大部分投资人并不认为牛市已经结束。事实上，随后的大崩溃也的确并非起源于美国：星期一早上，香港股市崩溃，之后蔓延至欧洲，随后美国市场跟进。截止到当月月底，各大金融市场跌幅达到-20%至-45%。

如此的重大事件，其原因自然各种解读：政府市场干预，自动化交易，之前高股价泡沫，金融市场的流动性枯竭，投机商的恶意做空，散户的恐慌性抛售。。。看到这，大家是否觉得似曾相识？限于本人知识所限，无法将上述可能的原因逐一解读。但是，从量化金融的角度来看，到底发生了什么，我们怎么避免呢？

假如有一个“完美”模型预测金融市场，并且所有人都用它，那么唯一的结果是，股市永远长红。
不幸的是，这个模型不存在。

假如有一个“完美”模型预测金融市场，一部分人使用它，那么结果是，使用模型的人永远赚钱，绝不亏钱。
不幸的是，这个模型也不存在。

假如有一个模型“近似完美”，一部分人使用它，那么结果是，使用模型的人持续赚钱，绝少亏钱。
不幸的是，这个模型也不存在！

当我们考虑“完美”或则“近似完美”的，我们离市场的真理就越来越远。。。

市场的核心变量是:回报+风险。可是这有个无法回避的悖论，高回报策略的原生态就是高风险！
更糟糕的是，从严格金融数学的角度来看，描述回报是那么的容易，描述风险却是那么的不容易。没有数学是坏数学，可是应用最合适的数学在正确的地方却绝非易事。

回到上面的例子，在80年代，华尔街上的交易员们自信已经掌握了金融世界的真理，因为他们有完美的模型。他们有模型描述股价，有模型基于股价描述衍生品，他们背后还有一大批数学天才继续创造所有可能变成金融产品的新完美模型。1987年，上半年的可观收益更是佐证了他们自信满满的观点。“这些模型可能失效导致Black Monday的概率低于1除以宇宙存在至今的天数！”—Svetlozar Rachev。为什么他们错了？太简单不过，一个冷冰冰的数学概念：他们错误描述了风险，低估了模型失效的“概率”。

那么什么样的数学才是“恰当的”数学去描述风险呢？我后面的文章将会持续讨论，层层解开风险的神秘面纱，当代quant最大的心头之痛。
