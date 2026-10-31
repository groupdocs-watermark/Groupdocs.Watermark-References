---
title: "HyperlinkPossibleWatermark 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示 PowerPoint 内容中可能的超链接水印。"
type: docs
url: /zh/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/
is_root: false
weight: 60
---


## HyperlinkPossibleWatermark class

表示 PowerPoint 内容中可能的超链接水印。

HyperlinkPossibleWatermark 类型公开以下成员：

### 属性
| 属性 | 描述 |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/height/) | 此 HyperlinkPossibleWatermark 的高度。 |
| [parent](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/parent/) | 此 HyperlinkPossibleWatermark 的父对象。 |
| [rotate_angle](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/rotate_angle/) | 此 HyperlinkPossibleWatermark 的旋转角度（以度为单位）。 |
| [text](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/text/) | 此 HyperlinkPossibleWatermark 的 URL。 |
| [unit_of_measurement](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/unit_of_measurement/) | 此 [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/) 的计量单位。 |
| [width](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/width/) | 此 HyperlinkPossibleWatermark 的宽度。 |
| [x](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/x/) | 此 HyperlinkPossibleWatermark 的 x 坐标。 |
| [y](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/y/) | 此 [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/) 的 y 坐标。 |
| [formatted_text_fragments](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/formatted_text_fragments/) | 此 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) 的格式化文本片段集合。（继承自 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)） |
| [image_data](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/image_data/) | 此 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) 的图像；如果水印没有图像则为 None。（继承自 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)） |
| [page_number](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/page_number/) | 放置水印的页码。（继承自 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)） |

### 示例

```python
import re
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search import HyperlinkPossibleWatermark
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria(re.compile(r"someurl\.com")))
    for i in range(len(possible) - 1, -1, -1):
        if isinstance(possible[i], HyperlinkPossibleWatermark):
            print(possible[i].text)
            watermarker.remove(possible[i])
    watermarker.save("./output.pdf")
```

### 另请参见
* module [`groupdocs.watermark.search`](/watermark/python-net/groupdocs.watermark.search/)
