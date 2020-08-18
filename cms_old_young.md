年轻代与老年代

## 对象何时进入老年代 

1 迭代年龄判断
2 大对象直接进入老年代
3 Young GC 后 Survivor 区放不下，按照一定的优先级，将对象放入老年代。
4 Survivor 区空间占用过半，假设年龄为1～n的对象占用了过半的空间，则年龄>n的对象进入老年代






refs
https://en.wikipedia.org/wiki/Garbage_collection_(computer_science)
https://www.cs.rit.edu/~ark/lectures/gc/08_00_00.html
https://juejin.im/post/6844903954845794311
