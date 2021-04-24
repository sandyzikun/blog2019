---
title: 《Hello World》
date: 2019-05-12 12:40:00
categories:
- VOCALOID&UTAU&SynthV相关
tags:
- VOCALOID曲推
---

> 徵羽摩柯，如约苏醒。

好了我们今天要介绍的曲子是——

# 你好，世界

* VC本家：[av28384607](http://www.bilibili.com/video/av28384607/)

## Staff名单
* Vocal: 徵羽摩柯
* Music: 正弦函数P(@正弦P)
* Lyrics: @鸣泣的紫蝶
* 调教: OQQ(@OQQ君)
* 曲绘: @偶尤大肥羊
* PV: @hisa镜

## 简介

1. 《你好，世界！》是正弦函数P作编曲、OQQ调教并于2018年8月3日投稿至Bilibili的Vocaloid中文原创歌曲，由徵羽摩柯演唱，为摩柯印象曲系列第一作。本曲是徵羽摩柯第一首殿堂曲，殿堂用时1日9时19分，截至现在已有55.33万次观看，5.20万人收藏。

2. 本曲主要讲述了作为技术宅与键盘手的摩柯眼中的世界与自我。动感而迷幻的旋律、科幻风的PV展现了本曲独特的程序代码主题，歌词细节则处处映照着摩柯的人设。

3. 标题是个程序员都懂。

## PV以及简介中出现的两处代码(貌似都是C/C++)

1. 简介中出现的介绍Staff全体的代码
   ```cpp
   #include <iostream>
   using namespace std;
   int main()
   {   /*徵羽摩柯，如约苏醒。*/
       cout << "*****Hello World!!*****" << endl
       << "曲名:你好，世界！" << endl
       << "作曲:正弦函数p" << endl
       << "作词:鸣泣的紫蝶" << endl
       << "曲绘:偶尤大肥羊" << endl
       << "PV:hisa镜" << endl
       << "调校/策划:OQQ君" << endl
       << "演唱:徵羽摩柯" << endl
       << "徵羽摩柯中之人:苏尚卿(西呱双)" << endl;
       return 0;
   }
   ```

2. PV中出现的用于打印钻石形状字符的代码
   ```cpp
   #include <iostream>
   using namespace std;
   /*
   This is my first c++ program.
   Auther:ZhiyuMoke
   Date:2018.5.30
   */
   void PrintDiamond(int n)
   {
       int i, j;
       for(i = 0; i < n; i++)
       {
           for(j = 0; j <= n - i; j++)
               cout << " ";
           for(j = 0; j < (2 * i - 1); j++)
               cout << "*";
           cout << endl;
       }
       for(i = 0; i < n; i++)
       {
           for(j = 0; j <= i; j++)
               cout << " ";
           for(j = 0; j < (2 * (n - i) - 1); j++)
               cout << "*";
           cout << endl;
       }
   }
   int main()
   {
       PrintDiamond(4);
       cout << "Hello World!!";
       PrintDiamond(4);
       return 0;
   }
   ```
   这个运行起来差不多是长这样的:
           *
          ***
         *****
        *******
         *****
          ***
           *
       Hello World!!
           *
          ***
         *****
        *******
         *****
          ***
           *

(内容参考：

* https://zh.moegirl.org/你好，世界!

* https://music.163.com/#/song?id=1300936430

* https://www.bilibili.com/video/av28384607/

更多信息欢迎大家补充)
