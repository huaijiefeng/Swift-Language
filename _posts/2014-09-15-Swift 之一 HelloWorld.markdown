---
layout: post
title:  "Swift 之一 HelloWorld"
date:   2014-09-15 17:38:06
categories: jekyll update
---


{% highlight swift %}
println("Hello, World!")	
{% endhighlight %}


{% highlight swift %}
#var 声明变量
var code = 1

#let 生命常量
let LABEL = "THIS IS A FLAG"
{% endhighlight %}  

#转字符串
{% highlight swift %}
#第一种方式
let test = "hello " + String(code);

#第二种方式
let string = "i have \(code)  apple";
{% endhighlight %}  

{% highlight swift %}
#定义数组
var array = ["apple", "fruit", "tree"]

#定义字典
var map=["opiton1":"tree", "option2":"apple"]
{% endhighlight %}  


#控制流
{% highlight swift %}
for tst  in array
{
    println(tst)
}
{% endhighlight %}  







