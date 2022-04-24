# wubi86-super
一款基于 RIME 的「五笔字型 86 版」方案，支持 Unicode 14.0 范围内 CJK 基本汉字区域至汉字扩展 G 区域超大字符集。

码表基于 [CNMan/UnicodeCJK-WuBi](https://github.com/CNMan/UnicodeCJK-WuBi) 整理，并由 [RIME 官方「五笔 86」仓库](https://github.com/rime/rime-wubi) 提取一、二、三键简码。

![](https://s3.bmp.ovh/imgs/2022/04/23/b40b96b787de95b0.png)
> **注：** 
> 1. 由于在五笔 86 中，「𫜵」`U+2B735` 为「豸」`eer`「貌」`eerq` 等字的第一个字根，故按照字根字的编码规则，编码为 `etyt`。
> 2. 本方案中，繁体部首「飠」在组字时编码为 `wp`，如「飯」字的编码为 `wprc`。单独输入「飠」偏旁时编码为 `wyvy`。此外有部分「飠」部字前三码为 `wgv`，与该字在 Unicode 提交的源字形有关。
> 3. 本方案中，基本区及扩展 B-C 区简体部首「麦」的编码为 `gt`，如「麸」的编码为 `gtfw`，非 `gqfw`。
