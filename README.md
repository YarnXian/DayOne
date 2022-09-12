# DayOne
分享一道Python算法题:

给你一个整数 x ，如果 x 是一个回文整数，返回 true ；否则，返回 false 。

* 回文数是指正序（从左向右）和倒序（从右向左）读都是一样的整数。

* 例如，121 是回文数，而 123 不是。

代码展示：
```Python
UpsideNumber = 121
if str(UpsideNumber)[::-1] == str(UpsideNumber):
    print(True)
else:
    print(False)
```
在上面的案例中，我们定义一个数值`UpsideNumber`，然后我们将它倒序输出，如果倒序输出的值等于原数值，就可以判定这是回文数，反之则不是。同样地，`UpsideNumber`不仅仅可以是一个数值，它也可以是字符串。这样我们便可以检测回文联：


```Python
UpsideNumber = '天连水尾水连天'
if str(UpsideNumber)[::-1] == str(UpsideNumber):
    print(True)
else:
    print(False)
```

输出结果是True。
