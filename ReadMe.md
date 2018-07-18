# Unicode 新世纪版五笔字型编码（未完成）

本项目**拟**将[五笔吧](http://tieba.baidu.com/f?kw=五笔&ie=utf-8)小吧主[LSJ天道酬勤](http://tieba.baidu.com/home/main?un=LSJ天道酬勤&ie=utf-8)制作的[海峰五笔码表 2.02A（2017年4月23日校对）](https://pan.baidu.com/s/1hq5kedm)逐字转换为新世纪版五笔字型码表。

* 仅聚焦单字，不涉及词组。

* 字形以Windows 10中的SimSun（CJK、CJK-A）、SimSun-ExtB（CJK-B、CJK-C、CJK-D和少量CJK-E）以及[方正字库](http://www.foundertype.com/)给[籍合网](http://www.ancientbooks.cn/)做的[中华书局宋体](http://www.ancientbooks.cn/helpcore?font)（支持Unicode 10.0.0）为准。

## 文本编辑器

推荐使用[BabelPad](http://www.babelstone.co.uk/Software/Download/BabelPad_CHS.zip)，可对Unicode编码区分别设置不同字体。

## Unicode CJK 部分变动历史：

|版本|CJK|CJK-A|CJK-B|CJK-C|CJK-D|CJK-E|CJK-F|
|-------|-------|-------|-------|-------|-------|-------|-------|
|码位|4E00-9FFF|3400-4DBF|20000-2A6DF|2A700-2B73F|2B740-2B81F|2B820-2CEAF|2CEB0-2EBEF|
|码数|20,992|6,592|42,720|4,160|224|5,776|7,488|
|1.0.1|20,902|||||||
|3.0.0||6,582||||||
|3.1.0|||42,711|||||
|4.1.0|20,924|||||||
|5.1.0|20,932|||||||
|5.2.0|20,940|||4,149||||
|6.0.0|||||222|||
|6.1.0|20,941|||||||
|8.0.0|20,950|||||5,762||
|10.0.0|20,971||||||7,473|
|11.0.0|20,976|||||||

GBK 基本相当于 Unicode 1.0.1；GB18030－2000 基本相当于 Unicode 3.0.0；GB18030－2005 基本相当于 Unicode 3.1.0

## 王码五笔字形输入法

[王码五笔字型大一统2018高级版](http://www.wangma.net.cn/prodetail.aspx?sm=2&p=7)仅售28元人民币，含86版、98版、新世纪版三个版本的五笔字型输入法，支持Windows XP/Vista/7/8/8.1/10 32/64位操作系统（不支持Metro App），可输入GB18030-2000标准的27533个汉字，**建议支持正版**。实在不想花钱的可以寻找曾经免费的[2012A](http://www.wangma.com.cn/view.asp?id=263&f_id=21)，亦可输入GB18030-2000标准的27533个汉字，但可能不支持最新的操作系统。

文件SHA1：
```
63710F82C77BB328810EEA6E678ADB0836D1C41C *wmdyt18.exe
CE42B721FA3FCAD3881CAAF4882C267FF01C1A6A *wmwb2012a.exe v2.0.0.0
CE5A4007936D580000AAF433282D9D183EF87ADC *wmwb2012a.exe v2.0.0.1
```

安装后默认是86版，需要先将`编码方案`设置为“新世纪版五笔字形”、将`字符集`设置为“GB18030-2000(27533字)”、将`容错码`设置为“不允许”。

![dyt_settings01](https://github.com/CNMan/Unicode_CJK_XSJWBBM/raw/master/imgs/dyt_settings01.png)

[新世纪版五笔字型字根助记歌](http://www.wangma.com.cn/view.asp?id=200&f_id=22)

[新世纪版五笔字型字根键位图](http://www.wangma.com.cn/view.asp?id=201&f_id=22)

[五笔字型辅助教材](http://www.wangma.com.cn/wb2012/help/wmwb.chm)

## 参考资料

[Unicode 11.0.0 CodeCharts](https://www.unicode.org/Public/11.0.0/charts/CodeCharts.pdf)

[Unihan Database Lookup](https://www.unicode.org/charts/unihan.html)

[《通用规范汉字表》（国发〔2013〕23号）](http://www.gov.cn/gzdt/att/att/site1/20130819/tygfhzb.pdf)

[《现代常用字部件及部件名称规范》（GF 0014-2009）](http://www.moe.edu.cn/ewebeditor/uploadfile/2015/01/13/20150113090318445.pdf)

[《信息处理用GB13000.1字符集汉字部件规范》（GF 3001-1997）](http://www.moe.gov.cn/ewebeditor/uploadfile/2015/01/12/20150112165337190.pdf)

[《现代汉语通用字笔顺规范》（国家语言文字工作委员会标准化工作委员会 编）](https://github.com/Haixing-Hu/typesetting-standard/raw/master/数字文字/现代汉语通用字笔顺规范（1997年版）.pdf)

[国家语委语料库在线网站](http://corpus.zhonghuayuwen.org/)

[方正通用规范字库（个人版）V1.0](http://ifont.foundertype.com/index/generalfonts.html)
