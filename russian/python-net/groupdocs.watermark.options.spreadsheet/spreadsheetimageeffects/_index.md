---
title: "Класс SpreadsheetImageEffects"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет эффекты, которые можно применить к изображению водяного знака в документе Excel."
type: docs
url: /ru/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/
is_root: false
weight: 30
---


## SpreadsheetImageEffects class

Представляет эффекты, которые можно применить к изображению водяного знака в документе Excel.

Тип SpreadsheetImageEffects раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/__init__/) | Инициализирует новый экземпляр класса [`SpreadsheetImageEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/). |

### Свойства
| Свойство | Описание |
| :- | :- |
| [border_line_format](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/border_line_format/) | Настройки формата линии для границы изображения. (унаследовано от [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [brightness](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/brightness/) | Яркость изображения. Должно быть число с плавающей точкой от 0.0 (самая темная) до 1.0 (самая яркая). Значение по умолчанию — 0.5. (унаследовано от [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [chroma_key](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/chroma_key/) | Значение цвета изображения, которое будет считаться прозрачным. Значение по умолчанию — полностью прозрачный цвет. (унаследовано от [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [contrast](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/contrast/) | Контраст указанного изображения. Должно быть число с плавающей точкой от 0.0 (наименьший контраст) до 1.0 (наибольший контраст). Значение по умолчанию — 0.5. (унаследовано от [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [gray_scale](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/gray_scale/) | Свойство указывает, будет ли изображение отображаться в режиме градаций серого. (унаследовано от [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |

### Пример

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

### См. также
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
