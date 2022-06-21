## Course Parser是做什么的
通过处理SIS中 My Course History 页面复制来的字符串以及修读计划中有关的字符串，快速将课程按照 School Package, ME, MR 排列。
```
School Package
-  -------  -
1  BIO1001  √
2  CHM1001  √
3  CSC1001  √
4  CSC1002  √
5  MAT1001  √
6  MAT1002  √
7  MAT2040  √
8  PHY1001  √
9  STA2001  √
-  -------  -
9/9 course(s), obtained 25.0 unit(s)

Major Required
--  -------  -
 1  CSC3001  √
 2  CSC3002  √
 3  CSC3050  √
 4  CSC3100  √
 5  CSC3150  √
 6  CSC3170  √
 7  CSC4001  √
 8  CSC4005
 9  EIE2050  √
10  PHY1002  √
--  -------  -
9/10 course(s), obtained 26.0 unit(s)

Major elective
-  -------
1  CSC3180
2  CSC4008
3  CSC4160
4  ECO2011
5  MAT3007
-  -------
5 course(s), obtained 15.0 unit(s)

Others
--  --------
 1  CHI1000
 2  ENG1001
 3  ENG1002
 4  ENG2001
 5  ENG2002S
 6  GEB2312
 7  GEC3403
 8  GFH1000
 9  GFN1000
10  ITE1000
11  PED1001
12  PED1002
--  --------
12 course(s), obtained 30.0 unit(s)

Total units: 96.0
```

## 怎么用呢  
打开SIS找到下图的 My Course History  
![image](https://user-images.githubusercontent.com/76863396/174778619-b7fc70f0-e7d5-4cc6-b32f-ee113cb99d5e.png)  
从表格第一行正文（如下图）起，复制表格的所有内容直到最后一行的 Status Icon  
![image](https://user-images.githubusercontent.com/76863396/174778935-406b5fe3-8ba8-4fed-8645-a1c446f9a04e.png)
将复制粘贴的内容填入第一个文本框
  
打开修读计划，从 Course List 的标题开始复制表格内容（如下图），直到 ME 部分的结束，若有多个 Stream 只可复制一个 Stream 的
![image](https://user-images.githubusercontent.com/76863396/174779426-3b73bb31-89ef-4867-916e-f8ca7e375bac.png)



