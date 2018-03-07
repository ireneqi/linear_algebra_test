# linear_algebra_test
linear_algebra_test
#Jupyter Note第一次使用
#初学者的尝试，请多指正

#swapRow方法和addScaledRow方法做了题目没要要求的异常处理。
因为我首先接触的是JavaScript，在学习的时候曾经有从客户端传数据到function 的相关做法，前辈曾经教过，稳定的程序一定不能出现错误（结果会出现闪退），宁可多抛出异常，写好的function有可能不是自己调用，（尤其是参数是有范围的，一定要验证）多重验证抛出错误信息有利于代码的维护，js在很多时候是静默错误的。要维持程序的稳定性一定要做到“防火防盗防闪退”。

Gaussian Jordan 消元法求解 Ax = b

高斯消元法引用了以下博客的思路及代码
1 http://blog.csdn.net/cheneyshark/article/details/78752614
这篇文章使用了numpy，看过之后觉得思路比较清晰了，但是不用numpy修改出错多次。
2 http://www.cnblogs.com/zingp/p/8011295.html
然后再这篇博文中发现更干净的写法，修改了原来的代码。
感谢以上两篇文章的分享。
