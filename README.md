# c++
1.unordered_map

leetcode滑动链表相关的两道题3,159使用了unordered_map，根据YouTube博主The Cherno的Maps in c++整理得到。
要在vector中找到一个元素，即使借助sort，也是比较慢的。map可以解决。key和value。
c++中的map有两种，map和unordered_map，一个是ordered，其底层是红黑树；一个是unordered，底层是hash table。对顺序没有要求时，建议使用unordered_map，因为其速度更快。
