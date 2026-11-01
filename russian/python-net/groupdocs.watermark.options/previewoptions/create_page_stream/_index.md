---
title: "свойство create_page_stream"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Делегат создания потока страницы, используемый для получения записываемого потока для каждой отрисованной страницы."
type: docs
url: /ru/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/
is_root: false
weight: 2010
---


## create_page_stream property

Делегат создания потока страницы, используемый для получения записываемого потока для каждой отрисованной страницы.

GroupDocs.Watermark рендерит страницы документа как изображения. Предоставьте callable, который принимает номер страницы (`int`) и возвращает записываемый поток `io.RawIOBase`; библиотека записывает отрендеренное изображение в поток и закрывает его.

### Definition:
```python
@property
def create_page_stream(self):
    ...
@create_page_stream.setter
def create_page_stream(self, value):
    ...
```

### См. также
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
