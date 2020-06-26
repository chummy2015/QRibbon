# QRibbon
Qt 实现的 Ribbon 风格菜单栏，基本思路是定制QTabWidget，通过QSS（样式表）实现显示样式的调整，QRibbon的原则是尽量不侵入正常业务逻辑的开发，所以在开发基于QMainWindow的程序时，可以按照正常的开发流程创建界面，创建普通的菜单栏以及菜单项及其信号槽关联，最后调用QRibbon::install(&amp;mainWindow)函数即可自动创建出与QMainWindow原有QMenuBar相对应的Ribbon...

![image](https://github.com/gnibuoz/QRibbon/blob/master/images/Qt-Ribbon.gif?raw=true)
