一些用到的LaTeX杂碎记录


**文件定义**

\documentclass[12pt]{article}

[]内可设置文字字号，{}内设置文件类型，常用有article，book等。其中article为单页，不可使用\cleardoublepage双页留白，除非在[]内添加twoside定义


如使用中文，可用ctexart定义

\documentclass[utf8]{ctexart}

需要更改编译器为XeLaTeX
