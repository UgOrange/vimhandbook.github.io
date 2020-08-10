# Vim 练级手册

《Vim 练级手册》一书是本开源的 Vim 教程，尽我所能的介绍 Vim 的相关知识

去年的 8 月份，我搭建了自己的博客（https://wxnacy.com），同时我开始第 N 次的学习 Vim，并开始作为主编辑器使用。

## 为什么写这本书

在我的博客中，Vim 相关的内容只占了总数的 1/10 左右，然后总站的访问量却占到了 1/4 到 1/3 的样子，这些都是统计的 Google 搜索来的访问量，所以我有理由相信在程序员中有相当一批人是喜欢 Vim，并坚持在用 Vim 编辑的。这不禁让我想起当初我学习的痛苦，中文的 Vim 资料其实很少，我在博客中总结了很多 Vim 的知识，但我还觉的很零散，一种反哺的心态，让我决心好好的梳理下学习 Vim 的过程，让更多的人看到，并开始或者更简单的使用 Vim。

之所以说我是第 N 次学习，是因为在过去的几年里，我数次想要使用这个装逼神器，但每次都因为太难而却步。无奈 Vim 的学习曲线简直逆天，满屏幕的找光标，每次退出 Vim 都会莫名其妙的报错，然后伴随当、当、当的报警声，想砸键盘有木有。

但我心里一直放不下它，不只是只需要舞动键盘就可以完成所有操作的那种酷炫感，每次修改服务器上的文件，都要先复制到本地，改完后在同步上去的步骤真的很让人崩溃。

## 我是怎样学的

在系统学习完 Python 后，我在日常浏览鸟哥的私房菜时又看到了关于 Vim 的基础教程，接下来就是它了，这次一定要死磕到底。

随后我忍着心中的烦躁，一个键位一个键位的练习和记忆，当时我突然有一种想法，我要把主编辑器换成 Vim，在经过一早晨的思考后，我的得出的结论是这样的，**以前经常半途而废，是因为我生活中不会经常用到它，只是“偶尔装逼”，这样的练习量太少了，遇到难处理的操作我就换成其他编辑器，这样的思想导致我不会真的花功夫去熟悉它，这样一来，半途而废，也是理所当然的**

这个想法在当时很大胆，因为当时正好赶上项目上线，有很多的工作需要很短的时间完成，这样做的结果是，我不得不花了比平常更多的时间来完成工作，那段时间真的很痛苦，摒弃了用了几年的 IDE，在 Vim 上开发简直是不知所措，很多时候我都要愣在那里想半天接下来该按哪个键。

杰夫·科尔文在《天才源自刻意练习》一书中是这样定义**刻意练习**的
> 刻意练习不是去做那些自己得心应手的事情，而是去寻找那些我们不擅长的事情。我们要找出那些自己觉得痛苦艰难却能促使我们不断进步的事情，然后不断重复这些事情。每次重复之后，我们都要强迫自己看到或让别人告知自己哪里没有做好，然后继续重复其中最痛苦艰难的部分。我们继续这个过程，直到身心俱疲。

以前我并不知道刻意练习的这个名词，但是现在看到这句话时却感受颇深，自我决心使用 Vim 并不断的练习后，我就越来越得心应手，至此我的所有开发工作，我的博客和这本书都是在 Vim 中编辑完成的，并且中途完全没有因为更换语言就想要更换编辑器的想法，因为看到别人在笨拙的一手使用鼠标操作光标，然后选中删除输入的过程，我心里想的都是，太慢了，太慢了。

如果你看到这里，可能你也开始想要了解 Vim，或者你想更好的使用 Vim，但不管怎么样，跟着我开始练级吧。

本书以连载的形式发布，自发布起每周一章。

<!-- 关于本书的电子版主题，开始我是想自己写一版的，但是估算了下工作量，感觉有些得不偿失，就偷懒使用了[阮一峰](http://www.ruanyifeng.com/home.html)先生在 [ECMAScript 6 入门](http://es6.ruanyifeng.com/)一书中使用的框架，特此署名。 -->

## 版权许可

本书采用“保持署名—非商用”创意共享4.0许可证。

只要保持原作者署名和非商用，您可以自由地阅读、分享、修改本书。

详细的法律条文请参见[创意共享网站](https://creativecommons.org/licenses/by-nc/4.0/)。

2018-04-06 发布