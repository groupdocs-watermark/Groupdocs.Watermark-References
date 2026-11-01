---
title: "PresentationLoadOptions sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bir Presentation belgesi için belge yükleme seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/
is_root: false
weight: 30
---


## PresentationLoadOptions class

Bir Presentation belgesi için belge yükleme seçeneklerini temsil eder.

PresentationLoadOptions türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/) | Yeni bir [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/) sınıfı örneği başlatır. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/#password) | Belirtilen bir şifre ile yeni bir PresentationLoadOptions sınıfı örneği başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Dosyanın türü, formatını gösterir (ör. docx, pdf, xlsx, vb.). (şu sınıftan devralınmıştır [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Belgenin format ailesi, tipini gösterir (ör. Image, Pdf, Spreadsheet, vb.). (şu sınıftan devralınmıştır [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Şifrelenmiş bir belgeyi açmak için parola. (şu sınıftan devralınmıştır [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/default/) | Sınıf için varsayılan değeri alır. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
    # belgeyle çalış
    pass
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
