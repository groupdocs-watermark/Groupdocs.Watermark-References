---
title: "SpreadsheetImageEffects sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Excel belgesi için bir görüntü filigranına uygulanabilecek efektleri temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/
is_root: false
weight: 30
---


## SpreadsheetImageEffects class

Excel belgesi için bir görüntü filigranına uygulanabilecek efektleri temsil eder.

SpreadsheetImageEffects türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/__init__/) | Yeni bir [`SpreadsheetImageEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/) sınıfı örneği başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [border_line_format](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/border_line_format/) | Görüntü kenarlığının çizgi biçim ayarları. ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) sınıfından devralınmıştır) |
| [brightness](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/brightness/) | Resmin parlaklığı. 0.0 (en karanlık) ile 1.0 (en parlak) arasında bir ondalık sayı olmalıdır. Varsayılan değer 0.5'tir. ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) sınıfından devralınmıştır) |
| [chroma_key](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/chroma_key/) | Şeffaf olarak işlenecek görüntünün renk değeri. Varsayılan değer tamamen şeffaf bir renktir. ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) sınıfından devralınmıştır) |
| [contrast](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/contrast/) | Belirtilen resmin kontrastı. 0.0 (en düşük kontrast) ile 1.0 (en yüksek kontrast) arasında bir ondalık sayı olmalıdır. Varsayılan değer 0.5'tir. ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) sınıfından devralınmıştır) |
| [gray_scale](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/gray_scale/) | Bu özellik, bir resmin gri tonlamalı modda gösterilip gösterilmeyeceğini belirtir. ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) sınıfından devralınmıştır) |

### Örnek

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.spreadsheet as gwo_xls

load_options = gwo_xls.SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    with gww.ImageWatermark("logo.png") as watermark:
        effects = gwo_xls.SpreadsheetImageEffects()
        effects.brightness = 0.7
        effects.contrast = 0.6
        effects.chroma_key = gww.Color.red
        effects.border_line_format.enabled = True
        effects.border_line_format.weight = 1
        options = gwo_xls.SpreadsheetWatermarkShapeOptions()
        options.effects = effects
        watermarker.add(watermark, options)
    watermarker.save("output.xlsx")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
