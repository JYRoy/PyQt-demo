正在用pyqt写我们比赛项目的客户端，因为学习了一些大佬的demo，针对左侧选项卡，写了一个简单的demo。记录一下。

环境
　　Python3.5.2
　　PyQt5

陈述
　　用的结构是左边一个QListWidget + 右边QStackedWidget，将QWebView加在QStackedWidget上（因为打算用来展示一些charts，用的pyecharts做的数据可视化，生成的html文件，直接嵌入在客户端内，因此用QWebView来显示，关于pyecharts可以看我另外一篇文章https://www.cnblogs.com/jyroy/p/9446486.html）

　　我用的QSS来进行QListWidget的美化，做成类似网易云音乐的侧边栏的样子，我用的是QSS Editor写的QSS（强烈推荐，好用！！），py代码、QSS代码和效果展示如下
