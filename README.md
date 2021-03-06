# wubi86-super
一款适用于 RIME 的「王码五笔字型 86 版」单字输入方案，支持 Unicode 14.0 范围内 CJK 基本汉字区域至汉字扩展 G 区域超大字符集，可用于输入基本区和扩展区 A~G 的生僻字。
![image](https://user-images.githubusercontent.com/51902309/166140198-a42ea4e5-ab55-40b5-a2c7-89c115e0e9a6.png)

码表基于 [CNMan/UnicodeCJK-WuBi](https://github.com/CNMan/UnicodeCJK-WuBi) 整理，并由 [RIME 方案仓库「五笔 86」方案](https://github.com/rime/rime-wubi) 提取一、二、三键简码。

> **86 五笔编码数据来源：**
> - 一级、二级、三级简码 by [RIME 方案仓库「五笔 86」方案](https://github.com/rime/rime-wubi) | [东风破 plum](https://github.com/rime/plum)
> - [CJK-Basic/CJK-A/CJK-B/CJK-C/CJK-D/CJK-E](https://pan.baidu.com/s/1hq5kedm) by [五笔吧](http://tieba.baidu.com/f?kw=五笔&ie=utf-8)小吧主[LSJ天道酬勤](http://tieba.baidu.com/home/main?un=LSJ天道酬勤&ie=utf-8)
> - CJK-F by ☂¹₄²₈⁵₇☂
> - CJK-G by [CPC中文印刷社区](http://www.cnprint.org/)网友[dingsir](http://www.cnprint.org/bbs/members/697305/)

下图为 Unicode 14.0 新增汉字的编码。

![](https://s3.bmp.ovh/imgs/2022/04/23/b40b96b787de95b0.png)

> **注：** 
> 1. 由于在五笔 86 中，「𫜵」`U+2B735` 为「貌」`eerq`「霾」`feef` 等字所含的字根之一，故按照字根字的编码规则，编码为 `etyt`。
> 2. 本方案中，繁体部首「飠」在组字时编码为 `wp`，如「飯」字的编码为 `wprc`。单独输入「飠」偏旁时编码为 `wyvy`。此外有部分「飠」部字前三码为 `wgv`，与该字在 Unicode 提交的源字形有关。
> 3. 本方案中，基本区及扩展 B-E 区简体部首「麦」的编码为 `gt`，如「麸」的编码为 `gtfw`，非 `gqfw`。扩展 G 区「麦」部的编码可能为 `gq`。
> 4. 扩展汉字区域可能混有 98 版编码，请在使用时留意。
