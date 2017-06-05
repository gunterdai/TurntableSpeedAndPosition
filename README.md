# TurntableSpeedAndPosition

## 单轴转台的速率与位置测试

### 测试目的

摸清转台的特性，找出合适的标定方法。

### 测试方法

五个速率点（10deg/s、30deg/s、60deg/s、90deg/s、120deg/s），分别进行速率标定和位置（一圈、两圈、三圈）标定，求出陀螺的比例因子进行分析。

### 测试结果

表1：陀螺的比例因子 <br>

比例因子 | 速率 | 一圈 | 两圈 | 三圈
------- | ----------------- | ----------------- | ----------------- | -----------------
10deg/s | 1.002444509045226 | 1.002487512861111 | 1.002376826416666 | 1.002447856916665
30deg/s | 1.002438845771145 | 1.002671148430556 | 1.002595940025000 | 1.002456014518519
60deg/s | 1.001625969169719 | 1.001920025875000 | 1.001831266708334 | 1.001775962453703
90deg/s | 1.000332211464577 | 1.000885678875000 | 1.000633222270834 | 1.000538447876852
120deg/s | 0.999612448910081 | 1.000171160833334 | 0.999966452971528 | 0.999821007324074

图1：陀螺的比例因子与圈数的关系 <br>

![](https://github.com/XinLiGitHub/TurntableSpeedAndPosition/raw/master/Software/untitled.bmp) <br>

图2：陀螺的比例因子与速率的关系 <br>

![](https://github.com/XinLiGitHub/TurntableSpeedAndPosition/raw/master/Software/untitled1.bmp) <br>

### 测试结论

低速（10deg/s、30deg/s、60deg/s）情况下，速率标定与位置标定，求出的陀螺的比例因子相差在万分之一。高速（90deg/s、120deg/s）情况下，速率标定与位置标定，求出的陀螺的比例因子相差在万分之二。
低速情况下的标定精度要高一些，旋转周数越多标定精度越高。
