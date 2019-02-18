主要分为以下几部分：</br>
（1）java面试题</br>
（2）Android面试题</br>
（3）高级开发技术面试题</br>
（4）跨平台Hybrid 开发</br>
一、java面试题</br>
熟练掌握java是很关键的，大公司不仅仅要求你会使用几个api，更多的是要你熟悉源码实现原理，甚至要你知道有哪些不足，怎么改进，还有一些java有关的一些算法，设计模式等等。</br>
（一） java基础面试知识点</br>
java中==和equals和hashCode的区别</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; == 比较基础数据类型的值是否相等，对于对象，比较其存储地址； equals在非重写的情况下，也是只比较存储地址； 
int、char、long各占多少字节数</br>
int与integer的区别</br>
探探对java多态的理解</br>
String、StringBuffer、StringBuilder区别</br>
什么是内部类？内部类的作用</br>
抽象类和接口区别</br>
抽象类的意义</br>
抽象类与接口的应用场景</br>
抽象类是否可以没有方法和属性？</br>
接口的意义</br>
泛型中extends和super的区别</br>
父类的静态方法能否被子类重写</br>
进程和线程的区别</br>
final，finally，finalize的区别</br>
序列化的方式</br>
Serializable 和Parcelable 的区别</br>
静态属性和静态方法是否可以被继承？是否可以被重写？以及原因？</br>
静态内部类的设计意图</br>
成员内部类、静态内部类、局部内部类和匿名内部类的理解，以及项目中的应用</br>
谈谈对kotlin的理解</br>
闭包和局部内部类的区别</br>
string 转换成 integer的方式及原理</br>

（二） java深入源码级的面试题 </br>
哪些情况下的对象会被垃圾回收机制处理掉？ </br>
讲一下常见编码方式？ </br>
utf-8编码中的中文占几个字节；int型几个字节？</br>
静态代理和动态代理的区别，什么场景使用？</br>
Java的异常体系</br>
谈谈你对解析与分派的认识。</br>
修改对象A的equals方法的签名，那么使用HashMap存放这个对象实例的时候，会调用哪个equals方法？</br>
Java中实现多态的机制是什么？</br>
如何将一个Java对象序列化到文件里？</br>
说说你对Java反射的理解</br>
说说你对Java注解的理解</br>
说说你对依赖注入的理解</br>
说一下泛型原理，并举例说明</br>
Java中String的了解</br>
String为什么要设计成不可变的？</br>
Object类的equal和hashCode方法重写，为什么？</br>

（三） 数据结构</br>

常用数据结构简介</br>
并发集合了解哪些？</br>
列举java的集合以及集合之间的继承关系</br>
集合类以及集合框架</br>
容器类介绍以及之间的区别（容器类估计很多人没听这个词，Java容器主要可以划分为4个部分：List列表、Set集合、Map映射、工具类（Iterator迭代器、Enumeration枚举类、Arrays和Collections），具体的可以看看这篇博文 Java容器类）</br>
List,Set,Map的区别</br>
List和Map的实现方式以及存储方式</br>
HashMap的实现原理</br>
HashMap数据结构？</br>
HashMap源码理解</br>
HashMap如何put数据（从HashMap源码角度讲解）？</br>
HashMap怎么手写实现？</br>
ConcurrentHashMap的实现原理</br>
ArrayMap和HashMap的对比</br>
HashTable实现原理</br>
TreeMap具体实现</br>
HashMap和HashTable的区别</br>
HashMap与HashSet的区别</br>
HashSet与HashMap怎么判断集合元素重复？</br>
集合Set实现Hash怎么防止碰撞</br>
ArrayList和LinkedList的区别，以及应用场景</br>
数组和链表的区别</br>
二叉树的深度优先遍历和广度优先遍历的具体实现</br>
堆的结构</br>
堆和树的区别</br>
堆和栈在内存中的区别是什么(解答提示：可以从数据结构方面以及实际实现方面两个方面去回答)？</br>
什么是深拷贝和浅拷贝</br>
手写链表逆序代码</br>
讲一下对树，B+树的理解</br>
讲一下对图的理解</br>
判断单链表成环与否？</br>
链表翻转（即：翻转一个单项链表）</br>
合并多个单有序链表（假设都是递增的）</br>

（四） 线程、多线程和线程池

开启线程的三种方式？</br>
线程和进程的区别？</br>
为什么要有线程，而不是仅仅用进程？</br>
run()和start()方法区别</br>
如何控制某个方法允许并发访问线程的个数？</br>
在Java中wait和seelp方法的不同；</br>
谈谈wait/notify关键字的理解</br>
什么导致线程阻塞？</br>
线程如何关闭？</br>
讲一下java中的同步的方法</br>
数据一致性如何保证？</br>
如何保证线程安全？</br>
如何实现线程同步？</br>
两个进程同时要求写或者读，能不能实现？如何防止进程的同步？</br>
线程间操作List</br>
Java中对象的生命周期</br>
Synchronized用法</br>
synchronize的原理</br>
谈谈对Synchronized关键字，类锁，方法锁，重入锁的理解</br>
static synchronized 方法的多线程访问和作用</br>
同一个类里面两个synchronized方法，两个线程同时访问的问题</br>
volatile的原理</br>
谈谈volatile关键字的用法</br>
谈谈volatile关键字的作用</br>
谈谈NIO的理解</br>
synchronized 和volatile 关键字的区别</br>
synchronized与Lock的区别</br>
ReentrantLock 、synchronized和volatile比较</br>
ReentrantLock的内部实现</br>
lock原理</br>
死锁的四个必要条件？</br>
怎么避免死锁？</br>
对象锁和类锁是否会互相影响？</br>
什么是线程池，如何使用?</br>
Java的并发、多线程、线程模型</br>
谈谈对多线程的理解</br>
多线程有什么要注意的问题？</br>
谈谈你对并发编程的理解并举例说明</br>
谈谈你对多线程同步机制的理解？</br>
如何保证多线程读写文件的安全？</br>
多线程断点续传原理</br>
断点续传的实现</br>
</br>
（五）并发编程有关知识点（这个是一般Android开发用的少的，所以建议多去看看）：
平时Android开发中对并发编程可以做得比较少，Thread这个类经常会用到，但是我们想提升自己的话，一定不能停留在表面，,我们也应该去了解一下java的关于线程相关的源码级别的东西。
附；java进阶与Android内核技术大纲
</br>


二、Android面试题</br>

（一）Android基础知识点</br>

四大组件是什么</br>
四大组件的生命周期和简单用法</br>
Activity之间的通信方式</br>
Activity各种情况下的生命周期</br>
横竖屏切换的时候，Activity 各种情况下的生命周期</br>
Activity与Fragment之间生命周期比较</br>
Activity上有Dialog的时候按Home键时的生命周期</br>
两个Activity 之间跳转时必然会执行的是哪几个方法？</br>
前台切换到后台，然后再回到前台，Activity生命周期回调方法。弹出Dialog，生命值周期回调方法。</br>
Activity的四种启动模式对比</br>
Activity状态保存于恢复</br>
fragment各种情况下的生命周期</br>
Fragment状态保存startActivityForResult是哪个类的方法，在什么情况下使用？</br>
如何实现Fragment的滑动？</br>
fragment之间传递数据的方式？</br>
Activity 怎么和Service 绑定？</br>
怎么在Activity 中启动自己对应的Service？</br>
service和activity怎么进行数据交互？</br>
Service的开启方式</br>
请描述一下Service 的生命周期</br>
谈谈你对ContentProvider的理解</br>
说说ContentProvider、ContentResolver、ContentObserver 之间的关系</br>
请描述一下广播BroadcastReceiver的理解</br>
广播的分类</br>
广播使用的方式和场景</br>
在manifest 和代码中如何注册和使用BroadcastReceiver?</br>
本地广播和全局广播有什么差别？</br>
BroadcastReceiver，LocalBroadcastReceiver 区别</br>
AlertDialog,popupWindow,Activity区别</br>
Application 和 Activity 的 Context 对象的区别</br>
Android属性动画特性</br>
如何导入外部数据库?</br>
LinearLayout、RelativeLayout、FrameLayout的特性及对比，并介绍使用场景。</br>
谈谈对接口与回调的理解</br>
回调的原理</br>
写一个回调demo</br>
介绍下SurfView</br>
RecycleView的使用</br>
序列化的作用，以及Android两种序列化的区别</br>
差值器</br>
估值器</br>
Android中数据存储方式</br>

（二）Android源码相关分析</br>

Android动画框架实现原理</br>
Android各个版本API的区别</br>
Requestlayout，onlayout，onDraw，DrawChild区别与联系</br>
invalidate和postInvalidate的区别及使用</br>
Activity-Window-View三者的差别</br>
谈谈对Volley的理解</br>
如何优化自定义View</br>
低版本SDK如何实现高版本api？</br>
描述一次网络请求的流程</br>
HttpUrlConnection 和 okhttp关系</br>
Bitmap对象的理解</br>
looper架构</br>
ActivityThread，AMS，WMS的工作原理</br>
自定义View如何考虑机型适配</br>
自定义View的事件</br>
AstncTask+HttpClient 与 AsyncHttpClient有什么区别？</br>
LaunchMode应用场景</br>
AsyncTask 如何使用?</br>
SpareArray原理</br>
请介绍下ContentProvider 是如何实现数据共享的？</br>
AndroidService与Activity之间通信的几种方式</br>
IntentService原理及作用是什么？</br>
说说Activity、Intent、Service 是什么关系</br>
ApplicationContext和ActivityContext的区别</br>
SP是进程同步的吗?有什么方法做到同步？</br>
谈谈多线程在Android中的使用</br>
进程和 Application 的生命周期</br>
封装View的时候怎么知道view的大小</br>
RecycleView原理</br>
AndroidManifest的作用与理解</br>

（三）常见的一些原理性问题</br>

Handler机制和底层实现</br>
Handler、Thread和HandlerThread的差别</br>
handler发消息给子线程，looper怎么启动？</br>
关于Handler，在任何地方new Handler 都是什么线程下?</br>
ThreadLocal原理，实现及如何保证Local属性？</br>
请解释下在单线程模型中Message、Handler、Message Queue、Looper之间的关系</br>
请描述一下View事件传递分发机制</br>
Touch事件传递流程</br>
事件分发中的onTouch 和onTouchEvent 有什么区别，又该如何使用？</br>
View和ViewGroup分别有哪些事件分发相关的回调方法</br>
View刷新机制</br>
View绘制流程</br>
自定义控件原理</br>
自定义View如何提供获取View属性的接口？</br>
Android代码中实现WAP方式联网</br>
AsyncTask机制</br>
AsyncTask原理及不足</br>
如何取消AsyncTask？</br>
为什么不能在子线程更新UI？</br>
ANR产生的原因是什么？</br>
ANR定位和修正</br>
oom是什么？</br>
什么情况导致oom？</br>
有什么解决方法可以避免OOM？</br>
Oom 是否可以try catch？为什么？</br>
内存泄漏是什么？</br>
什么情况导致内存泄漏？</br>
如何防止线程的内存泄漏？</br>
内存泄露场的解决方法</br>
内存泄漏和内存溢出区别？</br>
LruCache默认缓存大小</br>
ContentProvider的权限管理(解答：读写分离，权限控制-精确到表级，URL控制)</br>
如何通过广播拦截和abort一条短信？</br>
广播是否可以请求网络？</br>
广播引起anr的时间限制是多少？</br>
计算一个view的嵌套层级</br>
Activity栈</br>
Android线程有没有上限？</br>
线程池有没有上限？</br>
ListView重用的是什么？</br>
Android为什么引入Parcelable？</br>
有没有尝试简化Parcelable的使用？</br>

（四）开发中常见的一些问题
</br>
ListView 中图片错位的问题是如何产生的?</br>
混合开发有了解吗？</br>
知道哪些混合开发的方式？说出它们的优缺点和各自使用场景？（解答：比如:RN，weex，H5，小程序，WPA等。做Android的了解一些前端js等还是很有好处的)；</br>
屏幕适配的处理技巧都有哪些?</br>
服务器只提供数据接收接口，在多线程或多进程条件下，如何保证数据的有序到达？</br>
动态布局的理解</br>
怎么去除重复代码？</br>
画出 Android 的大体架构图</br>
Recycleview和ListView的区别</br>
ListView图片加载错乱的原理和解决方案</br>
动态权限适配方案，权限组的概念</br>
Android系统为什么会设计ContentProvider？</br>
下拉状态栏是不是影响activity的生命周期</br>
如果在onStop的时候做了网络请求，onResume的时候怎么恢复？</br>
Bitmap 使用时候注意什么？</br>
Bitmap的recycler()</br>
Android中开启摄像头的主要步骤</br>
ViewPager使用细节，如何设置成每次只初始化当前的Fragment，其他的不初始化？</br>
点击事件被拦截，但是想传到下面的View，如何操作？</br>
微信主页面的实现方式</br>
微信上消息小红点的原理</br>
CAS介绍（这是阿里巴巴的面试题，我不是很了解，可以参考博客: CAS简介）</br>

三、高级开发技术面试题
</br>
图片库对比</br>
图片库的源码分析</br>
图片框架缓存实现</br>
LRUCache原理</br>
图片加载原理</br>
自己去实现图片库，怎么做？</br>
Glide源码解析</br>
Glide使用什么缓存？</br>
Glide内存缓存如何控制大小？</br>

（二）网络和安全机制</br>

网络框架对比和源码分析</br>
自己去设计网络请求框架，怎么做？</br>
okhttp源码</br>
网络请求缓存处理，okhttp如何处理网络缓存的</br>
从网络加载一个10M的图片，说下注意事项</br>
TCP的3次握手和四次挥手</br>
TCP与UDP的区别</br>
TCP与UDP的应用</br>
HTTP协议</br>
HTTP1.0与2.0的区别</br>
HTTP报文结构</br>
HTTP与HTTPS的区别以及如何实现安全性</br>
如何验证证书的合法性?</br>
https中哪里用了对称加密，哪里用了非对称加密，对加密算法（如RSA）等是否有了解?</br>
client如何确定自己发送的消息被server收到?</br>
谈谈你对WebSocket的理解</br>
WebSocket与socket的区别</br>
谈谈你对安卓签名的理解。</br>
请解释安卓为啥要加签名机制?</br>
视频加密传输</br>
App 是如何沙箱化，为什么要这么做？</br>
权限管理系统（底层的权限是如何进行 grant 的）？</br>

（三）数据库</br>

sqlite升级，增加字段的语句</br>
数据库框架对比和源码分析</br>
数据库的优化</br>
数据库数据迁移问题</br>

（四）算法</br>

排序算法有哪些？</br>
最快的排序算法是哪个？</br>
手写一个冒泡排序</br>
手写快速排序代码</br>
快速排序的过程、时间复杂度、空间复杂度</br>
手写堆排序</br>
堆排序过程、时间复杂度及空间复杂度</br>
写出你所知道的排序算法及时空复杂度，稳定性</br>
二叉树给出根节点和目标节点，找出从根节点到目标节点的路径</br>
给阿里2万多名员工按年龄排序应该选择哪个算法？</br>
GC算法(各种算法的优缺点以及应用场景)</br>
蚁群算法与蒙特卡洛算法</br>
子串包含问题(KMP 算法)写代码实现</br>
一个无序，不重复数组，输出N个元素，使得N个元素的和相加为M，给出时间复杂度、空间复杂度。手写算法</br>
万亿级别的两个URL文件A和B，如何求出A和B的差集C(提示：Bit映射->hash分组->多文件读写效率->磁盘寻址以及应用层面对寻址的优化)</br>
百度POI中如何试下查找最近的商家功能(提示：坐标镜像+R树)。</br>
两个不重复的数组集合中，求共同的元素。</br>
两个不重复的数组集合中，这两个集合都是海量数据，内存中放不下，怎么求共同的元素？</br>
一个文件中有100万个整数，由空格分开，在程序中判断用户输入的整数是否在此文件中。说出最优的方法</br>
一张Bitmap所占内存以及内存占用的计算</br>
2000万个整数，找出第五十大的数字？</br>
烧一根不均匀的绳，从头烧到尾总共需要1个小时。现在有若干条材质相同的绳子，问如何用烧绳的方法来计时一个小时十五分钟呢？</br>
求1000以内的水仙花数以及40亿以内的水仙花数</br>
5枚硬币，2正3反如何划分为两堆然后通过翻转让两堆中正面向上的硬8币和反面向上的硬币个数相同</br>
时针走一圈，时针分针重合几次</br>
N*N的方格纸,里面有多少个正方形</br>
x个苹果，一天只能吃一个、两个、或者三个，问多少天可以吃完？</br>
</br>
（五）插件化、模块化、组件化、热修复、增量更新、Gradle</br>
</br>
对热修复和插件化的理解</br>
插件化原理分析</br>
模块化实现（好处，原因）</br>
热修复,插件化</br>
项目组件化的理解</br>
描述清点击 Android Studio 的 build 按钮后发生了什么</br>

（六）架构设计和设计模式</br>

谈谈你对Android设计模式的理解</br>
MVC MVP MVVM原理和区别</br>
你所知道的设计模式有哪些？</br>
项目中常用的设计模式</br>
手写生产者/消费者模式</br>
写出观察者模式的代码</br>
适配器模式，装饰者模式，外观模式的异同？</br>
用到的一些开源框架，介绍一个看过源码的，内部实现过程。</br>
谈谈对RxJava的理解</br>
RxJava的功能与原理实现</br>
RxJava的作用，与平时使用的异步操作来比的优缺点</br>
说说EventBus作用，实现方式，代替EventBus的方式</br>
从0设计一款App整体架构，如何去做？</br>
说一款你认为当前比较火的应用并设计(比如：直播APP，P2P金融，小视频等)</br>
谈谈对java状态机理解</br>
Fragment如果在Adapter中使用应该如何解耦？</br>
Binder机制及底层实现</br>
对于应用更新这块是如何做的？(解答：灰度，强制更新，分区域更新)？</br>
实现一个Json解析器(可以通过正则提高速度)</br>
统计启动时长,标准</br>

（七）性能优化</br>

如何对Android 应用进行性能分析以及优化?</br>
ddms 和 traceView</br>
性能优化如何分析systrace？</br>
用IDE如何分析内存泄漏？</br>
Java多线程引发的性能问题，怎么解决？</br>
启动页白屏及黑屏解决？</br>
启动太慢怎么解决？</br>
怎么保证应用启动不卡顿？</br>
App启动崩溃异常捕捉</br>
自定义View注意事项</br>
现在下载速度很慢,试从网络协议的角度分析原因,并优化(提示：网络的5层都可以涉及)。</br>
Https请求慢的解决办法（提示：DNS，携带数据，直接访问IP）</br>
如何保持应用的稳定性</br>
RecyclerView和ListView的性能对比</br>
ListView的优化</br>
RecycleView优化</br>
View渲染</br>
Bitmap如何处理大图，如一张30M的大图，如何预防OOM</br>
java中的四种引用的区别以及使用场景</br>
强引用置为null，会不会被回收？</br>

（八）NDK、jni、Binder、AIDL、进程通信有关</br>

请介绍一下NDK</br>
什么是NDK库?</br>
jni用过吗？</br>
如何在jni中注册native函数，有几种注册方式?</br>
Java如何调用c、c++语言？</br>
jni如何调用java层代码？</br>
进程间通信的方式？</br>
Binder机制</br>
简述IPC？</br>
什么是AIDL？</br>
AIDL解决了什么问题？</br>
AIDL如何使用？</br>
Android 上的 Inter-Process-Communication 跨进程通信时如何工作的？</br>
多进程场景遇见过么？</br>
Android进程分类？</br>
进程和 Application 的生命周期？</br>
进程调度</br>
谈谈对进程共享和线程安全的认识</br>
谈谈对多进程开发的理解以及多进程应用场景</br>
什么是协程？</br>

（九）framework层、ROM定制、Ubuntu、Linux之类的问题</br>
</br>
java虚拟机的特性</br>
谈谈对jvm的理解</br>
JVM内存区域，开线程影响哪块内存</br>
对Dalvik、ART虚拟机有什么了解？</br>
Art和Dalvik对比</br>
虚拟机原理，如何自己设计一个虚拟机(内存管理，类加载，双亲委派)</br>
谈谈你对双亲委派模型理解</br>
JVM内存模型，内存区域</br>
类加载机制</br>
谈谈对ClassLoader(类加载器)的理解</br>
谈谈对动态加载（OSGI）的理解</br>
内存对象的循环引用及避免</br>
内存回收机制、GC回收策略、GC原理时机以及GC对象</br>
垃圾回收机制与调用System.gc()区别</br>
Ubuntu编译安卓系统</br>
系统启动流程是什么？（提示：Zygote进程 –> SystemServer进程 –> 各种系统服务 –> 应用进程）</br>
大体说清一个应用程序安装到手机上时发生了什么</br>
简述Activity启动全部过程</br>
App启动流程，从点击桌面开始</br>
逻辑地址与物理地址，为什么使用逻辑地址？</br>
Android为每个应用程序分配的内存大小是多少？</br>
Android中进程内存的分配，能不能自己分配定额内存？</br>
进程保活的方式</br>
如何保证一个后台服务不被杀死？（相同问题：如何保证service在后台不被kill？）比较省电的方式是什么？</br>
App中唤醒其他进程的实现方式</br>


四、跨平台Hybrid 开发</br>
</br>
flutter</br>
Html5项目实战</br>
HTML&CSS&JavaScript 实战</br>
WordPress搭建网站项目实战</br>
前端Vue架构</br>
前端样式开发</br>
Weex内置能力</br>
Weex原生应用</br>
Weex扩展框架</br>
WeexUI架构</br>
介绍你做过的哪些项目</br>
都使用过哪些框架、平台？</br>
都使用过哪些自定义控件？</br>
研究比较深入的领域有哪些？</br>
对业内信息的关注渠道有哪些？</br>
最近都读哪些书？</br>
有没有什么开源项目？</br>
自己最擅长的技术点，最感兴趣的技术领域和技术点</br>
项目中用了哪些开源库，如何避免因为引入开源库而导致的安全性和稳定性问题</br>
实习过程中做了什么，有什么产出？</br>


