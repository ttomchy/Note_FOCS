# 第十三章复习题

#### 1. 通常文件有哪两种存取方式？

顺序存取，随机存取

#### 2. 新主文件和旧主文件之间是什么关系？

新主文件为旧主文件更新后的文件

#### 3. 在顺序文件更新时，事务文件的作用是什么？

事务文件用于记录更新的操作，并结合旧主文件形成新主文件

#### 4. 描述随机文件存取的地址函数

地址函数将键映射成地址

#### 5. 在索引文件中，索引是如何关联数据文件的？

通过键和地址的表进行关联

#### 6. 在文件直接散列法中键和地址之间是什么关系？

键就是地址

#### 7. 在文件除余散列法中键和地址之间是什么关系？

键对一个固定的数取模再加1后得到地址

#### 8. 在文件数字析取散列法中键和地址之间是什么关系？

从键中摘取部分位拼成地址

#### 9. 给出三种解决冲突的方法

开放寻址法，链表哈希法，桶哈希法

#### 10. 文本文件和二进制文件之间的区别是什么？

解码方式不同。文本文件按字符编码表解码，二进制文件直接解码成对应的十进制或十六进制数字。