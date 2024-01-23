+++
author = "TYH"
title = "TYHLearning——网站搭建学习"
date = "2023-12-21"
description = "TYHLearning系列"
categories = [
    "TYHLearning"
]
tags = [
    "TYHLearning","网站搭建学习"
]
+++

![ ](1.jpg)
[网站建设指南](https://www.runoob.com/web/web-buildingprimer.html, "菜鸟教程")

- [添加文件夹](#添加文件夹)
- [yaml 数据格式](#yaml-数据格式)

### 添加文件夹

第一点：在文件夹post添加新的文件夹，目前标题格式 -> 9-1-TYHLearning-网站布置学习像这样
第二点：添加如下内容（markdown 文件首部添加）

```markdown
    +++
    author = "TYH"
    title = "TYHLearning——MarkDown"
    date = "2023-12-21"
    description = "TYHLearning系列"
    categories = [
        "TYHLearning"
    ]
    tags = [
        "TYHLearning","MarkDown"
    ]
    +++
```

### yaml 数据格式

YAML（YAML Ain't Markup Language 或 YAML Ain't a Markup Language）是一种轻量级的数据序列化格式，通常用于配置文件和数据交换格式。它的设计目标是易读、易写，并且能够简洁地表达复杂的数据结构。

YAML 文件使用缩进和空格的结构表示层次关系，而不使用像 JSON 或 XML 那样的符号。它以易读的方式描述数据，并强调数据的表达清晰度。以下是一个简单的 YAML 文件的例子：

```ymal
name: John Doe
age: 30
city: New York
interests:
  - Reading
  - Hiking
  - Photography

```

在这个例子中，name、age、city 和 interests 是键，它们分别对应着相应的值。interests 的值是一个包含三个元素的列表。YAML 使用缩进来表示层次关系，而不是像 JSON 使用花括号或数组标记。

YAML 通常用于配置文件，例如在软件项目中的配置文件（如 .yaml 或 .yml 文件），以及一些系统和工具中的配置文件（如 Kubernetes 配置文件）。

总体而言，YAML 提供了一种人类友好、可读性强的数据格式，适用于许多场景，尤其是配置文件和数据序列化。
