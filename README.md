## data_validation

### 1. 唯一性

### 2. 完整性
**条目记录缺损，或超过边界**

### 3. 合法性
**依赖冲突 ，按照业务逻辑计算后结果违背预期**

date_vld函数：按照业务逻辑计算账期时间、账期跨度、截止某一个时间点的账期数

**具体功能：**（尽量只使用基础包）

1.以账期为单位，已知某个时间点，推算n个账期之后的应还日期，返回具体的时间值

2.推算某合同截止某一时间点（或当前）的应还期次

3.

4.计算两个时间点之间相差的年数、月数、天数

5.计算从某个时间点开始经过n年、n月、n日之后的时间值
