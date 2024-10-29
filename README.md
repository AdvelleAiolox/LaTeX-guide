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


更详细内容请参考 [The geometry package](https://texdoc.org/serve/geometry.pdf/0)



**行间距调整**

\usepackage{setspace}

\renewcommand{\baselinestretch}{1.2}

{}内数字表示行间距，LaTeX默认为1.2

如果需要和word配合使用需注意，一般认为word中1.2倍行间距约等于LaTeX中1.3倍行间距，但具体情况必须依据word中使用字体来确定，因为word中行间距与字体本身关系很大


