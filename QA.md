# 问答系统  
## 导语  
&ensp;&ensp;&ensp;&ensp;此系列文章主要介绍问答系统(简称QA)的基础知识，发展历程，技术演变过程，当前流行的技术、架构，权威比赛、会议、数据资源等内容。所有介绍将以主流方式为主，兼顾新小分支，行文会以大道联通、细节清晰为基本准则，欢迎大家讨论指正。  
  
**本节要点：** `QA起源、发展、分类`  

**QA起源**  
&ensp;&ensp;&ensp;&ensp;在现实生活中每个人都有丰富多样的信息需求，而解决这些问题的方式无外乎两类：问人和“问书”(包括查书、上网等各类自主查资料解决的方式)。前者受益于人，若是别人知道答案，不仅可提供答案还能帮助理解之；问人亦受制于人，别人未必知道答案或是知道答案但表述不清，最终不能解决需求或难以理解。此外，所需之时未必有合适的人可问、问人会麻烦别人、多人询问一人时效率不高。因此，很多情况下大家会选择自我求知。以前，大家更多的求助于纸质资料，随着电子化设备的兴起，人们逐渐转向求助于电子设备。其使用便利、存储大、反应快且可支持一定检索，网络的发展和设备小型化进一步提升了人们的“问书”体验。这一阶段，各类检索系统和搜索引擎已能较好地满足人们的信息需求。  
&ensp;&ensp;&ensp;&ensp;然而，人心是难以满足的，贪婪是驱使人们创造甚至推动科学进步的源动力。信息需求能否被满足取决于两个因素：其一，存在。即你所查找的信息源包含所需信息。其二，得到。即能准确地获取所需信息。互联网的发展使得网络上流通和积累的信息越来越多，这为因素一带来了增益(信息越多越可能包含答案)，却为因素二带来了阻碍(信息越多干扰越多，越难准确获得答案)。在此基础上，人们或许会有别的要求，比如尽可能快、准地获取信息，答案尽量简洁。各类搜索引擎能较快地搜到较多相关信息，但大多为网页(现在已有所进步，部分信息会以卡片的形式直接呈现，较为简洁)，需要自己进一步查找答案，且搜索提供的大多是关键词。而问答系统与此不同，其以提供信息服务为宗旨，支持自然语言提问(文本或语音，自然地话语与人们的日常使用一样)，回复的是简洁准确的答案。  
**发展**  
&ensp;&ensp;&ensp;&ensp;早期的问答系统大多集中于限定领域，如各类专家系统LUNAR，可回答月球采集样本相关问题；领域问答BaseBall，可回答棒球比赛相关问题。之后有MYCIN，可以识别可能导致急性感染的各种细菌，它还可以根据患者的体重推荐药物；PROSPECTOR(探矿者)，是一种探寻矿物的计算机顾问系统，旨在帮助地质学家评估勘探某地点或区域是否存在特定类型的矿床。国内有张克亮等《基于本体的航空领域问答系统》；曹明宇等《基于知识图谱的原发性肝癌知识问答系统》。限定域问答系统毕竟只能回答限定领域或范围的内容，难以满足人们多样化的信息需求，随后问答系统也开始向着开放域问答系统发展。开放域问答系统面临的问题种类各异，难以预先准备充足的资料用于回答，因此，或是以“开放回答对应开放提问”——人问人答，如百度知道、知乎；或是仅准备常用资料，如维基百科、百度百科、搜狗百科。  
**分类**  
&ensp;&ensp;&ensp;&ensp;按照不同分类标准，问答系统有不同的划分体系：  
(1)    以答案所属范围来划定：限定域问答系统和开放域问答系统。  
(2)    以回答方式划定：FAQ问答(找相关问答对，取其答案)和基于文档的问答(从大范围文件中寻找答案)。  
(3)    以回答对象划定：由人回答和机器作答。  

