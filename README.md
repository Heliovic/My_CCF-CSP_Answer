# My_CCF-CSP_Answer
记录我在解 CCF - CSP 时遇到的一些问题以及总结的经验。

## 201803-1 跳一跳

[Java (100/100)](https://github.com/Heliovic/My_CCF-CSP_Answer/blob/master/201803/20180301/Main.java)

## 201803-2 碰撞的小球

[Java (100/100)](https://github.com/Heliovic/My_CCF-CSP_Answer/blob/master/201803/20180302/Main.java)

### 解题思路

简单模拟

## 201803-3 URL映射

[Java (60/100)](https://github.com/Heliovic/My_CCF-CSP_Answer/blob/master/201803/20180303/Main.java)

### 解题思路

字符串处理

## 201803-4 棋局评估

[C++ (90/100)](https://github.com/Heliovic/My_CCF-CSP_Answer/blob/master/201803/20180304/main.cpp)

### 解题思路

博弈搜索。

* 对于 Alice，她想获得高分，就需要抑制 Bob，不让他获得低分数（绝对值高分）。因此需要遍历当前棋盘下每一种落子方案，选择使得 Bob 得到较高（绝对值较低）的分数。

* 对 Bob 同理，要抑制 Alice 获得高分，就要从每一种落子方案中选择使得 Alice 得分最低的那一个。

* 注意，在选择落子之前，要检查是否已经决出胜负或平局。

* 有 10 分没拿到，暂时不知为何。
