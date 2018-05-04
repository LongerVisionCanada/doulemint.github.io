---
layout: post
title:  "Welcome to MyBlog about Machine learning!"
date:   2018-04-28 14:34:25
categories: jekyll update
tags: featured
image: /assets/article_images/2014-08-29-welcome-to-jekyll/desktop.JPG
---
####导语：
>这里记录基础的线性回归&梯度下降的学习笔记。我的资料来源自[LearningTensorflow](https://github.com/SaoYan/LearningTensorflow)
希望自己可以通过写博客让自己的思路再次梳理一遍！温故知新~
最后记得常翻官方文档哦！[Tensorflow](http://www.tensorflow.org/)还有[numpy reference](https://docs.scipy.org/doc/numpy/genindex.html)

##一·初识tensorflow&python基础
| Tables        | Are           | Cool  |

	
| ------------- |:-------------:| -----:|

	
| tf.constant()    | 常量          | shape |

	
| tf.Variable(initial_number,type)    | 变量          |   $12 |

	
| tf.placeholder() | 待输入值      |    $1 |


###constant

```python
#定义常量并加减
x = tf.constant([[5,2],[2,1]])
y = tf.constant([2])
z = tf.add(x,y)
with tf.Session() as sess:
    print(sess.run(z))
>>>  [[7 4]
     [4 3]]	
```

###Variable


{% highlight ruby %}
print("\n build a variable...\n")
W = tf.Variable(.3, tf.float32)

# we can also get W by:

C = tf.constant(.3, tf.float32)
W = tf.Variable(C)
b = tf.Variable(-.3, tf.float32)
#=>w = 0.3 ; b = -0.3.
{% endhighlight %}



program：House Price Pediction 之 Tensorflow 学习笔记--（1）

####House Price Pediction 之 Tensorflow 学习笔记--（1）


tf.constant([][]);
tf.Variable([])
tf.placeholder([])
tf.assign()
<footer class="site-footer">
 <a class="subscribe" href="{{ "/feed.xml" | prepend: site.baseurl }}"> <span class="tooltip"> <i class="fa fa-rss"></i> Subscribe!</span></a>
  <div class="inner">a
   <section class="copyright">All content copyright <a href="mailto:{{ site.email}}">{{ site.name }}</a> &copy; {{ site.time | date: '%Y' }} &bull; All rights reserved.</section>
   <section class="poweredby">Made with <a href="http://jekyllrb.com"> Jekyll</a></section>
  </div>
</footer>
{% endhighlight %}


