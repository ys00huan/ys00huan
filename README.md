- 👋 Hi, I’m @ys00huan
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
ys00huan/ys00huan is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
- 大三下学生找项目，意向c++。
- 如果15天内没能完成以下目标，将会直接全力考研：
- ———— 寻找2个项目
- ———— 读懂项目，寻找改进点
- ———— 写进简历，应对面试官提问
- ———— 找到第一份日常实习，并且让人觉得还行
- 现在菜的扣脚，第一天使用github,我会努力学习的！！
- 现在我要找第一个项目了，可能只能去找一个完成了的项目去copy 了，我会在1天内完成寻找项目，并且搭建在本地。

1.https://github.com/amhndu/SimpleNES
2.https://github.com/Light-City/CPlusPlusThings
3.https://github.com/TheAlgorithms/C-Plus-Plus
4.https://github.com/changkun/modern-cpp-tutorial
5.https://github.com/wuye9036/CppTemplateTutorial
6.https://github.com/Alinshans/MyTinySTL
7.https://github.com/taylorconor/tinytetris
8.https://github.com/microsoft/calculator


对于网址1，现在完成了环境搭建，也正式运行了。被墙给卡住了实在是丢人。不过应该会好起来的吧~
现在我想我可以分析一下框架了：使用cmake管理头文件，整个项目还算清晰。我现在需要看看各个文件是完成什么样的功能。
该怎么开始呢。我给我5h 来理解这个项目。真怕自己去玩游戏回不来了hhhh

那么对于网址2，是一个面向初学者的全部基础教程，里面每一个配置文件都可以详细去学习。

对于网址3，这是非常棒的c++底层代码的集合，是各个我们引用的头文件的展开。可以大量的学习各个行业的知识，更加深刻的了解c++的底层逻辑。
比如：哈希链的实现，双哈希链的存储机制等等，也有数学里面的，更快的数学运算，更好的算法去实现一些基本运算。

对于网址4，也是一种教程方式，在一定程度上介绍了现代 C++ ，并不适合想要学习高级 C++ 的读者。本书的目的是为现代 C++ 提供快速入门。
当然，高级读者也可以使用来回顾和检查自己在现代 C++ 上的知识。

对于网址5，也是一个有关c++的教程，比网址4更适合新手学，比网址3更适合面向编程面向应用。

对于网址6，这是另一个人着手写的一个项目，也是他的第一个项目。实现了部分STL的功能，他叫其为“miniSTL”

网址7是实现了终端的俄罗斯方块。我觉得很适合新手去实现。

网址8是一个计算器，能够实现计算器的所有功能。我对他的“数据永远不会丢失”非常感兴趣，因为我们都知道在计算器里面是不太可能实现不丢失数据的。
比如我们算一道积分题，哪怕我们算出了标准解，我们也很难去算出准确数据，类似圆周率。
而且我们更没法计算类似偏微分方程这种都没有标准解的方程了（目前个人水平达不到），只能通过数值解法去逼近。
而且我也非常好奇，就是说，类似于 龙格-库塔 这种计算机偏微分解法的精度已经很准了，能达到百万分位，但是需求计算量可能很大，要怎么压缩计算量呢？



那么我想做的已经很明确了：我想做一个计算器，用来计算积分，微分方程。
有以下难点：
最大的难点----能算出准确值的方程只是很少的一部分，大部分偏微分方程都需要专门写代码去逼近，这个工作量可真大啊。
其他似乎都有办法解决。
考虑输出两种格式，一种准确解，一种数值解。准确解调用接口，数值解中能计算的直接交给计算器，不能计算的调用算法库。
匹配方程---寻找对应解法---输出结果









