---
title: "AddWatermarkResult 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示向文档添加水印的结果。"
type: docs
url: /zh/python-net/groupdocs.watermark.watermarks.results/addwatermarkresult/
is_root: false
weight: 10
---


## AddWatermarkResult class

表示向文档添加水印的结果。

AddWatermarkResult 类型公开以下成员：

### 属性
| 属性 | 描述 |
| :- | :- |
| [number_applied_watermarks](/watermark/python-net/groupdocs.watermark.watermarks.results/addwatermarkresult/number_applied_watermarks/) | 已应用水印的数量。 |
| [succeeded](/watermark/python-net/groupdocs.watermark.watermarks.results/addwatermarkresult/succeeded/) | 新创建的水印列表。 |

### 示例

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww

with gw.Watermarker("sample_2_pages.pdf") as watermarker:
    font = gww.Font("Arial", 19.0, gww.FontStyle.BOLD | gww.FontStyle.ITALIC)
    watermark = gww.TextWatermark("Test watermark", font)

    watermark.foreground_color = gww.Color.red
    watermark.background_color = gww.Color.blue
    watermark.text_alignment = gww.TextAlignment.RIGHT
    watermark.opacity = 0.5

    result = watermarker.add(watermark)

    for item in result.succeeded:
        print("WatermarkId:", item.watermark_id)
        print("WatermarkType:", item.watermark_type)
        print("PageNumber:", item.page_number)
        print("WatermarkPosition:", item.watermark_position)

    watermarker.save("output.pdf")
```

### 另请参见
* module [`groupdocs.watermark.watermarks.results`](/watermark/python-net/groupdocs.watermark.watermarks.results/)
