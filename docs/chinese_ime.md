# 如何加入中文输入法

在示例项目中，没有加入输入法，主要是开发板的flash不够。如果flash够大(不小于4M时)，可以自行加入：

* 加入3rd/gpinyin/src中的代码。
* 加入src/input\_engines/input\_engine\_pinyin.cpp。
* 去掉src/input\_engines/input\_engine\_null.cpp。
* include路径加入3rd/gpinyin/include。