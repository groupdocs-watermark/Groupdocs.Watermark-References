---
title: "ImageDctHashSearchCriteria 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示在文档中查找图像的搜索条件。"
type: docs
url: /zh/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/
is_root: false
weight: 40
---


## ImageDctHashSearchCriteria class

表示在文档中查找图像的搜索条件。

此搜索条件使用基于 DCT 的感知图像哈希来计算图像相似度。了解更多：https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

ImageDctHashSearchCriteria 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/#file_path) | 使用指定的文件路径初始化 ImageDctHashSearchCriteria 实例。 |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/#stream) | 使用提供的图像流初始化 ImageDctHashSearchCriteria 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | 使用逻辑 AND 运算符将此 SearchCriteria 与其他条件组合。（继承自 [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)） |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | （继承自 [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)） |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | 对该 SearchCriteria 取反。（继承自 [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)） |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | 使用逻辑 OR 运算符将此 SearchCriteria 与其他条件组合。（继承自 [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)） |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | （继承自 [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)） |

### 属性
| 属性 | 描述 |
| :- | :- |
| [max_difference](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/max_difference/) | 图像之间允许的最大差异。（继承自 [`ImageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/)） |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | 特定页码的列表。（继承自 [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/)） |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def clear_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")
```

### Guides
使用 `ImageDctHashSearchCriteria` 的任务指南：

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)

### 另请参见
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
