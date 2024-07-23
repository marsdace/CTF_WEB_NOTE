# BUUCTF WEB 2-Havefun解题过程【GET请求】

## **解题思路**

![1721542685094](images/2-Havefun/1721542685094.png)

查看源码，发现一段代码。通过代码可知，GET请求一个参数cat，当该参数的值为‘dog’时会输出东西。

![1721542756388](images/2-Havefun/1721542756388.png)

## 解题过程

直接在url后加上 ？cat =dog

![1721543116637](images/2-Havefun/1721543116637.png)

解题成功。

## 解题原理【GET请求】

GET和POST是HTTP协议中的两种发送请求的方法。

通过在url后加上?id=1 进行GET请求。

例如：

![](https://upload-images.jianshu.io/upload_images/19874706-9bfb333bf64c0ac4.png?imageMogr2/auto-orient/strip|imageView2/2/format/webp)

![](https://upload-images.jianshu.io/upload_images/19874706-5e1c9d04560a01b1.png?imageMogr2/auto-orient/strip|imageView2/2/format/webp)

###### 参考内容

[CTF_S10Sec的[什么是GET | 什么是POST]讲解(网页攻防Web)]https://www.jianshu.com/p/d492dc495062
