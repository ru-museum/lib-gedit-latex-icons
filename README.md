# lib-gedit-latex-icons
gedit-latex 付属 ICON 用ライブラリ

## 概要
- LINUX 用エディタ **gedit** のプラグインである **gedit-latex** に付属している ICON を使用する為のライブラリです。  

## 注意点
- ICON 自体は PNG ですので過度の拡大は**像が粗く**なります。  

## 使用方法
  
1. ライブラリ **lib-gedit-latex-icons.sty** の読込：

```
\usepackage{lib-gedit-latex-icons} 
\usepackage{graphicx} % PNG 用(必須) 
\usepackage{svg}      % SVG を使用の場合 
```
2. 表示：基本的に prefix として戦闘に **gl** を付与します。   
```
\glabort
```
