---
title: "SpreadsheetLoadOptions sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Spreadsheet belgesi için belge yükleme seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/
is_root: false
weight: 40
---


## SpreadsheetLoadOptions class

Spreadsheet belgesi için belge yükleme seçeneklerini temsil eder.

SpreadsheetLoadOptions türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/) | Yeni bir [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/) sınıfı örneği başlatır. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/#password) | Belirtilen bir şifre ile yeni bir [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/) sınıfı örneği başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Dosyanın türü, formatını gösterir (ör. docx, pdf, xlsx, vb.). (şu sınıftan devralınmıştır [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Belgenin format ailesi, tipini gösterir (ör. Image, Pdf, Spreadsheet, vb.). (şu sınıftan devralınmıştır [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Şifrelenmiş bir belgeyi açmak için parola. (şu sınıftan devralınmıştır [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/default/) | Sınıf için varsayılan değeri alır. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
    # burada filigran işlemlerini gerçekleştir
    pass
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
