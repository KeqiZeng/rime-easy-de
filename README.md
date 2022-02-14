# 基于Rime的简单的德语输入法

## Why

1.  记不住德语键盘布局的标点位置。
2.  Mac上鼠须管和德语键盘切换时，鼠须管的`y`键和`z`键会交换位置。

## Feature

1.  单个`.schema.yaml`文件，没有其他依赖。
2.  传统的美式键盘布局，可用`/a, /v, /c, /A, /V, /C, /s`分别输入`ä, ü, ö, Ä, Ü, Ö, ß`(可自行在symbols中更改快捷键)。
3.  英文标点，引号为德语引号，即`„“`。
4.  键盘上26个字母的大小写直接上屏。在允许输入德语特殊字符的前提下还原ascii\_mode的体验。

## Getting Start

把`easy_de.schema.yaml`文件放入Rime的用户目录下，在`default.custom.yaml`文件中的`schema_list`下添加`- schema: easy_de`，重新部署即可。

## Thanks

该输入方案的名称来源于[easy\_en](https://github.com/BlindingDark/rime-easy-en), 感谢！

感谢[Rime社区](https://github.com/rime/home)在我折腾Rime的这些天里提供的解惑！

屏幕前的你！
