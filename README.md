# asn.1 tool

## 介绍
解码4G、5G消息码流，包括终端和基站的接入层消息。

## 联系方式
有合作需求或者技术上的问题，请邮件联系：easy_codec@126.com


## 安装教程

目前工具只支持Windows系统。

点击EasyCodec.msi直接安装。

## 使用说明

它是一款具有编码和解码的工具，它是一款覆盖基站和终端多种接口消息的编码和解码工具，它还是一款编码和解码分析工具，通过它，你可以清晰的了解码流的每一位代表的含义。

## 操作效果

先看一下这个工具的操作，给大家一个直观感受。

![asn1工具](./README.assets/asn1工具.gif)

## **界面功能划分**

界面功能划分如下图所示：

![image-20240122101429523](./README.assets/image-20240122101429523.png)

## **广泛的协议支持**

工具支持3GPP空口，F1AP，NGAP，E1AP，XNAP等协议消息的编解码。



## **一目了然的IE类型**

每条IE都会有一个图标，标识每个IE的ANS.1类型，具体的图标含义如下：



- <img src="./README.assets/409fe1822f988397af7ab5dc7d5968e0.png" alt="img" style="zoom:10%;" />  boolean类型
- <img src="./README.assets/a90aa2e2155480eaaefbe0690b97d39c.png" alt="img" style="zoom:10%;" />  choice类型
- <img src="./README.assets/afed5094d06a622acf3506300d46e022.png" alt="img" style="zoom:10%;" />  enumerated类型
- <img src="./README.assets/d0b5c21daad948519e01d0bf16d4c6ce.png" alt="img" style="zoom:10%;" />  integer类型
- <img src="./README.assets/3dba1f5a0d81ff09e4e6523d1c02a6ef.png" alt="img" style="zoom:10%;" />  numericString类型
- <img src="./README.assets/37b4b2445a7f828575c654a36ad65433.png" alt="img" style="zoom:10%;" />  null类型
- <img src="./README.assets/ffdf397e7ffe0726d8de78dd1a4c152c.png" alt="img" style="zoom:10%;" />  object identifier类型
- <img src="./README.assets/77d42f482e89ff7d18fba958c76c177e.png" alt="img" style="zoom:10%;" />  octetstring类型
- <img src="./README.assets/3b17e2557ed053cac8f212879cf4bf08.png" alt="img" style="zoom:10%;" />  open type类型
- <img src="./README.assets/b6225b228448493a28d92fd73dceb149.png" alt="img" style="zoom:10%;" />  printable string类型
- <img src="./README.assets/89f3a8abe75f8858e969ee36469780ee.png" alt="img" style="zoom:10%;" />  real类型
- <img src="./README.assets/21c281686934a4cb5eda6cdab7f13aab.png" alt="img" style="zoom:10%;" />  sequence类型
- <img src="./README.assets/2d677a352bd806aa6fb2c1fba73536ce.png" alt="img" style="zoom:10%;" />  sequence of类型
- <img src="./README.assets/af6622072671bc3946ce291db92e7e48.png" alt="img" style="zoom:10%;" />  set类型
- <img src="./README.assets/d4b748547aaa23d453bccf3f7cafd840.png" alt="img" style="zoom:10%;" />  visible string类型
- <img src="./README.assets/fc9c443f31bcdff5b5a34165f463e777.png" alt="img" style="zoom:10%;" />  bitstring类型



## **方便快捷的输入方式**

![img](./README.assets/a0e4a1f223d4441fdde3fc7170c0acd8.png)

元素显示区的第二列可以输入不同类型的值，根据ASN.1的类型不同，输入数值的方式会有些差异。

在输入前，需要选中对应的IE行，然后再点击输入区对应的IE行，即可输入。敲击回车键或者鼠标点击“值输入区”以外的区域，输入值生效。



## **强大的搜索功能**

![image-20240122101828417](./README.assets/image-20240122101828417.png)

支持各种查找功能，并且在输入关键字的时候可以对历史关键字进行自动匹配和补齐。如下：

![image-20240122102030959](./README.assets/image-20240122102030959.png)



