---
title: "WordProcessingLoadOptions sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Word belgesi için belge yükleme seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/
is_root: false
weight: 40
---


## WordProcessingLoadOptions class

Word belgesi için belge yükleme seçeneklerini temsil eder.

WordProcessingLoadOptions türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/) | Yeni bir [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/) sınıfı örneği başlatır. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/#password) | Belirtilen bir şifre ile WordProcessingLoadOptions sınıfının yeni bir örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Dosyanın türü, formatını gösterir (ör. docx, pdf, xlsx, vb.). (şu sınıftan devralınmıştır [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Belgenin format ailesi, tipini gösterir (ör. Image, Pdf, Spreadsheet, vb.). (şu sınıftan devralınmıştır [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Şifrelenmiş bir belgeyi açmak için parola. (şu sınıftan devralınmıştır [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/default/) | Sınıf için varsayılan değeri alır. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

def process_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        # İçerik üzerinde işlemler gerçekleştirir, ör. koruma, korumayı kaldırma, filigran ekleme
        watermarker.save("./output.docx")

if __name__ == "__main__":
    process_document()
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
