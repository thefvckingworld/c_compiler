# c_compiler

一些c++的资源：

# cpp11 Compiler
c++11  Compiler for learning c++11

从0开始撸一个c++11编译器。

正在学习c++11, 仅作为学习c++11的练手项目。

前端：能cover住c++ 90%的语法即可。
后端：再说，有空再看

TODO: 后续作为课程开放，穿插c++11学习以及编译器知识。And Then，在bilbili开课。


书籍参考：
1.《龙书》，最新版
2.《虎书--C语言版》最新版
3.《鲸书》最新版
4.《c++11 standard》http://www.open-std.org/jtc1/sc22/wg14/www/docs/n1548.pdf【到时再来详细看找找看】 ISO/IEC 14882:2011
5.《intel x86-64》参考手册(Intel官网下载)
6.System V x64 ABI
7.https://www3.nd.edu/~dthain/compilerbook/
8.c++大师认证: http://www.cppgm.org/   (a simple roadmap)
9.《Parsing Techniques》
10.《编译器设计》
11.《c99 standard》得找来看下 【ISO/IEC 9899:1999】
12.《getting started with llvm core libraries》目前唯一一本关于介绍LLVM的书
13.《LLVM编译器实战教程》  等前面所有书看完以后，再来看这本书，等豆瓣有了评分之后再说
14.《深入分析gcc》
15.《计算机程序的构造和解释》
16.《编译原理与实践》冯博琴 译 视频 bilibili 56集
17.《信息论基础》计算机科学丛书  bilibili看视频教程

代码参考[再找找]：
1.https://github.com/rui314/8cc
2.llvm：http://llvm.org/  【先学习llvm源码】
3.Clang c++(参考代码实现)
4.thefvckingworld/8cc
5./DoctorWkt/acwj
6.

其他资料参考:
1.https://llvm-tutorial-cn.readthedocs.io/en/latest/index.html
2.https://kaleidoscope-llvm-tutorial-zh-cn.readthedocs.io/zh_CN/latest/
3.https://cs.brown.edu/courses/cs173/2012/OnLine/
4.http://www.cplusplus.com
5.Bjarne Stroustrup: http://www.stroustrup.com/
6.视频学习资源：90min scheme2c(还不知道这吊东西是干什么的) 
7.Stack overflow:高赞资源列表 https://stackoverflow.com/questions/1669/learning-to-write-a-compiler?page=1&tab=votes#tab-top


编译原理的一些其他资源：
1.课程： https://www.zhihu.com/question/28679215 （斯坦福）
2.课程：编译原理，网易云课堂  https://mooc.study.163.com/learn/1000002001?tid=1000003000#/learn/content
3.课程：编译原理，学堂在线  http://www.xuetangx.com/courses/course-v1:XIYOU+20180208+2019_T1/about
4.https://github.com/apachecn/awesome-cs-courses-zh
5.知乎上的推荐：https://www.zhihu.com/question/31295168
6.中科大编译原理：https://mooc.study.163.com/course/1000002001?tid=1000003000&_trace_c_p_k2_=e35f84a3f8c24581b9925a24b99b2986#/info


代码生成步骤【每一个步骤对应一个目录】：
1.简单预处理(基本的条件判断等)
2.词法分析
3.语法分析
4.代码生成
5.
6.
7.
8.
9.
10.


测试(Google Test)：
1.拿github上那些题解来进行编译，看能否通过OJ
2.自举
3.后续为了提高速度，可能需要专门的服务器来编译




实现步骤： 
1.先搭框架（后续随着学习的深入不断调整）
  a.Part one: 编译器
  b.Part two: document
  c.Part three： Google Test Case
  d.Other
  
2.以最快速度先实现一个 Hello World!用例

一些约定:
1.使用google c++ coding style【https://zh-google-styleguide.readthedocs.io/en/latest/】
2.为凸显先后关系，目录命名以： 数字 + ´_´ + 小写的文件名 形成
3.源文件以下划线连接的小写文件名即可，不加数字
4.

咨询列表：
1.知乎上关于编译器回答的列表，那些实现过编译器的人。
2.公司做编译器的同事
3.找大学里的老师


需实现的组件：
0. 《c++ primer》吃透
1. 把数据结构相关的算法全部用c++实现一遍
2. flex
3. bosin
4. llvm

专家博客：
1： vczh:  http://www.cppblog.com/vczh/archive/2008/05/22/50763.html
2.  vczh: 邮箱 vczh@163.com

一些c++库：
C++ Standard Library：是一系列类和函数的集合，使用核心语言编写，也是C++ISO自身标准的一部分。
Standard Template Library：标准模板库
C POSIX library ： POSIX系统的C标准库规范
ISO C++ Standards Committee ：C++标准委员会

Apache C++ Standard Library：是一系列算法，容器，迭代器和其他基本组件的集合
ASL ：Adobe源代码库提供了同行的评审和可移植的C++源代码库。
Boost ：大量通用C++库的集合。
BDE ：来自于彭博资讯实验室的开发环境。
Cinder：提供专业品质创造性编码的开源开发社区。
Cxxomfort：轻量级的，只包含头文件的库，将C++ 11的一些新特性移植到C++03中。
Dlib：使用契约式编程和现代C++科技设计的通用的跨平台的C++库。
EASTL ：EA-STL公共部分
ffead-cpp ：企业应用程序开发框架
Folly：由Facebook开发和使用的开源C++库
JUCE ：包罗万象的C++类库，用于开发跨平台软件
libPhenom：用于构建高性能和高度可扩展性系统的事件框架。
LibSourcey ：用于实时的视频流和高性能网络应用程序的C++11 evented IO
LibU ： C语言写的多平台工具库
Loki ：C++库的设计，包括常见的设计模式和习语的实现。
MiLi ：只含头文件的小型C++库
openFrameworks ：开发C++工具包，用于创意性编码。
Qt ：跨平台的应用程序和用户界面框架
Reason ：跨平台的框架，使开发者能够更容易地使用Java，.Net和Python，同时也满足了他们对C++性能和优势的需求。
ROOT ：具备所有功能的一系列面向对象的框架，能够非常高效地处理和分析大量的数据，为欧洲原子能研究机构所用。
STLport：是STL具有代表性的版本
STXXL：用于额外的大型数据集的标准模板库。
Ultimate++ ：C++跨平台快速应用程序开发框架
Windows Template Library：用于开发Windows应用程序和UI组件的C++库
Yomm11 ：C++11的开放multi-methods.

Boost.Asio：用于网络和底层I/O编程的跨平台的C++库。
libev ：功能齐全，高性能的时间循环，轻微地仿效libevent，但是不再像libevent一样有局限性，也修复了它的一些bug。
libevent ：事件通知库
libuv ：跨平台异步I/O

FMOD ：易于使用的跨平台的音频引擎和音频内容的游戏创作工具。
Maximilian ：C++音频和音乐数字信号处理库
OpenAL ：开源音频库—跨平台的音频API
Opus：一个完全开放的，免版税的，高度通用的音频编解码器
Speex：免费编解码器，为Opus所废弃
Tonic： C++易用和高效的音频合成
Vorbis： Ogg Vorbis是一种完全开放的，非专有的，免版税的通用压缩音频格式。

Boost.Compute ：用于OpenCL的C++GPU计算库
Bolt ：针对GPU进行优化的C++模板库
C++React ：用于C++11的反应性编程库
Intel TBB ：Intel线程构件块
Libclsph：基于OpenCL的GPU加速SPH流体仿真库
OpenCL ：并行编程的异构系统的开放标准
OpenMP：OpenMP API
Thrust ：类似于C++标准模板库的并行算法库
HPX ：用于任何规模的并行和分布式应用程序的通用C++运行时系统
VexCL ：用于OpenCL/CUDA 的C++向量表达式模板库

C++ B-tree ：基于B树数据结构，实现命令内存容器的模板库
Hashmaps： C++中开放寻址哈希表算法的实现

Bcrypt ：一个跨平台的文件加密工具，加密文件可以移植到所有可支持的操作系统和处理器中。
BeeCrypt：
Botan： C++加密库
Crypto++：一个有关加密方案的免费的C++库
GnuPG： OpenPGP标准的完整实现
GnuTLS ：实现了SSL，TLS和DTLS协议的安全通信库
Libgcrypt
libmcrypt
LibreSSL：免费的SSL/TLS协议，属于2014 OpenSSL的一个分支
LibTomCrypt：一个非常全面的，模块化的，可移植的加密工具
libsodium：基于NaCI的加密库，固执己见，容易使用
Nettle 底层的加密库
OpenSSL ： 一个强大的，商用的，功能齐全的，开放源代码的加密库。
Tiny AES128 in C ：用C实现的一个小巧，可移植的实现了AES128ESB的加密算法

hiberlite ：用于Sqlite3的C++对象关系映射
Hiredis： 用于Redis数据库的很简单的C客户端库
LevelDB： 快速键值存储库
LMDB：符合数据库四大基本元素的嵌入键值存储
MySQL++：封装了MySql的C API的C++ 包装器
RocksDB：来自Facebook的嵌入键值的快速存储
SQLite：一个完全嵌入式的，功能齐全的关系数据库，只有几百KB，可以正确包含到你的项目中。

Boost.Test：Boost测试库
Catch：一个很时尚的，C++原生的框架，只包含头文件，用于单元测试，测试驱动开发和行为驱动开发。
CppUnit：由JUnit移植过来的C++测试框架
CTest：CMake测试驱动程序
googletest：谷歌C++测试框架
ig-debugheap：用于跟踪内存错误的多平台调试堆
libtap：用C语言编写测试
MemTrack —用于C++跟踪内存分配
microprofile- 跨平台的网络试图分析器
minUnit ：使用C写的迷你单元测试框架，只使用了两个宏
Remotery：用于web视图的单一C文件分析器
UnitTest++：轻量级的C++单元测试框架

Boost.Log ：设计非常模块化，并且具有扩展性
easyloggingpp：C++日志库，只包含单一的头文件。
Log4cpp ：一系列C++类库，灵活添加日志到文件，系统日志，IDSA和其他地方。
templog：轻量级C++库，可以添加日志到你的C++应用程序中

GStreamer ：构建媒体处理组件图形的库
LIVE555 Streaming Media ：使用开放标准协议(RTP/RTCP, RTSP, SIP) 的多媒体流库
libVLC ：libVLC (VLC SDK)媒体框架
QtAv：基于Qt和FFmpeg的多媒体播放框架，能够帮助你轻而易举地编写出一个播放器
SDL ：简单直控媒体层
SFML ：快速，简单的多媒体库

ACE：C++面向对象网络变成工具包
Boost.Asio：用于网络和底层I/O编程的跨平台的C++库
Casablanca：C++ REST SDK
cpp-netlib：高级网络编程的开源库集合
Dyad.c：C语言的异步网络
libcurl :多协议文件传输库
Mongoose：非常轻量级的网络服务器
Muduo ：用于Linux多线程服务器的C++非阻塞网络库
net_skeleton ：C/C++的TCP 客户端/服务器库
nope.c ：基于C语言的超轻型软件平台，用于可扩展的服务器端和网络应用。 对于C编程人员，可以考虑node.js
Onion :C语言HTTP服务器库，其设计为轻量级，易使用。
POCO：用于构建网络和基于互联网应用程序的C++类库，可以运行在桌面，服务器，移动和嵌入式系统。
RakNet：为游戏开发人员提供的跨平台的开源C++网络引擎。
Tuf o ：用于Qt之上的C++构建的异步Web框架。
WebSocket++ ：基于C++/Boost Aiso的websocket 客户端/服务器库
ZeroMQ ：高速，模块化的异步通信库

libvpx ：VP8/VP9编码解码SDK
FFmpeg ：一个完整的，跨平台的解决方案，用于记录，转换视频和音频流。
libde265 ：开放的h.265视频编解码器的实现。
OpenH264：开源H.364 编解码器。
Theora ：免费开源的视频压缩格式。

Civetweb ：提供易于使用，强大的，C/C++嵌入式Web服务器，带有可选的CGI，SSL和Lua支持。
CppCMS ：免费高性能的Web开发框架（不是 CMS）.
Crow ：一个C++微型web框架（灵感来自于Python Flask）
Kore :使用C语言开发的用于web应用程序的超快速和灵活的web服务器/框架。
libOnion：轻量级的库，帮助你使用C编程语言创建web服务器。
QDjango：使用C++编写的，基于Qt库的web框架，试图效仿Django API，因此得此名。
Wt ：开发Web应用的C++库

Expat ：用C语言编写的xml解析库
Libxml2 ：Gnome的xml C解析器和工具包
libxml++ ：C++的xml解析器
PugiXML ：用于C++的，支持XPath的轻量级，简单快速的XML解析器。
RapidXml ：试图创建最快速的XML解析器，同时保持易用性，可移植性和合理的W3C兼容性。
TinyXML ：简单小型的C++XML解析器，可以很容易地集成到其它项目中。
TinyXML2：简单快速的C++CML解析器，可以很容易集成到其它项目中。
TinyXML++：TinyXML的一个全新的接口，使用了C++的许多许多优势，模板，异常和更好的异常处理。
Xerces-C++ ：用可移植的C++的子集编写的XML验证解析器

C++ Format ：C++的小型，安全和快速格式化库
casacore ：从aips++ 派生的一系列C++核心库
cxx-prettyprint：用于C++容器的打印库
DynaPDF ：易于使用的PDF生成库
gcc-poison ：帮助开发人员禁止应用程序中的不安全的C/C++函数的简单的头文件。
googlemock：编写和使用C++模拟类的库
HTTP Parser ：C的http请求/响应解析器
libcpuid ：用于x86 CPU检测盒特征提取的小型C库
libevil ：许可证管理器
libusb：允许移动访问USB设备的通用USB库
PCRE：正则表达式C库，灵感来自于Perl中正则表达式的功能。
Remote Call Framework ：C++的进程间通信框架。
Scintilla ：开源的代码编辑控件
Serial Communication Library ：C++语言编写的跨平台，串口库。
SDS：C的简单动态字符串库
SLDR ：超轻的DNS解析器
SLRE： 超轻的正则表达式库
Stage ：移动机器人模拟器
VarTypes：C++/Qt4功能丰富，面向对象的管理变量的框架。
ZBar：‘条形码扫描器’库，可以扫描照片，图片和视频流中的条形码，并返回结果。
CppVerbalExpressions ：易于使用的C++正则表达式
QtVerbalExpressions：基于C++ VerbalExpressions 库的Qt库
PHP-CPP：使用C++来构建PHP扩展的库
Better String ：C的另一个字符串库，功能更丰富，但是没有缓冲溢出问题，还包含了一个C++包装器

Clang :由苹果公司开发的
GCC：GNU编译器集合
Intel C++ Compiler ：由英特尔公司开发
LLVM ：模块化和可重用编译器和工具链技术的集合
Microsoft Visual C++ ：MSVC，由微软公司开发
Open WatCom ：Watcom，C，C++和Fortran交叉编译器和工具
TCC ：轻量级的C语言编译器
Comparison of debuggers ：来自维基百科的调试器列表
GDB ：GNU调试器
Valgrind：内存调试，内存泄露检测，性能分析工具

Cppcheck ：静态C/C++代码分析工具
include-what-you-use ：使用clang进行代码分析的工具，可以#include在C和C++文件中。
OCLint ：用于C，C++和Objective-C的静态源代码分析工具，用于提高质量，减少瑕疵。
Clang Static Analyzer：查找C，C++和Objective-C程序bug的源代码分析工具
List of tools for static code analysis ：来自维基百科的静态代码分析工具列表

以上提到的一些库都在本篇wiki中：https://blog.csdn.net/a110658684/article/details/78862348










