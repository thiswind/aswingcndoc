﻿#labels Featured
#翻译过程中的注意事项


翻译过程中的注意事项 （我的一些个人建议，欢迎指正与补充）
由于是直接翻译as源代码中的注释文档，所以有些基本的注意事项，以免破坏源代码导致生成错误的网页文档 (如果你很熟悉asdoc格式就不用看了 ^^)


# Details #

**不要把文档标签翻译了**
> 就是类似 @param @return ...  等等类似这种@开头的标签不用改动。

> @param 标签后的第一个字符是参数名，也不用改动。

> 如果原文是

> @param button A JButton object.

> 就译成 @param button 一个JButton对象。

> @see 标签后面的字符也不用改动

> 还有 一些html标签也不用改动

> 类似 ```
...``` <pre>...</pre>等等


**每个文件中主要的翻译内容**

> class/interface 注释，public与protected注释 还有 Event标签注释， 好像生成文档的主要就这4部分吧？


**所有文件编辑后保存的编码都使用 UTF-8 编码**

> 以免生成的网页出现乱码


**可以参考Java Swing的中文文档**

> http://gceclub.sun.com.cn/Java_Docs/jdk6/html/zh_CN/api/index.html

> 由于AsWing模仿的Swing框架，所以会有很多地方的用法几乎一样，所以文档也会有很多相同点，有时候可以直接借用Swing文档来加快速度，哈哈。但是毕竟两者也有很大的不同，所以当你决定要直接复制一段Swing文档到AsWing中的时候，一定要保证这段内容在Swing和AsWing之间没有任何偏差，并注意上面的几点。



翻译项目分配见 http://code.google.com/p/aswingcndoc/wiki/Distribution

_----------------------------- 已经开始参与翻译的朋友 ----------------_

[iiley](http://aswing.org)
> AsWing之父，哈哈，核心内容翻译。

[Jeff](http://blog.jeffxu.cn)
> 我的一个好友兼同学，对aswing比较熟悉，所以先开始了。
> 翻译项目 6 Buttons + Menus

[harry](http://harryxu.cn/blog)
> 我准备先搞布局那部分，相信很多aswing初学者会比较早的接触布局的。
> 翻译项目 10 Icons + Layouts

cjmxp

[龙城flash](http://longchengflash.bokee.com/)
> 测试翻译内容