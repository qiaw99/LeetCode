# [403. 青蛙过河](https://leetcode-cn.com/problems/frog-jump)

## 题目描述
<!-- 这里写题目描述 -->
<p>一只青蛙想要过河。 假定河流被等分为&nbsp;x<em>&nbsp;</em>个单元格，并且在每一个单元格内都有可能放有一石子（也有可能没有）。 青蛙可以跳上石头，但是不可以跳入水中。</p>

<p>给定石子的位置列表（用单元格序号升序表示），&nbsp;<strong>请判定青蛙能否成功过河</strong>（即能否在最后一步跳至最后一个石子上）。&nbsp;开始时，&nbsp;青蛙默认已站在第一个石子上，并可以假定它第一步只能跳跃一个单位（即只能从单元格1跳至单元格2）。</p>

<p>如果青蛙上一步跳跃了&nbsp;<em>k&nbsp;</em>个单位，那么它接下来的跳跃距离只能选择为&nbsp;<em>k - 1</em>、<em>k&nbsp;</em>或&nbsp;<em>k + 1</em>个单位。&nbsp;另请注意，青蛙只能向前方（终点的方向）跳跃。</p>

<p><strong>请注意：</strong></p>

<ul>
	<li>石子的数量 &ge; 2 且&nbsp;&lt; 1100；</li>
	<li>每一个石子的位置序号都是一个非负整数，且其 &lt; 2<sup>31</sup>；</li>
	<li>第一个石子的位置永远是0。</li>
</ul>

<p><strong>示例&nbsp;1:</strong></p>

<pre>
<strong>[0,1,3,5,6,8,12,17]</strong>

总共有8个石子。
第一个石子处于序号为0的单元格的位置, 第二个石子处于序号为1的单元格的位置,
第三个石子在序号为3的单元格的位置， 以此定义整个数组...
最后一个石子处于序号为17的单元格的位置。

返回 <strong>true</strong>。即青蛙可以成功过河，按照如下方案跳跃： 
跳1个单位到第2块石子, 然后跳2个单位到第3块石子, 接着 
跳2个单位到第4块石子, 然后跳3个单位到第6块石子, 
跳4个单位到第7块石子, 最后，跳5个单位到第8个石子（即最后一块石子）。
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>[0,1,2,3,4,8,9,11]</strong>

返回 <strong>false。</strong>青蛙没有办法过河。 
这是因为第5和第6个石子之间的间距太大，没有可选的方案供青蛙跳跃过去。
</pre>



## 解法
<!-- 这里可写通用的实现逻辑 -->


### Python3
<!-- 这里可写当前语言的特殊实现逻辑 -->

```python

```

### Java
<!-- 这里可写当前语言的特殊实现逻辑 -->

```java

```

### ...
```

```
