---
title: "page_margin_type プロパティ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "透かし追加時に使用される PDF ページ余白です。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/
is_root: false
weight: 2020
---


## page_margin_type property

透かし追加時に使用される PDF ページ余白です。

このプロパティは、[`Watermark.consider_parent_margins`](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) が True に設定されている場合にのみ機能します。False の場合、PDF CropBox が透かし領域として使用されます。

デフォルト値は `PdfPageMarginType.trim_box` です。

### Definition:
```python
@property
def page_margin_type(self):
    ...
@page_margin_type.setter
def page_margin_type(self, value):
    ...
```

### 関連項目
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
