# lib-gedit-latex-icons
Library for gedit-latex-ICONS

## 概要
- LINUX 用エディタ **gedit** のプラグインである **gedit-latex** に付属している ICON を使用する為のライブラリです。  

## 注意点
- このライブラリは **GNU/Linux Debian** 環境を想定しています。  
他のデストリビューションでは、システム上の **ICONS フォルダ**の位置が異なる場合がありますので、確認後 PATH を修正して下さい。 
- ICON 自体は PNG ですので過度の拡大は**像が粗く**なります。  

## 使用方法
  - 詳細は
  [GEDIT-LaTeX-Plugin ICONS for LaTeX](https://github.com/ru-museum/lib-gedit-latex-icons/blob/main/gedit-latex-icons.pdf)（gedit-latex-icons.pdf）をご覧下さい。 
  
1. ライブラリ **lib-gedit-latex-icons.sty** の読込：

```
\usepackage{lib-gedit-latex-icons} 
\usepackage{graphicx} % PNG 用(必須) 
\usepackage{svg}      % SVG を使用の場合 
```
2. 表示：基本的に prefix として先頭に **gl** を付与します。   
```
\glabort
```
