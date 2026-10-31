---
title: "page_margin_type 属性"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "在添加水印期间使用的 PDF 页面边距。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/
is_root: false
weight: 2020
---


## page_margin_type property

在添加水印期间使用的 PDF 页面边距。

此属性仅在 [`Watermark.consider_parent_margins`](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) 设置为 True 时工作。如果为 False，则使用 PDF CropBox 作为水印区域。

默认值为 `PdfPageMarginType.trim_box`。

### Definition:
```python
@property
def page_margin_type(self):
    ...
@page_margin_type.setter
def page_margin_type(self, value):
    ...
```

### 另请参见
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
