---
title: "SpreadsheetBackgroundWatermarkOptions sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Filigranı bir Spreadsheet çalışma sayfasına arka plan olarak eklerken seçenekleri temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/
is_root: false
weight: 20
---


## SpreadsheetBackgroundWatermarkOptions class

Filigranı bir Spreadsheet çalışma sayfasına arka plan olarak eklerken seçenekleri temsil eder.

Daha fazla bilgi edinin: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

SpreadsheetBackgroundWatermarkOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/__init__/) | Yeni bir [`SpreadsheetBackgroundWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/) sınıfı örneği başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [background_height](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/background_height/) | Arka plan görüntüsünün piksel cinsinden istenen yüksekliği. |
| [background_width](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/background_width/) | Arka plan görüntüsünün piksel cinsinden istenen genişliği. |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/worksheet_index/) | Filigranın ekleneceği çalışma sayfasının indeksi. |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Sınıf için varsayılan değeri alır. ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/) sınıfından devralınmıştır) |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions, SpreadsheetBackgroundWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = SpreadsheetLoadOptions()
with Watermarker(r"C:\Documents\test.xlsx", load_options) as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 36))

    options = SpreadsheetBackgroundWatermarkOptions()
    options.worksheet_index = -1  # default
    options.background_width = 800
    options.background_height = 600

    watermarker.add(watermark, options)
    watermarker.save()
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
