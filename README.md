# java-
Java课程作业项目仓库

一、实验目的
1.学会使用类来封装对象的属性和功能   
2.掌握类变量与实例变量，以及类方法与实例方法的区别 
3.掌握类和对象，会创建和使用对象

二、实验过程
用setSpeed(int m)方法将参数m的值赋值给speed;用setAmount(int m)方法将参数m的赋值给amount；将参数c的值赋值给cpu；用setHardDisk(HardDisk h)方法将参数h的值赋值给HD；
并用show()方法能显示cpu的速度和硬盘的容量。

三、核心方法
1.pc调用setCPU(CPU c)方法，调用时实参是cpu
2.pc调用setHardDisk(HardDisk h)方法，调用时实参是disk
3.pc调用show()方法
4.main方法中创建一个对象

四、实验结果
正确输出CPU速度为2200和硬盘容量200

五、实验感想
①、一定要保持java文件名和主类名一致，否则无法编译通过；尽量不使用空对象，虽然编译能通过，但最终运行错误。 
②、实例变量、实例方法都只能被对象调用，不能直接操作；类变量、类方法既可以被对象调用又可以通过类名直接操作；构造函数是特殊的方法，既是类方法又是实例方法。 
③、package语句指明该文件中定义的类所在的包，import语句能够引入一个包中的直接类，但不能自动引入该包的子包。
④、对象是用来描述客观事物的一个实体，类定义了对象将会拥有的特征（属性）和行为（方法） ；类是对象的类型，对象是类的实例。 
