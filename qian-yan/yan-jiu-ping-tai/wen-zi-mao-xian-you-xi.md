# 文字冒险游戏

经典的文本冒险游戏是一种交互式虚构的形式，玩家可以通过文本而不是图形获得描述和指令，并通过基于文本的命令与故事情节进行交互。这些命令通常用于查询系统的状态，与故事中的人物互动，收集和使用物品，或者在游戏世界中导航

## TextWorld

> [TextWorld: A Learning Environment for Text-based Games](https://arxiv.org/pdf/1806.11532v1.pdf)

我们介绍了TextWorld，一个沙箱学习环境，用于训练和评估基于文本的游戏的RL代理。TextWorld是一个Python库，用于处理文本游戏的交互式播放，以及状态跟踪和奖励分配等后端函数。它提供了一系列我们分析过的游戏的特点和挑战。更重要的是，它允许用户手工制作或自动生成新游戏。它的生成机制提供了对构建游戏的难度、范围和语言的精确控制，并可用于放松她的挑战

![](../../.gitbook/assets/textworld.png)

这些游戏通常实现三种基于文本的界面之一:基于解析器的、基于选择的和基于超链接的。基于选择和基于超链接的界面在给定的状态下以列表、上下文之外或状态描述中的链接的形式向玩家提供可能的动作。另一方面，基于解析器的数据接口对任何输入都是开放的，玩家必须学习游戏理解的单词。这对于计算机来说很有趣，因为它更像自然语言，在自然语言中，你必须根据你对语言和给定状态的理解，知道应该存在什么动作。

![](../../.gitbook/assets/text-based-games.png)

