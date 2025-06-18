你不知道的Python
================================================================================

我将Python使用过程中踩过的坑编进行记录。
本书假设您有一定的Python编程经验。

### 如何编译:

##### 环境需求

- 安装最新的texlive，安装步骤参考[清华大学开源镜像站CTAN页面](https://mirrors.tuna.tsinghua.edu.cn/help/CTAN/)。
- 需要有Python3，并安装Pygments：`pip install pygments`，它用于提供代码块高亮。

#### 编译

按下面命令操作即可。
```shell
cd src
xelatex ThePythonYouDontKnow.tex
```

---

### _deprecated

之前用Markdown记录的过的一些Python笔记。
有些还是能直接抄来用的，比如常量类、单例类。

「类型注解」私以为写得不错。
「元类」私以为写得不错。

---

2025：读过一些CPython源代码后，有些优化技巧已经不需要记了，
或都说当时的文档变得笨拙，后续重写相关内容。
