EasyNews
========

网易新闻无广告山寨版本😄



##编程规范（强制）
- 使用storyboard（简称sb）来调整自动布局.
- 头文件能不import就不要import文件，节省编译时间.
- 命名要规范，全局变量前面加上下划线。
- push之前尽量去掉或者注释掉输出，多注意，方便debug.
- 协议用"#pragma mark - protocol"来标记.
- 不使用Model类.
- 头文件要有一定量的注释.
- 不使用prefix header 文件,节省编译时间.
- 图片使用Images.xcassets.
- 千万别在View里面对数据做任何修改，View只能展现数据.这里的View指的是MVC里面的View.否则别怪我驳回代码.
- View千万不要处理业务逻辑.否则别怪我驳回代码.
- 能用OperationQueue的地方不要用GCD.
- 常量不要用宏定义指定，用静态变量声明.
- View要用delegate把事件传出，复杂的View用DataSource传入数据.
- 用分析去查看内存用错的地方.
- 用Profile测试程序的性能.

