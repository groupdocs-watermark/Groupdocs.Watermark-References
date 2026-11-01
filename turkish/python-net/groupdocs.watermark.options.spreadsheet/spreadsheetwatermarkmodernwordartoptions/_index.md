---
title: "SpreadsheetWatermarkModernWordArtOptions sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bir Spreadsheet çalışma sayfasına modern kelime sanatı filigranı eklerken seçenekleri temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/
is_root: false
weight: 110
---


## SpreadsheetWatermarkModernWordArtOptions class

Bir Spreadsheet çalışma sayfasına modern kelime sanatı filigranı eklerken seçenekleri temsil eder.

Daha fazla bilgi edinin:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

SpreadsheetWatermarkModernWordArtOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/__init__/) | Yeni bir [`SpreadsheetWatermarkModernWordArtOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/) sınıfı örneği başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/worksheet_index/) | Filigranı eklemek istediğiniz çalışma sayfasının dizini. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternative_text/) | Bir şekille ilişkilendirilecek açıklayıcı (alternatif) metin. ([`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/) sınıfından miras alınmıştır.) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/is_locked/) | Bu özellik, Excel'de şeklin düzenlenmesinin yasak olup olmadığını gösterir. ([`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/) sınıfından miras alınmıştır.) |
| [name](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name/) | Şeklin adı. ([`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/) sınıfından miras alınmıştır.) |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Sınıf için varsayılan değeri alır. ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/) sınıfından devralınmıştır) |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions, SpreadsheetWatermarkModernWordArtOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = SpreadsheetLoadOptions()
with Watermarker("./spreadsheet.xlsx", load_options) as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 36.0))
    options = SpreadsheetWatermarkModernWordArtOptions()
    options.worksheet_index = 0
    options.is_locked = False
    watermarker.add(watermark, options)
    watermarker.save("./output.xlsx")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
