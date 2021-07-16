##### DirectByteBuffer

- 直接内存，省去了将对象从堆外内存复制到堆内内存的过程

  

##### java的四种引用类型

- 强引用：普通的对象赋值就是强引用，GC不会回收强引用的对象。当内存空间不足时，GC宁愿报OOM异常也不会回收具有强引用的对象
- 软引用：可以通过java.lang.ref.SoftReference使用软引用，GC回收机制会在内存不足时回收具有软引用的对象
- 弱引用：可以用java.lang.ref.WeakReference实例来保存对一个Java对象的弱引用，被GC扫描到了的弱引用的对象，无论内存是否充足，都会被回收
- 虚引用：虚引用并不会决定对象的生命周期。虚引用关联的唯一目的是使该对象被回收时得到一个系统通知，一个比较典型的引用场景便是堆外内存的回收。虚引用必须配合ReferenceQueue使用
