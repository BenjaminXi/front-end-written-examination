# 数据结构
### <a id="数组和链表什么区别">数组和链表什么区别</a>
* 存储方式不同：数组是将元素在内存中连续存放，由于每个元素占用内存相同，可以通过下标迅速访问数组中任何元素；链表恰好相反，链表中的元素在内存中不是顺序存储的，而是通过存在元素中的指针联系到一起。比如：上一个元素有个指针指到下一个元素，以此类推，直到最后一个元素。如果要访问链表中一个元素，需要从第一个元素开始，一直找到需要的元素位置。
* 增加删除方式不同：数组中增加一个元素，需要移动大量元素，在内存中空出一个元素的空间，然后将要增加的元素放在其中。同样的道理，如果想删除一个元素，同样需要移动大量元素去填掉被移动的元素。如果应用需要快速访问数据，很少或不插入和删除元素，就应该用数组。链表中增加和删除一个元素非常简单，只要修改元素中的指针就可以了。如果应用需要经常插入和删除元素你就需要用链表数据结构了。

### <a id="堆和栈有什么区别和联系">堆和栈有什么区别和联系</a>
* 分配释放方式不同：堆是由编译器自动分配释放，栈由程序员分配释放；
* 存放不同：堆用于存放对象，栈用于执行程序；
* 线程共享不同：堆可以被多个线程共享，栈不可以被多个线程共享；
* 存储空间不同：堆空间不连续，栈空间连续；
* 读取速度不同：堆速度慢，栈速度快。
* 生存期不同：栈的生存期是确定的，因此缺乏一定的灵活性；堆在运行时动态分配内存，生存期不用提前告诉编译器，导致读取速度慢。

### <a id="根据前序遍历和后序遍历求中序遍历">根据前序遍历和后序遍历求中序遍历</a>
无法确定唯一的二叉树

### <a id="构建二叉搜索树">如何用34,76,45,18,26,54,92,65构建二叉搜索树，并求树的深度</a>

### 时间复杂度最好的为O(n)的是,时间复杂度最坏的为O(n\*n) 的是,稳定的排序有,<a id=""></a>
A快速排序 B基数排序 C堆排序 D归并排序 E冒泡排序

### 用递归实现深度优先算法

### 编程题
#### 一串字母数字符号混合的字符串，输出小写字母
#### 输入逗号分割的数字，输出被除数。如输入2,4,6,8,10,3,9;输出4,6,8,10,9.
#### 输入“I am a student.” 实现输出"student. a am I".
#### 对称的字符串的最大长度
#### rand5可以随机产生1到5的一个整数，如何用rand5构建rand7，使其能随机产生1到7的一个整数。
#### 散列表

#### 链表反转
#### 静态构造函数
```
public sealed class Singleton{
 private Singleton(){}
 private static Singleton instance = new Singleton();
 public static Singleton Instance{
  get{
   return instance;
  }
 }
}
```
这个不太理解，待更新。
