---
title: "IDocumentInfo sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Temel belge bilgilerini almayı gerektiren yöntemleri sağlar."
type: docs
url: /tr/python-net/groupdocs.watermark.common/idocumentinfo/
is_root: false
weight: 70
---


## IDocumentInfo class

Temel belge bilgilerini almayı gerektiren yöntemleri sağlar.

Daha fazla bilgi edinin: Belge bilgilerini alın.

IDocumentInfo türü aşağıdaki üyeleri gösterir:

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/file_type/) | Dosya formatı açıklaması. |
| [is_encrypted](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/is_encrypted/) | Bu özellik, belgenin şifrelenip şifrelenmediğini ve açmak için bir parolaya ihtiyaç duyup duymadığını gösterir. |
| [page_count](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/page_count/) | Toplam sayfa sayısı. |
| [pages](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/pages/) | Belge sayfalarının açıklamaları koleksiyonu. |
| [size](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/size/) | Belgenin bayt cinsinden boyutu. |

### Örnek

```python
from groupdocs.watermark import Watermarker

with Watermarker(r"D:\input.pdf") as watermarker:
    doc_info = watermarker.get_document_info()
    print(f"Document size: {doc_info.size}")
    print(f"Document format: {doc_info.file_type.file_format_name}")
    print(f"Document contains {doc_info.page_count} pages")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
