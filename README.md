# 写在前面
- 接手陌生模块时，如何快速了解每个页面对应的类，以及它们之间的跳转逻辑。总不能在代码里一个一个地找`startActivity()`吧？

- 有时候，又想查看别人的 app 的页面组织（像淘宝、微信啊），总不能一个一个反编译吧？

总想着有没有工具查看当前的`Activity`，由于原来的小工具apk无法弹出activity信息，于是自己修改了一下原有的小工具，使用toast将当前页面信息弹出，这下就方便了。

此应用主要用到的知识是AccessibilityService，学习可参考此链接：http://www.jianshu.com/p/4cd8c109cdfb
<br/>


