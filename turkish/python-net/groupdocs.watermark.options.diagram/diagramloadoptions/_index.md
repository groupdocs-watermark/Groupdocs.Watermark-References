---
title: "DiagramLoadOptions sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Visio belgesi için belge yükleme seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/
is_root: false
weight: 10
---


## DiagramLoadOptions class

Visio belgesi için belge yükleme seçeneklerini temsil eder.

DiagramLoadOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/__init__/) | [`DiagramLoadOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/) sınıfının yeni bir örneğini başlatır. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/__init__/#password) | [`DiagramLoadOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/) sınıfının yeni bir örneğini belirtilen bir şifreyle başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Dosyanın türü, formatını gösterir (ör. docx, pdf, xlsx, vb.). (şu sınıftan devralınmıştır [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Belgenin format ailesi, tipini gösterir (ör. Image, Pdf, Spreadsheet, vb.). (şu sınıftan devralınmıştır [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Şifrelenmiş bir belgeyi açmak için parola. (şu sınıftan devralınmıştır [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/default/) | Sınıf için varsayılan değeri alır. |

### Örnek

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.diagram import DiagramLoadOptions
import groupdocs.watermark.contents.diagram as gwc_vsdx

load_options = DiagramLoadOptions()
with gw.Watermarker("diagram.vsdx", load_options) as watermarker:
    content = watermarker.get_content()
    # şekilleri burada manipüle edin
    watermarker.save("output.vsdx")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
