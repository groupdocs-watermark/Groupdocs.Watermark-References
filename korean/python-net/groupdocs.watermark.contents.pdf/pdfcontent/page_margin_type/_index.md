---
title: "page_margin_type 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "워터마크 추가 중에 사용할 PDF 페이지 여백입니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/
is_root: false
weight: 2020
---


## page_margin_type property

워터마크 추가 중에 사용할 PDF 페이지 여백입니다.

이 속성은 [`Watermark.consider_parent_margins`](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) 가 True 로 설정된 경우에만 작동합니다. False인 경우, PDF CropBox가 워터마크 영역으로 사용됩니다.

기본값은 `PdfPageMarginType.trim_box`입니다.

### Definition:
```python
@property
def page_margin_type(self):
    ...
@page_margin_type.setter
def page_margin_type(self, value):
    ...
```

### 또 보기
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
