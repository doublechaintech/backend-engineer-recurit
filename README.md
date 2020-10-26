# 双链科技java后台工程师招聘

因为业务发展需要，双链科技正在招聘工程师。但每天收到大量内容非常相似的简历，简历筛选让我们头痛不已，而软件工程师还是要靠代码说话的，所以不如看代码直接一些。


请完成下列函数，从一个List中取得最大值：

```java

pulic Integer getMaxValue(List valueList){
    return  null;
}

```

要求：

* Java 8可编译通过并运行
* 把您这样做的原因写下来

提示：
* 这是一个公用函数，请考虑这个函数的安全性，健壮性，在小规模数据量下10000条的性能；
* 函数命名对于长期维护非常重要，就像希腊语之于数学，英语是计算机的母语，故请使用美式英语命名变量；
* 本考题看似简单，但是考到的知识点非常多，我们需要基础知识扎实严谨的软件工程师；
* 请在一天内完成本项目，不同水平的程序员做到的程度会不一样；
* 您可以fork本项目，在您自己的github账号的本页面完成，您的答案属于您；
* 完成之后，请使用您在github的账号邮箱（可能您需要把该邮箱设置为公开)发送通知到 zhangxilai#doublechaintech.com，通知中请包含你的github repo地址和您的答案(方便我查看）


```
//在您自己的READ.md中，答案写到下面的位置
public Integer getMaxValue(List valueList){
    return  (Integer) Collections.max(valueList);
}

//这样做的原因写到下面
collections类是集合的工具类，里面有大量的方法可以操作集合，Collections.max()方法可以获取集合中的最大值；
此公用函数有局限性，它的数据类型是包装类Integer，所以只针对int类型，对其他数据类型不适用。

```
