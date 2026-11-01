---
title: "EmailLoadOptions sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "E-posta mesajı için belge yükleme seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.options.email/emailloadoptions/
is_root: false
weight: 10
---


## EmailLoadOptions class

E-posta mesajı için belge yükleme seçeneklerini temsil eder.

EmailLoadOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/__init__/) | Yeni bir [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/) sınıfı örneği başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Dosyanın türü, formatını gösterir (ör. docx, pdf, xlsx, vb.). (şu sınıftan devralınmıştır [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Belgenin format ailesi, tipini gösterir (ör. Image, Pdf, Spreadsheet, vb.). (şu sınıftan devralınmıştır [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Şifrelenmiş bir belgeyi açmak için parola. (şu sınıftan devralınmıştır [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/default/) | Sınıf için varsayılan değeri alır. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # burada e-posta içeriğini değiştirin
    watermarker.save("./output.msg")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.options.email`](/watermark/python-net/groupdocs.watermark.options.email/)
