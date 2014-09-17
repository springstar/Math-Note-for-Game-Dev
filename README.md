*by 老G （qq 233424570）*

对于游戏开发中的数学知识，你可以有三种选择：

1. 不管他，只调用具体解决方案的接口：在游戏开发领域，很多游戏引擎和第三方库是封装了专门的数学知识的，对使用者做了屏蔽和隐藏，调用简单。如果你只需要写一些功能代码，那么，基本上不需要任何数学知识。

2. 在项目中直接引入这些库，对库的接口进行调用：你并不需要了解内部的数学原理，你只需要知道如何调用这些库的接口既可以。如果你需要编写某个扩展，可能是这种情况。

3. 了解程序内部的数学实现，并尝试推导。不论你是需要写库，还是调用库，还是优化你的代码（主要是通过算法优化，这里面大部分是数学知识），都有巨大的帮助。

实际开发中，第一二种情况是比较常见的。对这两种情况来说，数学更像是一个黑盒。而由于游戏开发中用户体验的巨大差别性（国内游戏重度强调用户体验和付费引导，而实际上对于一个核心玩法优秀的游戏，玩家对游戏体验是有较高的容错度的。很遗憾我们的国情如此。），只从编写业务逻辑角度，很难得到技术和水平的提高。这也对开发造成了很多的疑惑，比如很多情况下，穷举是无效的。那么，你如何判断这种无效呢？

虽然现在号称信息爆炸的年代，但带来的负面作用就是低质信息的泛滥。只要仔细分辨，不同的知识来源和实际运用情况是千差万别的，好的高质量的信息（另一种情况是，高针对性的信息）依然难得。不同的数学资料的来源问题如下：

- Blog：不系统，证明不严格，版式随意，内容经常丢失。一般来说，blog的内容是不完备的。

- 书籍：书中的内容和实际运用存在差异（典型例子就是《3D Math Primer for Graphics and Game Development》中的4x3矩阵，现在游戏开发中已经很少那么写了）。如果是专业的计算机相关的数学教材，则系统性较好，但内容形式一般比较学究，难以做到深入浅出，表现为，证明和推导跳转性极强（比如一个证明需要10个步骤，最后写出关键的3~5个。这点在《3D COMPUTER GRAPHICS——A Mathematical Introduction with OpenGL》中较突出，作者普遍认为读者的数学知识较好），不连贯。而国内翻译的书籍排版，很多只能用灾难性来形容。而如果是游戏开发数学的书籍，则缺乏很多深入的推导和展开，有些地方更是一笔带过（这点国内国外是一样的），让人不知所以然。

- 代码：代码是偏应用向的，贴近实际，存在大量的简化和优化（因为不同的编程语言和运行环境而有差别）。你很难把数学知识和代码完全联系起来。

- wiki：不同的条目是不同的人员编写的。体例并不统一，内容也忽长忽短（详略不当），互相之间的引证也经常丢失（大片红字连接）。对于文史类知识，wiki的实用性非常高。但是对于专业的理工科知识，wiki参考价值值得怀疑（此时仅对非专业人员普及专业知识帮助较大）。

如果你希望成为一个专业的游戏工程师，数学知识是不可能被绕过的。因为游戏开发中的核心代码，其实很多都是数学知识的直接演绎。希望本书对你有所帮助。

用一句老话结尾吧，中国游戏的未来在于独立游戏和开源分享。大家共勉。

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/cn/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/3.0/cn/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/cn/">知识共享署名-非商业性使用-相同方式共享 3.0 中国大陆许可协议</a>进行许可。
