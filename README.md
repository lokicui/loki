# Loki
Loki是由Andrei编写的一个与《Modern C++ Design》（C++设计新思维）一书配套发行的C++代码库。 它不仅把C++模板的功能发挥到了极致，而且把类似设计模式这样思想层面的东西通过库来提供。 本篇文章介绍如何利用Loki来轻松地实现一些设计模式。
由于Loki使用了大量牛X到爆的模板技巧，对编译器的要求是很苛刻的，官方兼容列表里只列出了VC7.1以上版本及GCC3.4以上版本。如果你象我一样喜欢用C++Builder6或VC6，可以去下载《Modern C++ Design》配套源码，那里面的Loki提供了对其它不兼容编译器的移植代码，只是版本低了一点，有些接口有些差别。
Loki的下载地址是http://sourceforge.net/projects/loki-lib/，目前最新版本是Loki 0.1.7，后面的代码都使用这个版本作为测试标准。
编译
Loki库提供了N多种编译途经，你可以直接打开项目文件（VC、Code::Block、Cpp-Dev等IDE）编译，也可以用传统的makefile来make，还可以直接用批处理文件编译。象我这种被IDE惯坏的人，一般都是直接把src目录里的代码加入到项目中了事。
BTW，《Modern C++ Design》确实是一本好书，在这里也顺便推荐一下^_^
