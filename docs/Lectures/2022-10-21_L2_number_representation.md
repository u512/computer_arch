# 数字表示

## 数据输入: 模拟->数字

真实时间都是模拟的

为了导入模拟的信息，我们必须要做两件事:

- 采样

- 量化

## Bit可以表示一切

**字符**

- 26个字母 => 5 bits就可以表示(2^5=32)

- 大小写字母 + 标点符号 => 8 bits就可以表示 ("ASCII")

- 表示世界上所有语言的标准码 => 8, 16, 32 bits表示 ("Unicode")


**逻辑值**

- 0 => False
- 1 => True

**颜色**

- 00 => Red
- 01 => Green
- 10 => Blue

!!! note

    N bits最多能表示 2^N 个不同的值

## 十进制/二进制/十六进制

**十进制:** 0, 1, 2, 3, 4, 5, 6, 7, 8, 9

例如:

$$
 5128 = {5124}_{10} = 5 \times {10}^{3} + 1 \times {10}^{2} + 2 \times {10}^{1} + 8 \times {10}^{0}
$$

**二进制:** 0, 1

例如: "1011"用二进制记为"0b1011"

$$
 1011 = {1011}_{2} = 1 \times {2}^{3} + 0 \times {2}^{2} + 1 \times {2}^{1} + 1 \times {2}^{0} = 11
$$

**十六进制:** 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F

其中:

- A => 10
- B => 11
- C => 12
- D => 13
- E => 14
- F => 15

例如: "C9"用十六进制记为"0xC9"

$$
 C9 = {C9}_{16} = 12 \times {16}^{1} + 9 \times {16}^{0} = 201
$$


## 数字表示

