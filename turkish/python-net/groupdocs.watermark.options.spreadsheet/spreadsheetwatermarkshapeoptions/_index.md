---
title: "SpreadsheetWatermarkShapeOptions sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bir Spreadsheet çalışma sayfasına şekil filigranı eklerken seçenekleri temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/
is_root: false
weight: 120
---


## SpreadsheetWatermarkShapeOptions class

Bir Spreadsheet çalışma sayfasına şekil filigranı eklerken seçenekleri temsil eder.

Daha fazla bilgi edinin:
- Add watermarks to spreadsheet documents (https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

SpreadsheetWatermarkShapeOptions türü aşağıdaki üyeleri ortaya çıkarır:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/__init__/) | SpreadsheetWatermarkShapeOptions sınıfının yeni bir örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [effects](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/effects/) | Filigrana uygulanan efektler, bir [`SpreadsheetImageEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/) veya [`SpreadsheetTextEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/) örneği olarak belirtilir. |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/worksheet_index/) | Filigranın ekleneceği çalışma sayfasının indeksi. |
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
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.spreadsheet import (
    SpreadsheetLoadOptions, SpreadsheetWatermarkShapeOptions,
)

def add_watermark_to_worksheet():
    with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        options = SpreadsheetWatermarkShapeOptions()
        options.worksheet_index = 0
        watermarker.add(watermark, options)

        watermarker.save("./output.xlsx")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
