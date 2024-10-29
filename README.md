一些用到的LaTeX杂碎记录



**文件定义**

\documentclass[12pt]{article}

[]内可设置文字字号，{}内设置文件类型，常用有article，book等。其中article为单页，不可使用\cleardoublepage双页留白，除非在[]内添加twoside定义


如使用中文，可用ctexart定义

\documentclass[utf8]{ctexart}

需要更改编译器为XeLaTeX


更详细内容请参考 [wikibooks,LaTeX/Document Structure](https://en.wikibooks.org/wiki/LaTeX/Document_Structure)



**页面调整**

\usepackage{geometry}

\geometry{a4paper, margin=0.7in}

{}内可设置纸张样式，和页边距

margin是全部页边距，也可使用left=2cm,right=2.5cm,top=2cm,bottom=2.5cm类似格式进行单独定义
