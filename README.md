#### 内容在 pdf 文件夹里，源码在 src 文件夹里

文件结构：


```
- pdf/
    - main.pdf
- src/
   |- main.tex
    - sections/
       |- section1.tex
       |- section2.tex
       |- section3.tex
       |- section4.tex
       |- section5.tex
        - section6.tex
```


每个 section*.tex 里

```tex
\unsolve
```

代表没有解决，可以用

```tex
\ans[
    %content
]
```

替换掉以补充回答。

