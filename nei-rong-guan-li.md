# 中级

## gitbook的基本规则
 
Gitbook需要2个基本文件：

* README.md
* UMMARY.md

README.md是关于你的书的介绍，而SUMMARY.md中则包含了书目，即章节结构，它的格式大致是：
```
* [第1章](c1.md)
 * [第1节](c1s1.md)
 * [第2节](c1s2.md)
* [第2章](c2.md)
```


## 内容托管
在gitbook建立的项目，默认是会放在git.gitbook.com
```
https://git.gitbook.com/用户id/项目名.git
```

你也可以把文档写好以后先push到github上，内容调整好了以后。
gitbook官网有工具 [Improved GitHub integration](https://www.gitbook.com/blog/releases/github-integration)

![](/assets/60F15816-543D-497C-923E-643779FCE01A.png)

![](/assets/02F65F9C-010D-4856-955D-2415176DE407.png)

可以把github的项目直接导入到gitbook里


### 建议
gitbook的网速还是偏慢，还是建议托管在github上
