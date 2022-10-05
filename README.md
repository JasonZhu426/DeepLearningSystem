# Deep Learning System

深度学习系统（AI系统）

这个开源项目英文名字叫做 Deep Learning System 或者 AI System，中文名字叫做 深度学习系统 或者 AI系统。

主要是跟大家一起探讨和学习人工智能、深度学习的计算机系统设计，而整个系统是围绕着我在工作当中所积累、梳理、构建关于华为昇腾的内容。当然这里不是打广告，而是希望跟所有关注开源项目的好朋友一起探讨研究，共同促进学习讨论。

没人关注也要坚持哦！（给自己打个无聊的气）

## 内容大纲

这里的内容不能叫做课程大纲，只能叫做内容大纲。

第一部分基础篇介绍AI框架的**<u>前端核心模块</u>**，首先介绍任何一个AI框架都离不开的自动微分，通过自动微分功能后就会产生表示神经网络的图和算子，然后介绍AI框架爱前端的优化，还有最近很火的大模型分布式训练在AI框架中的关键技术。

第二部分进进阶篇介绍AI框架**<u>底层编译技术</u>**，将站在系统设计的角度，思考在设计现代机器学习系统中需要考虑的编译器问题，特别是中间表达乃至后端优化。

第三部分硬核篇介绍**<u>AI芯片</u>**，这里就很硬核了，希望可以坚持到最后啦，从芯片的基础到AI芯片的范围都会涉及，芯片设计需要考虑上面AI框架的前端、后端编译，而不是停留在天天喊着吊打英伟达，被现实打趴。

第四部分是很实际的**<u>推理和部署</u>**，讲了太多原理身体太虚容易消化不良，还是得回归到业务本质，让行业、企业能够真正应用起来，而推理和部署涉及一些核心算法和注意的事情也分享下。

### 课程部分

**[前端核心模块](./Frontend/)**

|||||
|---|---|---|---|
|编号|名称|名称|备注|
|1|自动微分|01 基本介绍|[silde](./Frontend/AutoDiff/01.introduction.pptx), [video](https://www.bilibili.com/video/BV1FV4y1T7zp/), [article](https://zhuanlan.zhihu.com/p/518198564)|
| |自动微分|02 什么是微分|[silde](./Frontend/AutoDiff/02.base_concept.pptx), [video](https://www.bilibili.com/video/BV1Ld4y1M7GJ/), [article](https://zhuanlan.zhihu.com/p/518198564)|
| |自动微分|03 正反向计算模式|[silde](./Frontend/AutoDiff/03.grad_mode.pptx), [video](https://www.bilibili.com/video/BV1zD4y117bL/), [article](https://zhuanlan.zhihu.com/p/518296942)|
| |自动微分|04 三种实现方法|[silde](./Frontend/AutoDiff/04.grad_mode.pptx), [video](https://www.bilibili.com/video/BV1BN4y1P76t/), [article](https://zhuanlan.zhihu.com/p/520065656)|
| |自动微分|05 手把手实现正向微分框架|[silde](./Frontend/AutoDiff/05.forward_mode.ipynb), [video](https://www.bilibili.com/video/BV1Ne4y1p7WU/), [article](https://zhuanlan.zhihu.com/p/520451681)|
| |自动微分|06 亲自实现一个PyTorch|[silde](./Frontend/AutoDiff/06.reversed_mode.ipynb), [video](https://www.bilibili.com/video/BV1ae4y1z7E6/), [article](https://zhuanlan.zhihu.com/p/547865589)|
| |自动微分|07 自动微分的挑战&未来|[silde](./Frontend/AutoDiff/07.challenge.pptx), [video](https://www.bilibili.com/video/BV17e4y1z73W/)|
|2|AI框架基础|01 基本介绍|[silde](./Frontend/Foundation/01.introduction.pptx), [video](https://www.bilibili.com/video/BV1he4y1z7oD/?vd_source=26de035c60e6c7f810371fdfd13d14b6)|
||AI框架基础|02 AI框架有什么用|[silde](./Frontend/Foundation/02.fundamentals.pptx), [video](https://www.bilibili.com/video/BV1fd4y1q7qk/?vd_source=26de035c60e6c7f810371fdfd13d14b6)|
||AI框架基础|03 AI框架之争（框架发展）|[silde](./Frontend/Foundation/03.history.pptx), [video](https://www.bilibili.com/video/BV1C8411x7Kn/?vd_source=26de035c60e6c7f810371fdfd13d14b6)|
||AI框架基础|04 编程范式（声明式&命令式）|[silde](./Frontend/Foundation/04.programing.pptx), [video](https://www.bilibili.com/video/BV1gR4y1o7WT/?vd_source=26de035c60e6c7f810371fdfd13d14b6)|
|||||

**底层编译技术**

待更...

**AI芯片**

待更...

**推理和部署**

待更...

## 项目背景

近年来人工智能特别是深度学习技术得到了飞速发展，这背后离不开计算机硬件和软件系统的不断进步。在可见的未来，人工智能技术的发展仍将依赖于计算机系统和人工智能相结合的共同创新模式。需要注意的是，计算机系统现在正以更大的规模和更高的复杂性来赋能于人工智能，这背后不仅需要更多的系统上的创新，更需要系统性的思维和方法论。与此同时，人工智能也反过来为设计复杂系统提供支持。

我们注意到，现在的大部分人工智能相关的课程，特别是深度学习和机器学习相关课程主要集中在相关理论、算法或者应用，与系统相关的课程并不多见。我们希望人工智能系统这门课能让人工智能相关教育变得更加全面和深入，以共同促进人工智能与系统在开源方面的共同学习和讨论。

（原谅我复制粘贴微软[AI-System](https://github.com/microsoft/AI-System)的介绍，人家写得很好啦；另外推荐一个很好学习参考项目，公司跟英国麦络老师（爱丁堡大学）合作的[机器学习系统：设计和实现](https://github.com/openmlsys/openmlsys-zh)。）
