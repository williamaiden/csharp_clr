# csharp_clr

使用clr 可以轻易的实现C++调用C#,C#调用C++

clr与直接dll相比，有一点优越性就是clr可以直接导出一个C++类，

也就是说，在C#中可以直接继承这个dll中的类。（这点非常棒）。

另外有一点需要注意的是，请保证在运行目录下有所有的.dll文件，否则会发生IO异常。
