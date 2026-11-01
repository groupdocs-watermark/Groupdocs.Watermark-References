---
title: "create_page_stream özelliği"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Her işlenen sayfa için yazılabilir bir akış elde etmek amacıyla kullanılan sayfa akışı oluşturma temsilcisi."
type: docs
url: /tr/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/
is_root: false
weight: 2010
---


## create_page_stream property

Her işlenen sayfa için yazılabilir bir akış elde etmek amacıyla kullanılan sayfa akışı oluşturma temsilcisi.

GroupDocs.Watermark, belge sayfalarını görüntü olarak işler. Sayfa numarasını (`int`) alan ve yazılabilir bir `io.RawIOBase` akışı döndüren bir callable sağlayın; kütüphane işlenen görüntüyü akışa yazar ve kapatır.

### Definition:
```python
@property
def create_page_stream(self):
    ...
@create_page_stream.setter
def create_page_stream(self, value):
    ...
```

### Ayrıca Bakınız
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
