## 分布式计算与网络第七次作业


### 习题

#### p1  
a.

|  目标地址   | 端口  |
|  ----  | ----  |
| H3的IP  | 3 |

b.
```
无法实现，因为转发表中没有源IP信息
```
#### p4
a.
```
所需最小时隙为3，第一个时隙同时发送与接受X,Y,第二个时隙同时发送与接受X,Y，第三个时隙发送Z。
```
b.
```
所需最大时隙依然为3，因为根据空闲发送队列永不空闲的原则，X,Y总是会被同时发送，3个时隙将会完成。
```
#### p6
|  地址范围   |数量  | 端口  |
|  ----  | ----  | ----  |
| 00000000-00111111  | 64 |0 |
| 01000000-01011111  | 32 |1 |
| 01100000-01111111  | 32 |2 |
| 10000000-10111111  | 64 |2 |
| 11000000-11111111  | 64 |3 |
