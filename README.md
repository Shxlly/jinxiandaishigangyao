#### 内容在 pdf 文件夹里，源码在 src 文件夹里。

# FAQ

* 文件结构和作用是怎样的？
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



* 这个文档有什么不完善的地方？
  还有没有完成的题目，在每个 ```section*.tex``` 里 用空回答或```\unsolve``` 代表问题还没有解决。



* 如何帮忙 填写/编辑 答案？
##### 方法一（推荐不熟悉的朋友们）：
在GitHub ```Issues``` 里面点击 ```New issue``` 来详细描述。

##### 方法二：
可以用```\ans[\content]``` 替换 tex 文件中的 ```\unsolve```以 填写/编辑 答案。然后在 GitHub 上 ```pull request```。