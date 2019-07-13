# Data structure And Algorithm
### 程序=数据结构+算法

![Image text](https://github.com/tanfengjie/Algorithm/blob/master/images/DataSturcture-Algorithm.jpeg)

####一.数据结构的基本概念
##### 数据结构定义：

数据结构是一种存储和组织数据的方式，以便于访问和修改。数据结构包括数据的逻辑结构、数据的存储结构以及数据的运算，即按照某种逻辑关系组织起来的一批数据，按一定的映射方式把它存放在计算机的存储器中，并在这些数据上定义了一个运算的集合。

##### 数据的逻辑结构：
反映数据元素之间的关系。有集合、线性结构、树型结构、图型结构。
##### 数据的存储结构：
逻辑结构在计算机中的存储映象，是逻辑结构在计算机中的实现，它包括数据元素的表示和元素之间关系的表示。有顺序存储结构（数组）、链式存储结构（链表）、索引存储结构、散列存储结构等。
##### 数据的运算：
对数据施加的操作，通过算法描述。


####二.算法的基本概念
##### 算法定义：

计算机求解一个问题所需的一系列步骤

##### 算法的基本特性：

输入：一个算法有0个或者多个输入，以刻画运算对象的初始情况，所谓0个输入是指算法本身给出了初始条件；
输出：一个算法有一个或多个输出，以反映对输入数据加工后的结果。没有输出的算法是毫无意义的；
有穷性：算法必须能在执行有限个步骤之后终止；
确切性：算法的每一步骤必须有确切的定义；
可行性：算法中执行的任何计算步骤都是可以被分解为基本的可执行的操作步，即每个计算步都可以在有限时间内完成。
算法设计的要求：

正确性：设计的算法能满足具体问题的需求，并且任何合法的输入都会得出正确的输出；
可读性：是指算法被写好之后，该算法理解的难易程度，一个算法可读性的好坏十分重要。如果一个算法比较抽象且难以理解，那么这个算法就不利于交流和推广使用，对于修改、扩展、维护来说都十分不方便，因此，在追求高效的同时，也应是算法尽量简明易懂。
健壮性：当输入数据非法时，算法也会做出相应的判断，而不会因为输入的错误而造成瘫痪。
时间效率高（时间复杂度）和需要的存储空间少（空间复杂度）
##### 时间复杂度：

程序大概的执行次数（不是执行时间）。一般情况下，算法中基本操作重复执行的次数是问题规模n的某个函数，用T(n)表示，若有某个辅助函数f(n),使得当n趋近于无穷大时，T(n)/f(n)的极限值为不等于零的常数，则称f(n)是T(n)的同数量级函数。记作T(n)=Ｏ(f(n)),称Ｏ(f(n)) 为算法的渐进时间复杂度，简称时间复杂度

##### 空间复杂度：

该算法所耗费的存储空间，它也是问题规模n的函数。其是对一个算法在运行过程中临时占用存储空间大小的量度。一个算法在计算机存储器上所占用的存储空间，包括存储算法本身所占用的存储空间，算法的输入输出数据所占用的存储空间和算法在运行过程中临时占用的存储空间这三个方面。

![Image text](https://github.com/tanfengjie/Algorithm/blob/master/images/DataSturcture-Algorithm-X.jpeg)