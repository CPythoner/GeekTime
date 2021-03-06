[TOC]



# 10x 程序员工作法

## 00. 开篇词 | 程序员解决的问题，大多不是问题
软件行业里有一本名著叫**《人月神话》**，其中提到两个非常重要的概念：**本质复杂度**（Essential Complexity）和**偶然复杂度**（Accident Complexity）。

简单来说，本质复杂度就是解决一个问题时，无论怎么做都必须要做的事，而偶然复杂度是因为选用的做事方法不当，而导致要多做的事。

事实：大部分程序员忙碌解决的问题，都不是程序问题，而是由偶然复杂度导致的问题。换句话说，**只要选择了正确的做事方法，减少偶然复杂度带来的工作量，软件开发是可以有条不紊进行的。**

如何减少偶然复杂度引发的问题，让软件开发工作有序、高效地进行，这正是作者希望通过这个专栏帮你解决的问题。

最佳开发实践原则：
* 以始为终
* 任务分解
* 沟通反馈
* 自动化

## 01. 10x 程序员是如何思考的？
1975 年，弗雷德里克·布鲁克斯（Frederick Brooks）出版了软件行业的名著《人月神话》，他给出了一个统计结果，优秀程序员的开发效率是普通程序员的 10 倍。

### 1.1 一个思考框架
思考三个问题：
1. 我现在是什么水平？
2. 我想达到一个什么水平？
3. 我将怎样到达那个水平？

目标清晰的人才能进入到第三个问题，而茫然的人则无从下手。这三个问题来自一个思考框架：
1. Where are we？（我们在哪？）
2. Where are we going？（我们要到哪里去？）
3. How can we get there？（我们如何到达那里？）

这三个问题实际帮我们确定：
* 现状
* 目标
* 实现路径

如果一个人能够清晰的回答这三个问题，通常意味着他对要做的事有着清晰的认识。

## 1.2 四个思考原则
给出思考框架是为了让你明白为什么要提出问题，而具体问题要怎么问，就可以遵循下面这四项原则：
* **以终为始**，就是在工作的一开始就确定好自己的目标，这个原则是在帮助我们回答思考框架中，Where are we going?（我们要到哪儿去？）这个问题；
* **任务分解**，将大目标拆分成一个一个可行的执行任务，工作分解得越细致，我们便越能更好地掌控工作，它是帮助我们回答思维框架中，How can we get there?（我们如何到达那里？）的问题。
* **沟通反馈**，是为了疏通与其他人交互的渠道。一方面，我们保证信息能够传达出去，减少因为理解偏差造成的工作疏漏；另一方面，也要保证我们能够准确接收外部信息，以免因为自我感觉良好，阻碍了进步；
* **自动化**，就是将繁琐的工作通过自动化的方式交给机器执行，这是我们程序员本职工作的一部分，我们擅长的是为其他人打造自动化的服务，但自己的工作却应用得不够，这也是我们工作中最值得优化的部分。

![1.2](https://github.com/CPythoner/GeekTime/blob/master/10X%20%E7%A8%8B%E5%BA%8F%E5%91%98%E5%B7%A5%E4%BD%9C%E6%B3%95/images/1.2.jpg?raw=true)

## 1.3 举例
如果产品经理把要做的产品需求摆在面前。站在**以终为始**的角度，我需要了解真正的目标是什么，所以，我会关心**为什么要做这个特性**。为了保证目标是有效的，我会关心**它给用户带来的价值**。

有了**任务分解**的视角，我需要将一个大的目标进行拆解，如果我要达成这个目标，整体解决方案是远远不够的，我需要把任务分解成一个一个小的部分。所以，我会关心一个一个**具体的使用场景**。

一方面，我会了解到更多的细节，另一方面，当时间紧迫的时候，我会和产品经理来谈谈究竟优先实现哪个场景。

为什么要学会**沟通反馈**？因为我需要明确，自己是否真正理解了产品经理提交的需求。所以，我要不断地问问题，确保自己的理解和产品经理交代的内容一致。

另外，我也需要保证我的产品做出来确实能够达到目标。所以，我会关心它**上线后的衡量手段**。因为我知道，这个行业里有太多代码上线后，从来没有运行过。

**自动化**的角度很有意思，**我们做的方案通常是一个自动化方案，但我们需要了解这个方案没有自动化之前是怎么做的。**如果不自动化，用户会怎么用。所以，我会关心是不是还有其它替换方案，比如，买一个现成的服务。因为很多需求的提出，只是因为我们有了一个开发团队而已。

总结：
面对问题时，用思考框架问问自己，现状、目标和路径。



## 02. 以始为终：如何让你的努力不白费？

如果让你设计一个登录功能，你会怎么做？

###  2.1 想像共同体
我们这些做软件的人其实就是一个想象的共同体，这个“集体想象”就是我们要做的软件，任何想象都需要一个载体将其展现出来，我们编写软件的过程就是将这个“集体想象”落实的过程。

任何事物都要经过两次创造：一次是在头脑中的创造，也就是智力上的或者第一次创造（Mental_First Creation），然后才是付诸实践，也就是实际的构建或第二次创造（Physical_Second Creation）。

我们在工作中遇到的很多问题，其实就是在于**第一次创造没有做好，就进入到第二次创造。**

相比于第一次创造，第二次创造是一件**成本很高**的事。所以，在动手做事之前，我们要在第一次创造上多下一些功夫，将相关各方的“集体想象”统一起来。

对做软件的人来说，我们应该把“终”定位成做一个对用户有价值的软件，能够为别人带来价值，自己的价值才能体现出来。

### 2.2 规划和发现
在执行任务之前，先倒着想想再动手规划，这样规划出来的工作更能瞄准真正的目标。

“**以终为始**”的方式，不仅仅可以帮我们规划工作，还可以帮我们发现工作中的问题。比如提前梳理上线流程发现流程中的疏漏。

概括地说，践行“以终为始”就是在做事之前，先考虑结果，根据结果来确定要做的事情。



## 03. DoD的价值：你完成了工作，为什么他们还不满意？

### 3.1 理解的鸿沟
理解不一致会导致分歧。弥合差异的一个最佳实践：**DoD**（Definition of Done，完成的定义），从这个概念的名字便不难看出，它就是为了解决软件开发中常见的“完成”问题而生的。

### 3.2 完成的定义
DoD 告诉我们怎样算是完成了，尽量减少因为理解偏差造成的各种浪费。**团队在开始工作之前先制定 DoD。**

怎样让 DoD 发挥更好的作用？
* DoD 是一个清单，清单是由一个个的检查项组成的，用来检查我们的工作完成情况。
* DoD 的检查项应该是实际可检查的。
* DoD 是团队成员彼此汇报的一种机制。当我们有了 DoD ，工作只有两种状态，即“**做完**”和“**没做完**”。

在团队层面里，我们也可以定义 DoD：
* **某个功能的 DoD**，比如：这个功能特性已经开发完成，经过产品负责人的验收，处于一个可部署的状态。
* **一个迭代的DoD**，比如：这个迭代规划的所有功能已经完成。
* **一次发布的 DoD**，比如：整个软件处于可发布的状态，上线计划已经明确。

**DoD** 是一个的**思维模式**，是一种**尽可能消除不确定性，达成共识的方式**。我们本着“以终为始”的方式做事情，DoD 让我们能够在一开始就把“终”清晰地定义出来。



## 04. 接到需求任务后，你要先做哪些事

### 4.1 需求描述的问题
在软件开发中，程序员要做什么一般都由**需求**来定义。功能列表式的需求描述方式，将一个完整的需求敲成了碎片，只有所有的功能全部开发完成对接在一起的时候，才是“破镜重圆”的时刻。

也就是说，不到最后一刻，大多数人并没有一个完整的图景，这就相当于看不到完整的“终”。

**用户故事**（User Story）是一种新的需求描述方式。它是站在用户的角度来描述了一个用户希望得到的功能，关注用户在系统中完成一个动作需要经过怎样的路径。既然它是“故事”，它就需要是一个完整的场景，可以讲述出来。

简要地介绍这个用户故事的主要内容，一般会用这样的格式：
**As a （Role）, I want to （Activity）, so that （Business Value）.**
意思就是：**作为一个什么角色，要做什么样的事，以便达成一种怎样的效果**。其中最重要的是，告诉别人**为什么要做这件事**，虽然只有一句话，却往往是很多人欠缺的思考，只知做，不知为何做。

举个概述的例子：作为一个注册用户，我想要通过用户密码登录，以便我可以使用注册用户才能够使用的服务。

用户故事的关键点：**验收标准**，它可以清晰地定义出需求边界。

验收标准非常重要的一环是**异常流程的描述**。验收标准给出了**这个需求最基本的测试用例**，它保证了开发人员完成需求最基本的质量。

如果你的团队采用用户故事的格式进行需求描述固然好，如果不能，在功能列表中，补充验收标准也会极大程度地改善双方协作的效率。

### 4.2 你的角色
**扮演不同角色的时候，我们的思考模式是不同的。**还是以开发用户名密码登录为例，你想到的可能是：输入正确的用户名和密码可以正常登录，输入错误的用户名和密码不能登录，而且给出提示。

所以，如果你要兼顾开发人员和产品经理两个角色，建议你先扮演好产品经理的角色，多花点时间把验收标准制定好，再回到开发人员的角色上去写代码。毕竟，**最好维护的代码是没有写出来的代码。**

**在做任何需求或任务之前，先定好验收标准。**



## 05. 持续集成：集成本身就是写代码的一个环节

写代码是程序员的职责，但我们更有义务交付一个可运行的软件。交付一个可运行的软件，通常不是靠程序员个体奋战就能完成的，它是由开发团队协作的结果。



在很长一段时间内，集成都是软件行业的难题，改动量和集成时间互相影响。幸运的是，不同的人在不同的方向尝试着改变，结果，同时加大改动量和集成时间的人陷入了泥潭，而调小这两个参数的人看到了曙光。



《Rapid Development》提出**Daily Build 每日构建**即每天集成一次。每日构建作为早期的一种“最佳实践”被提了出来，但因为它基本上都是原则，没有得到广泛的应用。当人们进一步“调小”参数后，诞生了一个更极致的实践：持续集成，也就是每次提交代码都进行集成。

![5.0](https://github.com/CPythoner/GeekTime/blob/master/10X%20%E7%A8%8B%E5%BA%8F%E5%91%98%E5%B7%A5%E4%BD%9C%E6%B3%95/images/5.0.png?raw=true)



**持续集成**：开发和集成同时进行。



尽早提交代码去集成。



## 06 精益创业：产品经理不靠谱，你怎么办？

可悲的现状：IT 行业中大多数人的专业程度是不够的。



我们必须要有自己的独立思考，多问几个为什么，尽可能减少调到“坑”里之后再求救的次数。



**精益创业** 要解决的是面向不确定性创造新事物，该方法论提出`开发（build）- 测量（measur) - 认知（learn）`这样一个反馈循环。就是说，当你有了一个新的想法（idea）时，就把想法开发成产品（code）投入市场，然后，收集数据（data）获取反馈，看看前面的想法是不是靠谱。

![6.0](https://github.com/CPythoner/GeekTime/blob/master/10X%20%E7%A8%8B%E5%BA%8F%E5%91%98%E5%B7%A5%E4%BD%9C%E6%B3%95/images/6.0.jpg?raw=true)



精益创业提出一个非常重要的概念，最小可行产品，也就是许多人口中的 MVP（Minimum Viable Product）。简言之，少花钱，多办事。



**为什么要学精益创业？**精益创业提供给我们的是一个做产品的思考框架，我们能够接触到的大多数产品都可以放在这个框架内思考。



当产品经理让我们做一个新的产品特性时，我们可以从精益创业这个实践上得到启发，向产品经理们问一些问题，帮助我们确定产品经理提出的需求确实是经过严格思考的。

如果今天的内容你只记住一件事，那请记住：**默认所有需求都不做，直到弄清楚为什么要做这件事。**









## 附录：
书籍推荐：
* 《人月神话》
* 《人类简史》尤瓦尔·赫拉利
* 《未来简史》尤瓦尔·赫拉利
* 《Rapid Development》（国内译作《快速软件开发》）Steve McConnel 
* [Continuous Integration](https://martinfowler.com/articles/continuousIntegration.html)     Martin Fowler
* 《精益创业》 Eric Ries