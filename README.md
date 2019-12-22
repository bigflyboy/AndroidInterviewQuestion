### 主要分为以下几部分：
1. java面试题
2. Android面试题
3. 高级开发技术面试题
4. 跨平台Hybrid 开发
### 一、java面试题
##### 熟练掌握java是很关键的，大公司不仅仅要求你会使用几个api，更多的是要你熟悉源码实现原理，甚至要你知道有哪些不足，怎么改进，还有一些java有关的一些算法，设计模式等等。
####  (1) java基础面试知识点
##### 1. java中==和equals和hashCode的区别
- == 比较基础数据类型的值是否相等，对于对象，比较其存储地址； equals在非重写的情况下，也是只比较存储地址;
##### 2. int、char、long各占多少字节数
##### 3. int与integer的区别
##### 4. 探探对java多态的理解
##### 5. String、StringBuffer、StringBuilder区别
##### 6. 什么是内部类？内部类的作用
##### 7. 抽象类和接口区别
##### 8. 抽象类的意义
##### 9. 抽象类与接口的应用场景
##### 10. 抽象类是否可以没有方法和属性？
##### 11. 接口的意义
##### 12. 泛型中extends和super的区别
##### 13. 父类的静态方法能否被子类重写
##### 14. 进程和线程的区别
##### 15. final，finally，finalize的区别
##### 16. 序列化的方式
##### 17. Serializable 和Parcelable 的区别
##### 18. 静态属性和静态方法是否可以被继承？是否可以被重写？以及原因？
##### 19. 静态内部类的设计意图
##### 20. 成员内部类、静态内部类、局部内部类和匿名内部类的理解，以及项目中的应用
##### 21. 谈谈对kotlin的理解
##### 22. 闭包和局部内部类的区别
##### 23. string 转换成 integer的方式及原理

####  (2) java深入源码级的面试题 
##### 1. 哪些情况下的对象会被垃圾回收机制处理掉？ 
   1.所有实例都没有活动线程访问。
   2.没有被其他任何实例访问的循环引用实例。
   3.Java 中有不同的引用类型。判断实例是否符合垃圾收集的条件都依赖于它的引用类型。
##### 2. 讲一下常见编码方式？ 
##### 3. utf-8编码中的中文占几个字节；int型几个字节？
##### 4. 静态代理和动态代理的区别，什么场景使用？
##### 5. Java的异常体系
##### 6. 谈谈你对解析与分派的认识。
##### 7. 修改对象A的equals方法的签名，那么使用HashMap存放这个对象实例的时候，会调用哪个equals方法？
##### 8. Java中实现多态的机制是什么？
##### 9. 如何将一个Java对象序列化到文件里？
##### 10. 说说你对Java反射的理解
##### 11. 说说你对Java注解的理解
##### 12. 说说你对依赖注入的理解
##### 13. 说一下泛型原理，并举例说明
##### 14. Java中String的了解
##### 15. String为什么要设计成不可变的？
##### 16. Object类的equal和hashCode方法重写，为什么？

####  (3) 数据结构

##### 1. 常用数据结构简介
##### 2. 并发集合了解哪些？
##### 3. 列举java的集合以及集合之间的继承关系
##### 4. 集合类以及集合框架
##### 5. 容器类介绍以及之间的区别（容器类估计很多人没听这个词，Java容器主要可以划分为4个部分：List列表、Set集合、Map映射、工具类（Iterator迭代器、Enumeration枚举类、Arrays和Collections），具体的可以看看这篇博文 Java容器类）
##### 6. List,Set,Map的区别
##### 7. List和Map的实现方式以及存储方式
##### 8. HashMap的实现原理
##### 9. HashMap数据结构？
##### 10. HashMap源码理解
##### 11. HashMap如何put数据（从HashMap源码角度讲解）？
##### 12. HashMap怎么手写实现？
##### 13. ConcurrentHashMap的实现原理
##### 14. ArrayMap和HashMap的对比
##### 15. HashTable实现原理
##### 16. TreeMap具体实现
##### 17. HashMap和HashTable的区别
##### 18. HashMap与HashSet的区别
##### 19. HashSet与HashMap怎么判断集合元素重复？
##### 20. 集合Set实现Hash怎么防止碰撞
##### 21. ArrayList和LinkedList的区别，以及应用场景
##### 22. 数组和链表的区别
##### 23. 二叉树的深度优先遍历和广度优先遍历的具体实现
##### 24. 堆的结构
- 数据结构中的堆是完全二叉树,即最后一行的子树都是从左往右排列;
删除节点会把最后一个子树,挪到该节点,然后向下比较子树,与较大的子树互换位置,直到最后一层;
插入则是,放在最后一行,最右侧,然后与父节点比较,大于父节点,则换位置.
也就是说每一个父节点的关键字的值都大于或等于这个节点的子节点的关键字值。
##### 25. 堆和树的区别
##### 26. 堆和栈在内存中的区别是什么(解答提示：可以从数据结构方面以及实际实现方面两个方面去回答)？
- 堆内存先进先出,存储对象.动态分配内存,存取速度慢.不需要知道存储的元素的生存期.另外所有线程公用一个堆, 每个线程都有一个栈;堆内的数据不共享,是指对同一个Apple a = new Apple(); Apple b = a ;修改b,则a值也会变.
而对于栈.先进后出,存储基本类型,不包括String,生存期必须固定.  赋值的时候不会被影响.存取速度快.
##### 27. 什么是深拷贝和浅拷贝
##### 28. 手写链表逆序代码
##### 29. 讲一下对树，B+树的理解
##### 30. 讲一下对图的理解
##### 31. 判断单链表成环与否？
##### 32. 链表翻转（即：翻转一个单项链表）
##### 33. 合并多个单有序链表（假设都是递增的）

####  (4) 线程、多线程和线程池

##### 1. 开启线程的三种方式？
##### 2. 线程和进程的区别？
##### 3. 为什么要有线程，而不是仅仅用进程？
##### 4. run()和start()方法区别
##### 5. 如何控制某个方法允许并发访问线程的个数？
- Semaphore ,在方法执行之前mSemaphore.acquire(); 执行之后 mSemaphore.release();****
##### 6. 在Java中wait和seelp方法的不同；
    在调用sleep()方法的过程中，线程不会释放对象锁。
    而当调用wait()方法的时候，线程会放弃对象锁，
##### 7. 谈谈wait/notify关键字的理解
##### 8. 什么导致线程阻塞？
##### 9. 线程如何关闭？
##### 10. 讲一下java中的同步的方法
- synchronized 修饰非静态方法,则单个对象在不同的线程 只能顺序访问. 如果要多个对象同步,
则必须synchronized(X.class)来锁对象
##### 11. 数据一致性如何保证？
##### 12. 如何保证线程安全？
##### 13. 如何实现线程同步？
##### 14. 两个进程同时要求写或者读，能不能实现？如何防止进程的同步？
##### 15. 线程间操作List
##### 16. Java中对象的生命周期
- 创建阶段（Creation）、应用阶段（Using）、不可视阶段（Invisible）、
不可到达阶段（Unreachable）、可收集阶段（Collected）、终结阶段（Finalized）与释放阶段（Free）
##### 17. Synchronized用法
##### 18. synchronize的原理
##### 19. 谈谈对Synchronized关键字，类锁，方法锁，重入锁的理解
- 
##### 20. static synchronized 方法的多线程访问和作用
##### 21. 同一个类里面两个synchronized方法，两个线程同时访问的问题
##### 22. volatile的原理
##### 23. 谈谈volatile关键字的用法
##### 24. 谈谈volatile关键字的作用
##### 25. 谈谈NIO的理解
##### 26. synchronized 和volatile 关键字的区别
##### 27. synchronized与Lock的区别
##### 28. ReentrantLock 、synchronized和volatile比较
##### 29. ReentrantLock的内部实现
##### 30. lock原理
##### 31. 死锁的四个必要条件？
##### 32. 怎么避免死锁？
##### 33. 对象锁和类锁是否会互相影响？
##### 34. 什么是线程池，如何使用?
##### 35. Java的并发、多线程、线程模型
##### 36. 谈谈对多线程的理解
##### 37. 多线程有什么要注意的问题？
##### 38. 谈谈你对并发编程的理解并举例说明
##### 39. 谈谈你对多线程同步机制的理解？
##### 40. 如何保证多线程读写文件的安全？
##### 41. 多线程断点续传原理
##### 42. 断点续传的实现

### 二、Android面试题

#### （1）Android基础知识点

##### 1. 四大组件是什么
##### 2. 四大组件的生命周期和简单用法
##### 3. Activity之间的通信方式
##### 4. Activity各种情况下的生命周期
##### 5. 横竖屏切换的时候，Activity 各种情况下的生命周期
-启动: onCreate() -> onStart() -> onResume()
横竖屏切换后(原来的活动会销毁然后再重建): onPause() -> onStop() -> onDestroy() -> onCreate() -> onStart() -> onResume()
-配置后Manifest 启动: onCreate() -> onStart() -> onResume()
横竖屏切换时活动不重建,但是会回调一个方法: onConfigurationChanged()。
##### 6. Activity与Fragment之间生命周期比较
-当Activity包含一个Fragment的时候，Activity和Fragment生命周期的变化：
  Activity（onCreate）---> Fragment（onAttach onCreate onCreateView onActivityCreate）--->
  Activity（onStart）---> Fragment（onStart）--->
  Activity（onResume）---> Fragment（onResume）--->
  Fragment（onPause）---> Activity（onPause）--->
  Fragment（onStop）---> Activity（onStop）--->
  Fragment（onDestroyView onDestroy onDetach）---> Activity（onDestroy）
  由于Fragment依附于Activity，所以启动的时候Activity的方法肯定在前面，Fragment的方法在后面，但是在要销毁的时候，Fragment的方法先执行，再执行     Activity的方法。

##### 7. Activity上有Dialog的时候按Home键时的生命周期
-正常
##### 8. 两个Activity 之间跳转时必然会执行的是哪几个方法？
  -一般情况下比如说有两个activity,分别叫A,B。
  当在A 里面激活B 组件的时候, A会调用onPause()方法,然后B调用onCreate() ,onStart(), onResume()。
  这个时候B覆盖了A的窗体, A会调用onStop()方法。
  如果B是个透明的窗口,或者是对话框的样式, 就不会调用A的onStop()方法。
  如果B已经存在于Activity栈中，B就不会调用onCreate()方法。
##### 9. 前台切换到后台，然后再回到前台，Activity生命周期回调方法。弹出Dialog，生命值周期回调方法。
##### 10. Activity的四种启动模式对比
##### 11. Activity状态保存于恢复
##### 12. fragment各种情况下的生命周期
##### 13. Fragment状态保存startActivityForResult是哪个类的方法，在什么情况下使用？
##### 14. 如何实现Fragment的滑动？
##### 15. fragment之间传递数据的方式？
##### 16. Activity 怎么和Service 绑定？
##### 17. 怎么在Activity 中启动自己对应的Service？
-  Activity通过bindService(Intent service, ServiceConnection  conn, int flags)跟Service进行绑定。
##### 18. service和activity怎么进行数据交互？
- 执行startService时，Service会经历onCreate->onStartCommand。当执行stopService时，直接调用onDestroy方法。调用者如果没有stopService，Service会一直在后台运行，下次调用者再起来仍然可以stopService。
  执行bindService时，Service会经历onCreate->onBind。这个时候调用者和Service绑定在一起。调用者调用unbindService方法或者调用者Context不存在了（如Activity被finish了），Service就会调用onUnbind->onDestroy。这里所谓的绑定在一起就是说两者共存亡了。
  多次调用startService，该Service只能被创建一次，即该Service的onCreate方法只会被调用一次。但是每次调用startService，onStartCommand方法都会被调用。Service的onStart方法在API 5时被废弃，替代它的是onStartCommand方法。
  第一次执行bindService时，onCreate和onBind方法会被调用，但是多次执行bindService时，onCreate和onBind方法并不会被多次调用，即并不会多次创建服务和绑定服务。
##### 19. Service的开启方式
##### 20. 请描述一下Service 的生命周期
##### 21. 谈谈你对ContentProvider的理解
##### 22. 说说ContentProvider、ContentResolver、ContentObserver 之间的关系
    -ContentProvider——内容提供者， 在android中的作用是对外共享数据，也就是说你可以通过ContentProvider把应用中的数据共享给其他应用访问，其他应用可以通过ContentProvider 对你应用中的数据进行添删改查。
    ContentResolver——内容解析者， 其作用是按照一定规则访问内容提供者的数据（其实就是调用内容提供者自定义的接口来操作它的数据）。
    ContentObserver——内容观察者，目的是观察(捕捉)特定Uri引起的数据库的变化，继而做一些相应的处理，它类似于数据库技术中的触发器(Trigger)，当   ContentObserver所观察的Uri发生变化时，便会触发它。

##### 23. 请描述一下广播BroadcastReceiver的理解
##### 24. 广播的分类
##### 25. 广播使用的方式和场景
##### 26. 在manifest 和代码中如何注册和使用BroadcastReceiver?
##### 27. 本地广播和全局广播有什么差别？
##### 28. BroadcastReceiver，LocalBroadcastReceiver 区别
 -BroadcastReceiver是针对应用间、应用与系统间、应用内部进行通信的一种方式
LocalBroadcastReceiver仅在自己的应用内发送接收广播，也就是只有自己的应用能收到，数据更加安全广播只在这个程序里，而且效率更高。
不能静态注册，只能采用动态注册的方式

##### 29. AlertDialog,popupWindow,Activity区别
##### 30. Application 和 Activity 的 Context 对象的区别
##### 31. Android属性动画特性
##### 32. 如何导入外部数据库?
##### 33. LinearLayout、RelativeLayout、FrameLayout的特性及对比，并介绍使用场景。
##### 34. 谈谈对接口与回调的理解
##### 35. 回调的原理
##### 36. 写一个回调demo
##### 37. 介绍下SurfView
##### 38. RecycleView的使用
##### 39. 序列化的作用，以及Android两种序列化的区别
##### 40. 差值器
##### 41. 估值器
##### 42. Android中数据存储方式

#### （2）Android源码相关分析

##### 1. Android动画框架实现原理
##### 2. Android各个版本API的区别
##### 3. Requestlayout，onlayout，onDraw，DrawChild区别与联系
-调用requestLayout()方法的时机是：当前View发生了一些改变，这个改变使得现有的View失效，所以调用requestLayout()方法对View树进行重新布局，过程包括了measure()和layout()过程，但不会调用draw()过程，即不会发生重新绘制视图过程。
 -onLayout()方法(如果该View是ViewGroup对象，需要实现该方法，对每个子视图进行布局)
-调用view.invalidate(),会触发onDraw()和computeScroll()。前提是该view被附加在当前窗口上。
-ViewGroup绘制自己的孩子通过dispatchDraw（canvas）实现，这个方法中调用drawChild()
##### 4. invalidate和postInvalidate的区别及使用
    前者要在主线程调用，后者哪里都可以调用
##### 5. Activity-Window-View三者的差别
 -1、activity的attach方法中执行了window的初始化，window的实例为PhoneWindow。
 2、activity的setContentView(ID)方法最终是调用的PhoneWindow的setContentView()方法。
 3、PhoneWindow在执行setContentView()的过程中生成了一个frameLayout的子类DecorView.并且根据feature的类型加载了一个对应的系统布局，放入了 decorview中。系统布局中有一个id为com.android.internal.R.id.content的framelayout,这个frameLayout作为一个父布局加载我们应用中自己定义的xml文件。

##### 6. 谈谈对Volley的理解
##### 7. 如何优化自定义View
  -(1)减少不必要的代码：对于频繁调用的方法，需要尽量减少不必要的代码。
  (2)不在 onDraw 中做内存分配的事：先从 onDraw 开始，需要特别注意不应该在这里做内存分配的事情，因为它会导致 GC，从而导致卡顿。在初始化或者动画间隙期间做分配内存的动作。不要在动画正在执行的时候做内存分配的事情。
  (3)减少 onDraw 被调用的次数：大多数时候导致 onDraw 都是因为调用了 invalidate().因此请尽量减少调用 invaildate()的次数。如果可能的话，尽量调用含有 4 个参数的 invalidate()方法而不是没有参数的 invalidate()。没有参数的 invalidate 会强制重绘整个 view。
  (4)减少 layout 的次数：一个非常耗时的操作是请求 layout。任何时候执行 requestLayout()，会使得 Android UI 系统去遍历整个View 的层级来计算出每一个 view 的大小。如果找到有冲突的值，它会需要重新计算好几次。
  (5)选用扁平化的 View：另外需要尽量保持 View 的层级是扁平化的（去除冗余、厚重和繁杂的装饰效果），这样对提高效率很有帮助。
  (6)复杂的 UI 使用 ViewGroup：如果你有一个复杂的 UI，你应该考虑写一个自定义的 ViewGroup 来执行他的 layout 操作。（与内置的view 不同，自定义的 view 可以使得程序仅仅测量这一部分，这避免了遍历整个 view 的层级结构来计算大小。）继承 ViewGroup作为自定义 view 的一部分，有子 views，但是它从来不测量它们。而是根据他自身的 layout 法则，直接设置它们的大小。

##### 8. 低版本SDK如何实现高版本api？
  1、添加注解 @TargetApi(Build.VERSION_CODES.N)
  不管项目的minSdkVersion是多少，被注解元素的的minSdk指定为特定版本，以跳过lint检查

  2、添加运行时SDK版本判断

##### 9. 描述一次网络请求的流程
1.通过URL找IP
2.对IP结果建立TCP连接
自己主机IP端口的对目标IP的端口（例：http://www.baidu.com http协议所占用的TCP端口为80端口）三次握手建立TCP连接。
3.向服务器发送数据
4.服务器解析，并返回
##### 10. HttpUrlConnection 和 okhttp关系
##### 11. Bitmap对象的理解
##### 12. looper架构
##### 13. ActivityThread，AMS，WMS的工作原理
##### 14. 自定义View如何考虑机型适配
##### 15. 自定义View的事件
##### 16. AstncTask+HttpClient 与 AsyncHttpClient有什么区别？
##### 17. LaunchMode应用场景
##### 18. AsyncTask 如何使用?
##### 19. SpareArray原理
##### 20. 请介绍下ContentProvider 是如何实现数据共享的？
##### 21. AndroidService与Activity之间通信的几种方式
##### 22. IntentService原理及作用是什么？
##### 23. 说说Activity、Intent、Service 是什么关系
##### 24. ApplicationContext和ActivityContext的区别
##### 25. SP是进程同步的吗?有什么方法做到同步？
##### 26. 谈谈多线程在Android中的使用
##### 27. 进程和 Application 的生命周期
##### 28. 封装View的时候怎么知道view的大小
##### 29. RecycleView原理
##### 30. AndroidManifest的作用与理解

#### (3)常见的一些原理性问题

##### 1. Handler机制和底层实现
##### 2. Handler、Thread和HandlerThread的差别
##### 3. handler发消息给子线程，looper怎么启动？
##### 4. 关于Handler，在任何地方new Handler 都是什么线程下?
##### 5. ThreadLocal原理，实现及如何保证Local属性？
##### 6. 请解释下在单线程模型中Message、Handler、Message Queue、Looper之间的关系
##### 7. 请描述一下View事件传递分发机制
##### 8. Touch事件传递流程
##### 9. 事件分发中的onTouch 和onTouchEvent 有什么区别，又该如何使用？
##### 10. View和ViewGroup分别有哪些事件分发相关的回调方法
##### 11. View刷新机制
    最终走到了父布局ViewGroup的invalidateChild()方法.通过一个do while循环查找父布局，最终指向了ViewRootImpl的invalidateChildInParent()方法.
   最后走到绘制三大流程都是在performTraversals。 View的测量、布局、绘制三大流程都是在performTraversals()方法中发起的。
##### 12. View绘制流程
https://blog.csdn.net/sinat_27154507/article/details/79748010
    measureChildWithMargins-getChildMeasureSpec。 会根据父布局的measurespec 确定子view的
    当父View的mode是EXACTLY的时候：说明父View的大小是确定的

子View的宽或高是MATCH_PARENT：
子View的宽或高是WRAP_CONTENT：子View是包裹布局，说明子View的大小还不确定，所以子View最大不能超过父View的大小mode=AT_MOST。
子View的宽或高是具体数值：子viewd大小已经固定了，子View的大小就是固定这个数值，mode=EXACTLY。
当父View的mode是AT_MOST的时候：说明父View大小是不确定的。

子View的宽或高是MATCH_PARENT：父View大小是不确定的，子View是填充布局情况，也不能确定大小，所以View大小不能超过父View的大小，mode=AT_MOST
子View的宽或高是WRAP_CONTENT：子View是包裹布局，大小不能超过父View的大小，mode=AT_MOST。
子View的宽或高是具体数值：子viewd大小已经固定了，子View的大小就是固定这个数值，mode=EXACTLY。 

    需要注意一点就是，此时的MeasureSpec并不是View真正的大小，只有setMeasuredDimension之后才能真正确定View的大小。
    getDefaultSize 主要作用就是根据View的建议最小值，结合父View传递的measureSpec，得出并返回measureSpec。 并不是父View 独自决定，它是根据父 view 的MeasureSpec加上子vIew的自己的LayoutParams，通过相应的规则转化而得到的大小
    setMeasuredDimension 作用就是将测量好的宽跟高进行存储。在onMeasure（） 必须调用这个方法，不然就会抛出 IllegalStateException 异常。
   
   draw 过程中一共分成7步，其中两步我们直接直接跳过不分析了。
  第一步：drawBackground(canvas)： 作用就是绘制 View 的背景。
  第三步：onDraw(canvas) ：绘制 View 的内容。View 的内容是根据自己需求自己绘制的，所以方法是一个空方法，View的继承类自己复写实现绘制内容。
  第三步：dispatchDraw（canvas）：遍历子View进行绘制内容。在 View 里面是一个空实现，ViewGroup 里面才会有实现。在自定义 ViewGroup 一般不用复写这个方法，因为它在里面的实现帮我们实现了子 View 的绘制过程，基本满足需求。
  第四步：onDrawForeground(canvas)：对前景色跟滚动条进行绘制。
  第五步：drawDefaultFocusHighlight(canvas)：绘制默认焦点高亮

##### 13. 自定义控件原理
##### 14. 自定义View如何提供获取View属性的接口？
##### 15. Android代码中实现WAP方式联网
##### 16. AsyncTask机制
##### 17. AsyncTask原理及不足
##### 18. 如何取消AsyncTask？
##### 19. 为什么不能在子线程更新UI？
##### 20. ANR产生的原因是什么？
##### 21. ANR定位和修正
##### 22. oom是什么？
##### 23. 什么情况导致oom？
##### 24. 有什么解决方法可以避免OOM？
##### 25. Oom 是否可以try catch？为什么？
    在try语句中声明了很大的对象，导致OOM，并且可以确认OOM是由try语句中的对象声明导致的，那么在catch语句中，可以释放掉这些对象，解决OOM的问题，继续执行剩余语句。

    但是这通常不是合适的做法。

    Java中管理内存除了显式地catch OOM之外还有更多有效的方法：比如SoftReference, WeakReference, 硬盘缓存等。
    在JVM用光内存之前，会多次触发GC，这些GC会降低程序运行的效率。
    如果OOM的原因不是try语句中的对象（比如内存泄漏），那么在catch语句中会继续抛出OOM
##### 26. 内存泄漏是什么？
    https://blog.csdn.net/weixin_41101173/article/details/79710782
##### 27. 什么情况导致内存泄漏？
##### 28. 如何防止线程的内存泄漏？
##### 29. 内存泄露场的解决方法
##### 30. 内存泄漏和内存溢出区别？
##### 31. LruCache默认缓存大小
    默认手机内存的1/8
##### 32. ContentProvider的权限管理(解答：读写分离，权限控制-精确到表级，URL控制)
    https://blog.csdn.net/anddlecn/article/details/51733690
##### 33. 如何通过广播拦截和abort一条短信？
##### 34. 广播是否可以请求网络？
    子线程可以，主线程超过10s引起anr
##### 35. 广播引起anr的时间限制是多少？
##### 36. 计算一个view的嵌套层级
##### 37. Activity栈
##### 38. Android线程有没有上限？
    其实这个没有上限的，因为资源都限制在这个进程里，你开多少线程都最多用这些资源
##### 39. 线程池有没有上限？
##### 40. ListView重用的是什么？
##### 41. Android为什么引入Parcelable？
##### 42. 有没有尝试简化Parcelable的使用？

#### (4)开发中常见的一些问题

##### 1. ListView 中图片错位的问题是如何产生的?
##### 2. 混合开发有了解吗？
##### 3. 知道哪些混合开发的方式？说出它们的优缺点和各自使用场景？（解答：比如:RN，weex，H5，小程序，WPA等。做Android的了解一些前端js等还是很有好处的)；
##### 4. 屏幕适配的处理技巧都有哪些?
##### 5. 服务器只提供数据接收接口，在多线程或多进程条件下，如何保证数据的有序到达？
##### 6. 动态布局的理解
##### 7. 怎么去除重复代码？
##### 8. 画出 Android 的大体架构图
##### 9. Recycleview和ListView的区别
##### 10. ListView图片加载错乱的原理和解决方案
##### 11. 动态权限适配方案，权限组的概念
##### 12. Android系统为什么会设计ContentProvider？
##### 13. 下拉状态栏是不是影响activity的生命周期
##### 14. 如果在onStop的时候做了网络请求，onResume的时候怎么恢复？
##### 15. Bitmap 使用时候注意什么？
##### 16. Bitmap的recycler()
##### 17. Android中开启摄像头的主要步骤
##### 18. ViewPager使用细节，如何设置成每次只初始化当前的Fragment，其他的不初始化？
    在setUserVisibleHint()方法中设置加载数据方法，加载数据方法中设置检测方法，如果视图已经初始化而且视图对用户可见（getUserVisibleHint()为true），则加载数据
##### 19. 点击事件被拦截，但是想传到下面的View，如何操作？
    虽然网上说的花里胡哨。但是没用，拦截后 手动在父view的ontouch 里调用子view的 dispatch
##### 20. 微信主页面的实现方式
##### 21. 微信上消息小红点的原理
##### 22. CAS介绍（这是阿里巴巴的面试题，我不是很了解，可以参考博客: CAS简介）

### 三、高级开发技术面试题

#### (1) 第三方框架

##### 1. 图片库对比
##### 2. 图片库的源码分析
##### 3. 图片框架缓存实现
##### 4. LRUCache原理
##### 5. 图片加载原理
##### 6. 自己去实现图片库，怎么做？
##### 7. Glide源码解析
##### 8. Glide使用什么缓存？
##### 9. Glide内存缓存如何控制大小？

#### (2) 网络和安全机制

##### 1. 网络框架对比和源码分析
##### 2. 自己去设计网络请求框架，怎么做？
##### 3. okhttp源码
##### 4. 网络请求缓存处理，okhttp如何处理网络缓存的
##### 5. 从网络加载一个10M的图片，说下注意事项
##### 6. TCP的3次握手和四次挥手
##### 7. TCP与UDP的区别
##### 8. TCP与UDP的应用
##### 9. HTTP协议
##### 10. HTTP1.0与2.0的区别
##### 11. HTTP报文结构
##### 12. HTTP与HTTPS的区别以及如何实现安全性
##### 13. 如何验证证书的合法性?
##### 14. https中哪里用了对称加密，哪里用了非对称加密，对加密算法（如RSA）等是否有了解?
##### 15. client如何确定自己发送的消息被server收到?
##### 16. 谈谈你对WebSocket的理解
##### 17. WebSocket与socket的区别
##### 18. 谈谈你对安卓签名的理解。
##### 19. 请解释安卓为啥要加签名机制?
##### 20. 视频加密传输
##### 21. App 是如何沙箱化，为什么要这么做？
##### 22. 权限管理系统（底层的权限是如何进行 grant 的）？

#### (3) 数据库

##### 1. sqlite升级，增加字段的语句
##### 2. 数据库框架对比和源码分析
##### 3. 数据库的优化
##### 4. 数据库数据迁移问题

#### (4) 算法

##### 1. 排序算法有哪些？
##### 2. 最快的排序算法是哪个？
##### 3. 手写一个冒泡排序
##### 4. 手写快速排序代码
##### 5. 快速排序的过程、时间复杂度、空间复杂度
##### 6. 手写堆排序
##### 7. 堆排序过程、时间复杂度及空间复杂度
##### 8. 写出你所知道的排序算法及时空复杂度，稳定性
##### 9. 二叉树给出根节点和目标节点，找出从根节点到目标节点的路径
##### 10. 给阿里2万多名员工按年龄排序应该选择哪个算法？
##### 11. GC算法(各种算法的优缺点以及应用场景)
##### 12. 蚁群算法与蒙特卡洛算法
##### 13. 子串包含问题(KMP 算法)写代码实现
##### 14. 一个无序，不重复数组，输出N个元素，使得N个元素的和相加为M，给出时间复杂度、空间复杂度。手写算法
##### 15. 万亿级别的两个URL文件A和B，如何求出A和B的差集C(提示：Bit映射->hash分组->多文件读写效率->磁盘寻址以及应用层面对寻址的优化)
##### 16. 百度POI中如何试下查找最近的商家功能(提示：坐标镜像+R树)。
##### 17. 两个不重复的数组集合中，求共同的元素。
##### 18. 两个不重复的数组集合中，这两个集合都是海量数据，内存中放不下，怎么求共同的元素？
##### 19. 一个文件中有100万个整数，由空格分开，在程序中判断用户输入的整数是否在此文件中。说出最优的方法
##### 20. 一张Bitmap所占内存以及内存占用的计算
##### 21. 2000万个整数，找出第五十大的数字？
##### 22. 烧一根不均匀的绳，从头烧到尾总共需要1个小时。现在有若干条材质相同的绳子，问如何用烧绳的方法来计时一个小时十五分钟呢？
##### 23. 求1000以内的水仙花数以及40亿以内的水仙花数
##### 24. 5枚硬币，2正3反如何划分为两堆然后通过翻转让两堆中正面向上的硬8币和反面向上的硬币个数相同
##### 25. 时针走一圈，时针分针重合几次
##### 26. N*N的方格纸,里面有多少个正方形
##### 27. x个苹果，一天只能吃一个、两个、或者三个，问多少天可以吃完？

#### (5) 插件化、模块化、组件化、热修复、增量更新、Gradle

##### 1. 对热修复和插件化的理解
##### 2. 插件化原理分析
##### 3. 模块化实现（好处，原因）
##### 4. 热修复,插件化
##### 5. 项目组件化的理解
##### 6. 描述清点击 Android Studio 的 build 按钮后发生了什么

#### (6) 架构设计和设计模式

##### 1. 谈谈你对Android设计模式的理解
##### 2. MVC MVP MVVM原理和区别
##### 3. 你所知道的设计模式有哪些？
##### 4. 项目中常用的设计模式
##### 5. 手写生产者/消费者模式
##### 6. 写出观察者模式的代码
##### 7. 适配器模式，装饰者模式，外观模式的异同？
##### 8. 用到的一些开源框架，介绍一个看过源码的，内部实现过程。
##### 9. 谈谈对RxJava的理解
##### 10. RxJava的功能与原理实现
##### 11. RxJava的作用，与平时使用的异步操作来比的优缺点
##### 12. 说说EventBus作用，实现方式，代替EventBus的方式
##### 13. 从0设计一款App整体架构，如何去做？
##### 14. 说一款你认为当前比较火的应用并设计(比如：直播APP，P2P金融，小视频等)
##### 15. 谈谈对java状态机理解
##### 16. Fragment如果在Adapter中使用应该如何解耦？
##### 17. Binder机制及底层实现
##### 18. 对于应用更新这块是如何做的？(解答：灰度，强制更新，分区域更新)？
##### 19. 实现一个Json解析器(可以通过正则提高速度)
##### 20. 统计启动时长,标准

#### (7) 性能优化

##### 1. 如何对Android 应用进行性能分析以及优化?
    尽量减少布局层级和复杂度
     善用Tag include merge
    使用traceView  检查代码的耗时区
    检查内存泄漏
    图片进行压缩 
    findbugs
    最后不合理的产品需求
##### 2. ddms 和 traceView
##### 3. 性能优化如何分析systrace？
##### 4. 用IDE如何分析内存泄漏？
##### 5. Java多线程引发的性能问题，怎么解决？
##### 6. 启动页白屏及黑屏解决？
    做成主题图层  给启动页
##### 7. 启动太慢怎么解决？
##### 8. 怎么保证应用启动不卡顿？
##### 9. App启动崩溃异常捕捉
##### 10. 自定义View注意事项
##### 11. 现在下载速度很慢,试从网络协议的角度分析原因,并优化(提示：网络的5层都可以涉及)。
##### 12. Https请求慢的解决办法（提示：DNS，携带数据，直接访问IP）
##### 13. 如何保持应用的稳定性
##### 14. RecyclerView和ListView的性能对比
##### 15. ListView的优化
##### 16. RecycleView优化
##### 17. View渲染
##### 18. Bitmap如何处理大图，如一张30M的大图，如何预防OOM
##### 19. java中的四种引用的区别以及使用场景
##### 20. 强引用置为null，会不会被回收？
    会 只要没有引用
#### (8) NDK、jni、Binder、AIDL、进程通信有关

##### 1. 请介绍一下NDK
##### 2. 什么是NDK库?
##### 3. jni用过吗？
##### 4. 如何在jni中注册native函数，有几种注册方式?
##### 5. Java如何调用c、c++语言？
##### 6. jni如何调用java层代码？
##### 7. 进程间通信的方式？
##### 8. Binder机制
##### 9. 简述IPC？
##### 10. 什么是AIDL？
##### 11. AIDL解决了什么问题？
##### 12. AIDL如何使用？
##### 13. Android 上的 Inter-Process-Communication 跨进程通信时如何工作的？
##### 14. 多进程场景遇见过么？
##### 15. Android进程分类？
##### 16. 进程和 Application 的生命周期？
##### 17. 进程调度
##### 18. 谈谈对进程共享和线程安全的认识
##### 19. 谈谈对多进程开发的理解以及多进程应用场景
##### 20. 什么是协程？

#### (9) framework层、ROM定制、Ubuntu、Linux之类的问题

##### 1. java虚拟机的特性
##### 2. 谈谈对jvm的理解
##### 3. JVM内存区域，开线程影响哪块内存
##### 4. 对Dalvik、ART虚拟机有什么了解？
##### 5. Art和Dalvik对比
##### 6. 虚拟机原理，如何自己设计一个虚拟机(内存管理，类加载，双亲委派)
##### 7. 谈谈你对双亲委派模型理解
##### 8. JVM内存模型，内存区域
##### 9. 类加载机制
##### 10. 谈谈对ClassLoader(类加载器)的理解
##### 11. 谈谈对动态加载（OSGI）的理解
##### 12. 内存对象的循环引用及避免
##### 13. 内存回收机制、GC回收策略、GC原理时机以及GC对象
##### 14. 垃圾回收机制与调用System.gc()区别
##### 15. Ubuntu编译安卓系统
##### 16. 系统启动流程是什么？（提示：Zygote进程 –> SystemServer进程 –> 各种系统服务 –> 应用进程）
##### 17. 大体说清一个应用程序安装到手机上时发生了什么
##### 18. 简述Activity启动全部过程
##### 19. App启动流程，从点击桌面开始
##### 20. 逻辑地址与物理地址，为什么使用逻辑地址？
##### 21. Android为每个应用程序分配的内存大小是多少？
##### 22. Android中进程内存的分配，能不能自己分配定额内存？
##### 23. 进程保活的方式
##### 24. 如何保证一个后台服务不被杀死？（相同问题：如何保证service在后台不被kill？）比较省电的方式是什么？
##### 25. App中唤醒其他进程的实现方式


### 四、跨平台Hybrid 开发

##### 1. flutter
##### 2. Html5项目实战
##### 3. HTML&CSS&JavaScript 实战
##### 4. WordPress搭建网站项目实战
##### 5. 前端Vue架构
##### 6. 前端样式开发
##### 7. Weex内置能力
##### 8. Weex原生应用
##### 9. Weex扩展框架
##### 10. WeexUI架构
##### 11. 介绍你做过的哪些项目
##### 12. 都使用过哪些框架、平台？
##### 13. 都使用过哪些自定义控件？
##### 14. 研究比较深入的领域有哪些？
##### 15. 对业内信息的关注渠道有哪些？
##### 16. 最近都读哪些书？
##### 17. 有没有什么开源项目？
##### 18. 自己最擅长的技术点，最感兴趣的技术领域和技术点
##### 19. 项目中用了哪些开源库，如何避免因为引入开源库而导致的安全性和稳定性问题
##### 20. 实习过程中做了什么，有什么产出？


