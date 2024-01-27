# asn.1 tool

## Description
Decode 4G/5G message stream, including access layer messages from terminals and base stations.

## Contact Information

If you have any cooperation needs or technical issues, please contact us via email: easy_codec@126.com


## Installation Tutorial

Currently, the tool only supports Windows systems.

Click on EasyCodec.msi to install directly.

## Instructions for use

It is a tool with encoding and decoding capabilities, covering multiple interface messages between base stations and terminals. It is also an encoding and decoding analysis tool, through which you can clearly understand the meaning represented by each bit of the bitstream.

## Operation effect

Let's take a look at the operation of this tool to give everyone a visual experience.

![asn1-tool](./README.assets/asn1-tool.gif)

## Protocol Support

The tool supports encoding and decoding of protocol messages such as 3GPP air port, F1AP, NGAP, E1AP, XNAP, etc.

## Easy to understand IE types

Each IE will have an icon that identifies the ANS.1 type of each IE. The specific meaning of the icon is as follows:



- <img src="./README.assets/409fe1822f988397af7ab5dc7d5968e0.png" alt="img" style="zoom:10%;" />  boolean type
- <img src="./README.assets/a90aa2e2155480eaaefbe0690b97d39c.png" alt="img" style="zoom:10%;" />  choice type
- <img src="./README.assets/afed5094d06a622acf3506300d46e022.png" alt="img" style="zoom:10%;" />  enumerated type
- <img src="./README.assets/d0b5c21daad948519e01d0bf16d4c6ce.png" alt="img" style="zoom:10%;" />  integer type
- <img src="./README.assets/3dba1f5a0d81ff09e4e6523d1c02a6ef.png" alt="img" style="zoom:10%;" />  numericString type
- <img src="./README.assets/37b4b2445a7f828575c654a36ad65433.png" alt="img" style="zoom:10%;" />  null type
- <img src="./README.assets/ffdf397e7ffe0726d8de78dd1a4c152c.png" alt="img" style="zoom:10%;" />  object identifier type
- <img src="./README.assets/77d42f482e89ff7d18fba958c76c177e.png" alt="img" style="zoom:10%;" />  octetstring type
- <img src="./README.assets/3b17e2557ed053cac8f212879cf4bf08.png" alt="img" style="zoom:10%;" />  open type
- <img src="./README.assets/b6225b228448493a28d92fd73dceb149.png" alt="img" style="zoom:10%;" />  printable string type
- <img src="./README.assets/89f3a8abe75f8858e969ee36469780ee.png" alt="img" style="zoom:10%;" />  real type
- <img src="./README.assets/21c281686934a4cb5eda6cdab7f13aab.png" alt="img" style="zoom:10%;" />  sequence type
- <img src="./README.assets/2d677a352bd806aa6fb2c1fba73536ce.png" alt="img" style="zoom:10%;" />  sequence of type
- <img src="./README.assets/af6622072671bc3946ce291db92e7e48.png" alt="img" style="zoom:10%;" />  set type
- <img src="./README.assets/d4b748547aaa23d453bccf3f7cafd840.png" alt="img" style="zoom:10%;" />  visible string type
- <img src="./README.assets/fc9c443f31bcdff5b5a34165f463e777.png" alt="img" style="zoom:10%;" />  bitstring type

## Convenient and fast input method

![image-20240127231145131](./README.en.assets/image-20240127231145131.png)

The second column of the element display area allows for different types of values to be entered, and the way numerical values are entered may vary depending on the type of ASN. 1.

Before entering, you need to select the corresponding IE row and then click on the corresponding IE row in the input area to input. Pressing the enter key or clicking the mouse on an area outside the "value input area" will take effect when entering the value.

## Powerful search function

![image-20240127231315562](./README.en.assets/image-20240127231315562.png)

Supports various search functions, and can automatically match and complete historical keywords when entering them. As follows:

<img src="./README.en.assets/image-20240127231357489.png" alt="image-20240127231357489" style="zoom: 25%;" />
