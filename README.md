# 中华人民共和国宪法 Constitution of the People's Republic of China

> This repository contains the revision history of the Chinese consititution since its first release in 1954. Its content is contained in the Markdown file [Constitution.md](https://github.com/tianyikillua/chinese-constitution/blob/master/Constitution.md) with each revision represented by a `commit` through the `git` version control system. This project is inspired from the [Archeo-Lex](https://github.com/Legilibre/Archeo-Lex) project as well as my personal participation in recording the revision history of the [French immigration law](https://github.com/tianyikillua/ceseda) via `git`.

一个法律法典的修订平行于一个软件源代码的版本更新：

1. 一个固定时间对应一个他们的有效版本；
2. 对一个旧版本的修改增添一个新的版本。

详见这篇[博文](http://www.litianyi.me/2017/01/01/lois-github/)和我曾参与的开源项目 [Archeo-Lex](https://github.com/Legilibre/Archeo-Lex) 以及[法国外国人法典](https://github.com/tianyikillua/ceseda)。运用这个类比，可以运用软件工程中的版本管理系统（比如 `git`）进行法律法典修订历史的可视化，运用 `diff` 更好地展现出每次改动。

本库将这套类比运用在[中华人民共和国宪法](https://zh.wikipedia.org/zh-hans/中华人民共和国宪法)上。宪法内容记录在一个 Markdown 文件 [Constitution.md](https://github.com/tianyikillua/chinese-constitution/blob/master/Constitution.md) 中，每次修改表示为一个对其的 `commit`，可通过 `diff` 更好地了解改动。完整修订历史可以在 [Commits](https://github.com/tianyikillua/chinese-constitution/commits) 页面看到。四个版本的宪法（54、75、78和82）以及现行宪法（经过 2004 年的修宪）用 `tags` 表示。

1. 1954年09月20日第一届全国人民代表大会第一次会议通过了新中国第一本宪法；
2. 1975年01月17日第四届全国人民代表大会第一次会议与1978年03月05日第五届全国人民代表大会第一次会议对五四宪法进行大修；考虑到其规模之大，这里将它们考虑为两个从五四宪法导出的两个独立的版本分支 `branch`；
3. 1982年12月04日第五届全国人民代表大会第五次会议重新基于五四宪法进行修宪，为中国现行宪法的基础（八二宪法）；
4. 1988年04月12日第七届全国人民代表大会第一次会议直至2018年03月11日第十三届全国人民代表大会第一次会议对八二宪法进行了些“小”修订。

由 `git` 系统自动生成的修宪历史可以总结于下图。

```
* 2018年03月11日第十三届全国人民代表大会第一次会议通过 (tag: 现行宪法)
* 2004年03月14日第十届全国人民代表大会第二次会议通过
* 1999年03月15日第九届全国人民代表大会第二次会议通过
* 1993年03月29日第八届全国人民代表大会第一次会议通过
* 1988年04月12日第七届全国人民代表大会第一次会议通过
* 1982年12月04日第五届全国人民代表大会第五次会议通过 (tag: 1982宪法)
|
|  * 1978年03月05日第五届全国人民代表大会第一次会议通过 (tag: 1978宪法)
| /
|/ 
|  * 1975年01月17日第四届全国人民代表大会第一次会议通过 (tag: 1975宪法)
| /
|/  
* 1954年09月20日第一届全国人民代表大会第一次会议通过 (tag: 1954宪法)
```