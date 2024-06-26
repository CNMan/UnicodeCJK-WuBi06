# 新世纪版五笔字型 Unicode CJK 超大字符集编码数据库

* 仅聚焦单字全码，不涉及简码、容错码和词组。

* 字形参考
  * [Unicode 15.1.0 CodeCharts](https://www.unicode.org/Public/15.1.0/charts/CodeCharts.pdf)
  * [GB 18030-2022 信息技术 中文编码字符集](https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=A1931A578FE14957104988029B0833D3)
  * [GB/T 36616.1-2018 信息技术 通用编码字符集（基本多文种平面） 汉字64点阵字型 第1部分：宋体](https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=B237C0E1B670D4116A4CD942FAFFD82F)
  * [GB/T 36616.2-2018 信息技术 通用编码字符集（基本多文种平面） 汉字64点阵字型 第2部分：黑体](https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=D04297F7BFEBD71FFE0149C48EE3BF5E)
  * [GB/T 36616.3-2018 信息技术 通用编码字符集（基本多文种平面） 汉字64点阵字型 第3部分：楷体](https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=1EA5D0FFC8E7E5362117A060B6BE8D65)
  * [GB/T 36616.4-2018 信息技术 通用编码字符集（基本多文种平面） 汉字64点阵字型 第4部分：仿宋体](https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=09D8B4FDABD348DE1809202A6A921C46)
  * 不一致的请反馈至[Unicode与国标字形不符字整理](https://github.com/CNMan/UnicodeCJK-WuBi06/issues/42)

* 字体使用
  * [方正字库](http://www.foundertype.com/)给[籍合网](http://www.ancientbooks.cn/)做的[中华书局宋体](http://www.ancientbooks.cn/helpcore?font)（支持Unicode 12.1.0）
    * [中华书局宋体错误（GB18030-2005字符部分）](https://github.com/CNMan/UnicodeCJK-WuBi06/issues/7)
    * [中华书局宋体错误（GB18030-2022新增字符部分）](https://github.com/CNMan/UnicodeCJK-WuBi06/issues/36)
  * [遍黑体](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic)

* 这是一个数据库，不是一个码表。

* 力求“标准”、“同形同码”

## [新世纪五笔字型资源库](https://06wb.github.io/)

## 交流群组

QQ群：38021162、857031696

[Telegram](https://telegram.org/) 群组 [@wbinput](https://t.me/wbinput)

## [如何参与项目](https://cnman.github.io/unicodecjk-wubi06.html)

## [关于项目进度](https://github.com/CNMan/UnicodeCJK-WuBi06/issues/4)

## [部分字根异写的处理](https://cnman.github.io/zigenyiti.html)

## G源以外其他地区字形编码

T源（中国台湾）、H源（中国香港）、M源（中国澳门）、J源（日本）、K源（韩国）、KP源（朝鲜）、V源（越南）、U源（Unicode委员会/美国等）等与G源（中国大陆/新加坡）字形不同的编码本人没时间整理，如有需求，请分别在[HK](https://github.com/CNMan/UnicodeCJK-WuBi06/tree/HK)、[MO](https://github.com/CNMan/UnicodeCJK-WuBi06/tree/MO)、[TW](https://github.com/CNMan/UnicodeCJK-WuBi06/tree/TW)等分支添加新世纪五笔编码。

## 反馈

如果你发现编码错误，请发[Issue](https://github.com/CNMan/UnicodeCJK-WuBi06/issues)、[Pull request](https://github.com/CNMan/UnicodeCJK-WuBi06/pulls)或发邮件到以下地址，以便及时修正

![myemail](https://github.com/CNMan/UnicodeCJK-WuBi06/raw/master/imgs/myemail.png)

## Unicode CJK 部分变动历史：

|版本|发布年月|CJK|CJK-A|CJK-B|CJK-C|CJK-D|CJK-E|CJK-F|CJK-G|CJK-H|CJK-I|CJK-CI|CJK-CIS|
|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|
|码位||4E00-9FFF|3400-4DBF|20000-2A6DF|2A700-2B73F|2B740-2B81F|2B820-2CEAF|2CEB0-2EBEF|30000-3134F|31350-323AF|2EBF0-2EE5F|F900-FAFF|2F800-2FA1F|
|码数||20,992|6,592|42,720|4,160|224|5,776|7,488|4,944|4,192|624|512|544|
|1.0.1|1992.06|20,902||||||||||302||
|3.0.0|1999.09||6,582|||||||||||
|3.1.0|2001.03|||42,711|||||||||542|
|3.2.0|2002.03|||||||||||361||
|4.1.0|2005.03|20,924||||||||||467||
|5.1.0|2008.04|20,932||||||||||||
|5.2.0|2009.10|20,940|||4,149|||||||470||
|6.0.0|2010.10|||||222||||||||
|6.1.0|2012.01|20,941||||||||||472||
|8.0.0|2015.06|20,950|||||5,762|||||||
|10.0.0|2017.06|20,971||||||7,473||||||
|11.0.0|2018.06|20,976||||||||||||
|13.0.0|2020.03|20,989|6,592|42,718|||||4,939|||||
|14.0.0|2021.09|20,992||42,720|4,153|||||||||
|15.0.0|2022.09||||4,154|||||4,192||||
|15.1.0|2023.09||||||||||622|||

GBK 基本相当于 Unicode 1.0.1；GB18030－2000 基本相当于 Unicode 3.0.0；GB18030－2005 基本相当于 Unicode 3.1.0；GB18030－2022 基本相当于 Unicode 11.0.0。

```
总码数：20,992+6,592+42,720+4,160+224+5,776+7,488+4,944+4,192+624+512+544=98,768
总字数：20,992+6,592+42,720+4,154+222+5,762+7,473+4,939+4,192+622+472+542=98,682
```

## 王码五笔字型输入法

[王码五笔字型大一统2018高级版](http://www.wangma.net.cn/prodetail.aspx?sm=2&p=7)仅售9.9元人民币，含86版、98版、新世纪版三个版本的五笔字型输入法，支持Windows XP/Vista/7/8/8.1/10 32/64位操作系统（不支持Metro App），可输入GB18030-2000标准的27533个汉字，**建议支持正版**。实在不想花钱的可以寻找曾经免费的[2012A](http://www.wangma.com.cn/view.asp?id=263&f_id=21)，亦可输入GB18030-2000标准的27533个汉字，但可能不支持最新的操作系统。

[五笔字型辅助教材](http://www.wangma.com.cn/wb2012/help/wmwb.chm)

文件SHA1：
```
63710F82C77BB328810EEA6E678ADB0836D1C41C *wmdyt18.exe
CE42B721FA3FCAD3881CAAF4882C267FF01C1A6A *wmwb2012a.exe v2.0.0.0
CE5A4007936D580000AAF433282D9D183EF87ADC *wmwb2012a.exe v2.0.0.1
```

安装后默认是86版，需要先将`编码方案`设置为“新世纪版五笔字形”、将`字符集`设置为“GB18030-2000(27533字)”、将`容错码`设置为“不允许”。

![dyt_settings01](https://github.com/CNMan/UnicodeCJK-WuBi06/raw/master/imgs/dyt_settings01.png)

![dyt00](https://github.com/CNMan/UnicodeCJK-WuBi06/raw/master/imgs/dyt00.png)

![dyt01](https://github.com/CNMan/UnicodeCJK-WuBi06/raw/master/imgs/dyt01.png) ![dyt02](https://github.com/CNMan/UnicodeCJK-WuBi06/raw/master/imgs/dyt02.png)

[新世纪版五笔字型字根键位图](http://www.wangma.com.cn/view.asp?id=201&f_id=22)

![zgjwt_jf_871x468](https://github.com/CNMan/UnicodeCJK-WuBi06/raw/master/imgs/zgjwt_jf_871x468.jpg)

[新世纪版五笔字型字根助记歌](http://www.wangma.com.cn/view.asp?id=200&f_id=22)

|1区横起笔|2区竖起笔|3区撇起笔|4区点起笔|5区折起笔|
|---|---|---|---|---|
|11 G 王旁青头五一提|21 H 目止具头卜虎皮|31 T 禾竹牛旁卧人立|41 Y 言文方点在四一|51 N 已类左框心尸羽|
|12 F 土士二干十寸雨|22 J 日曰两竖与虫依|32 R 白斤气头叉手提|42 U 立带两点病门里|52 B 子耳了也乃齿底|
|13 D 大三肆头古石厂|23 K 口中两川三个竖|33 E 月舟衣力豕豸臼|43 I 水边一族三点小|53 V 女刀九巡录无水|
|14 S 木丁西边要无女|24 L 田框四车甲单底|34 W 人八登祭风头几|44 O 火变三态广二米|54 C 又巴甬矣马失蹄|
|15 A 工戈草头右框七|25 M 山由贝骨下框里|35 Q 金夕犭儿包头鱼|45 P 之字宝盖补示衣|55 X 幺母绞丝弓三匕|

新世纪版五笔字型字根变动表

![zgbdb](https://github.com/CNMan/UnicodeCJK-WuBi06/raw/master/imgs/zgbdb.jpg)

新世纪版五笔字型字根总表及助记词

![zgzb](https://github.com/CNMan/UnicodeCJK-WuBi06/raw/master/imgs/zgzb.jpg)

汉字编码方法及流程

![bmff](https://github.com/CNMan/UnicodeCJK-WuBi06/raw/master/imgs/bmff.jpg)

## 参考资料

[Unihan Database Lookup](https://www.unicode.org/charts/unihan.html)

[ISO/IEC 10646 6th edition](https://standards.iso.org/ittf/PubliclyAvailableStandards/ISO_IEC_10646_2020_Amd_1_2023_ed_6-id_83362_Publication_PDF_(en).zip)

[IDS data for CJK Unified Ideographs](https://github.com/cjkvi/cjkvi-ids)

[国家语委语料库在线网站](http://corpus.zhonghuayuwen.org/)

[现代汉语通用字笔顺规范](http://www.moe.gov.cn/jyb_sjzl/ziliao/A19/201001/t20100115_75615.html)

[GB/T 18031-2016 信息技术 数字键盘汉字输入通用要求](http://www.gb688.cn/bzgk/gb/newGbInfo?hcno=3CA25D96795756C2B350B03478A7AB18)

[GB/T 19246-2003 信息技术 通用键盘汉字输入通用要求](http://www.gb688.cn/bzgk/gb/newGbInfo?hcno=8F7BD4C48AA924CC5CD260BB1E298E4F)

[GB/T 25741-2010 信息技术 汉字编码字符集 汉字部首序和笔顺序](http://www.gb688.cn/bzgk/gb/newGbInfo?hcno=DB34CB2C5C377E35E3766A543724B767)

[GF 0012-2009 GB13000.1字符集汉字部首归部规范](http://www.moe.gov.cn/jyb_sjzl/ziliao/A19/200901/t20090102_186104.html)

[GF 0014-2009 现代常用字部件及部件名称规范](http://www.moe.gov.cn/jyb_sjzl/ziliao/A19/201001/t20100115_75696.html)

[GF 0017-2013 识字教学用通用键盘汉字字形输入系统评测规则](http://www.moe.gov.cn/jyb_sjzl/ziliao/A19/201301/t20130101_185997.html)

[GF 0023-2020 通用规范汉字笔顺规范](http://www.moe.gov.cn/jyb_sjzl/ziliao/A19/202103/t20210318_520473.html)

[GF 2001-2001 GB13000.1字符集汉字折笔规范](http://www.moe.gov.cn/jyb_sjzl/ziliao/A19/201001/t20100115_75688.html)

[GF 3001-1997 信息处理用GB13000.1字符集汉字部件规范](http://www.moe.gov.cn/jyb_sjzl/ziliao/A19/201001/t20100115_75616.html)

[GF 3002-1999 GB13000.1字符集汉字笔顺规范](http://www.moe.gov.cn/jyb_sjzl/ziliao/A19/201001/t20100115_75619.html)

[GF 3003-1999 GB13000.1字符集汉字字序（笔画序）规范](http://www.moe.gov.cn/jyb_sjzl/ziliao/A19/201001/t20100115_75631.html)

[《通用规范汉字表》（国发〔2013〕23号）](http://www.gov.cn/zwgk/2013-08/19/content_2469793.htm)

[方正通用规范字库（个人版）V1.0](http://ifont.foundertype.com/index/generalfonts.html)

[计算机汉字键盘设计“三原理”——王永民](http://www.wangma.net.cn/UploadFiles/otherfile/a9add073cd9c4de59a7e891f5bc6b9ba.pdf)

[1994年央视五笔字型讲座视频（86版）（王永民）](http://www.wangma.net.cn/vido_main.aspx?sm=4)

[标准五笔字型教材（86版）（王永民）](http://www.wangma.net.cn/InfoMationDetail.aspx?sm=5&m=207)

[https://gitee.com/xionghuaidong/public](https://gitee.com/xionghuaidong/public)

[https://gitee.com/xionghuaidong/WubiTools](https://gitee.com/xionghuaidong/WubiTools)

[五笔爱好者论坛两周年精华](https://cnman.github.io/uploads/wbfans.com_2years.chm)

## 版权

所有权利归[王码公司](http://www.wangma.com.cn/)！请勿商用！

## 致谢

* 王码五笔发明人王永民

* [86版五笔字型超大字符集编码](https://pan.baidu.com/s/1hq5kedm) by [五笔吧](http://tieba.baidu.com/f?kw=五笔&ie=utf-8)小吧主[LSJ天道酬勤](http://tieba.baidu.com/home/main?un=LSJ天道酬勤&ie=utf-8)

* [98版五笔字型超大字符集编码](https://github.com/yanhuacuo/98wubi-unicode) by [98五笔吧](http://tieba.baidu.com/f?kw=98五笔&ie=utf-8)吧主[yanhuacuo](http://tieba.baidu.com/home/main?un=yanhuacuo&ie=utf-8)

* [新世纪五笔吧](http://tieba.baidu.com/f?kw=新世纪五笔&ie=utf-8)原吧主[xionghuaidong](http://tieba.baidu.com/home/main?un=xionghuaidong&ie=utf-8)

* 曾经为86版、98版五笔字型超大字符集编码作出贡献的“五笔爱好者论坛”网友
