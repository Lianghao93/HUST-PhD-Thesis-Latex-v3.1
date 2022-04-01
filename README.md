# 华中科技大学学位论文Latex模板说明

    该模板为华中科技大学硕士/博士学位论文Latex模板
    根据华中科技大学研究生院发布的最新学位论文模板，在原版本的基础上进行了更新
    当前版本由人工智能与自动化学院生物计算团队更新管理
    可能存在诸多错误与问题，请提出宝贵意见
    欢迎大家进群分享使用经验（QQ群：782574845）。
    
**********************************************************************
安装配置环境

    Windows、MacOS推荐安装TeXstudio，并更新宏包。
    不喜欢折腾的，可以注册使用Overleaf在线编辑。

使用说明

    \body     	论文内容撰写存档
    \figures    	论文图片统一存档
    \ref      	 	参考文献整合存档 
    main.tex   	论文整体章节编辑

更新作者

    Lianghao Li (李良昊)，Jianqing Lin (林剑清) 
            ——人工智能与自动化学院生物计算团队

QQ交流群

    华中大学位论文Latex群（群号：782574845）

**********************************************************************

# HUST-PhD-Thesis-Latex

HUSTThesis.cls 2022/03/30 version V3.1

This is the unofficial LaTeX class for Master/Ph.D. Thesis Template of Huazhong University of Science and Technology


Contributors: Lianghao Li (2021 V3.1), Xinze Zhang (2020 V3.0), Huikan Liu (2006 V2.0), and Feng Jiang (2005 V1.0). 

Copyright (C) 2020-2021 by Xinze Zhang <xinze@hust.edu.cn>

Copyright (C) 2006-2007 by Huikan Liu <hkliu@mail.edu.cn>

This code is distributed under the Perl Artistic License
( http://language.perl.com/misc/Artistic.html )
and may be freely used, distributed and modified.
Retain the contribution notices and credits.

Current maintainer:    lianghao93@vip.qq.com;
                       linjqcn@gmail.com


**********************************************************************

Available class options
(e.g., \documentclass[draftformat,mathCMR]{HUSTthesis}

            *** choose only one from each category ***

draftformat, finalformat

    提交草稿打开 draftformat 选项，提交盲审版打开 finalformat 选项。
    草稿正文页包括页眉（“华中科技大学博士学位论文”），页眉修饰线（双线）。
    页脚（页码），页脚修饰线（单线）。
    盲审版正文页不包括页眉、页眉修饰线和页脚修饰线，仅包含页脚。
    
mathtimes, mathCMR

    公式字体选项，mathtimes 选项让公式启用 Times Roman 字体，
    mathCMR 选项让公式启用 CM Roman 字体。
    目前学校尚未规定公式选用什么字体，推荐使用 CM Roman 字体，
    因为 Times Roman 数学字体不支持黑体。
    如果使用 Times Roman 字体，需加载 bm 宏包用于支持黑体（不推荐）。

*******
09/2021 V3.1 changes:

modify class file (HUSTthesis.cls):

    1. update the defence committee page between Chinese and English cover

    2. update the indentation and spacing of the itemize, enumerate and description

    3. update the reference list according to the latest standard

    4. update the appendixs according to the latest standard
    
    5. Change the line spacing to match the Word template
    
    6. Added bold fonts to some fonts (Heiti & Kaiti)

    7. Changed the font, font size, line spacing and indentation of the table of contents page to match the Word template

    8. Updated header and footer
    
 by Li Lianghao (lianghao1993@hust.edu.cn; lianghao93@vip.qq.com)
    Lin Jianqing (linjqcn@gmail.com)

*******
11/2020 V3.0 changes:
1. modify class file (HUSTthesis.cls):

    1.1 update the location of 学号(xuehao) of covering page

    1.2 update the table length of the emajor

    1.3 update the font specification with using the font locally, enabling this project be compiled on overleaf

    1.4 remove the font command of lishu and youyuan

2. change the folder name of ./data/* to ./body/* and update the information of xinze zhang

 by Zhang Xinze (xinze@hust.edu.cn)
 
 *******

 06/2006 V2.0 changes:

 1. wrote class file (HUSTthesis.cls) based on ThuThesis.cls written by
    Xue Ruini, the class file is designed for Doctoral Thesis of HUST.

 2. define new Itemize, Enumerate and Description environments with compact spacing

 by Liu Huikan (hkliu@mail.edu.cn)

*******

 04/2004 V1.0 released (Feng Jiang)


 by Feng Jiang (fjiang@people.com.cn)
