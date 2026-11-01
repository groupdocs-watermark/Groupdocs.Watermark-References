---
title: "Класс WordProcessingImageEffects"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет эффекты, которые могут быть применены к изображению водяного знака в документе Word."
type: docs
url: /ru/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/
is_root: false
weight: 30
---


## WordProcessingImageEffects class

Представляет эффекты, которые могут быть применены к изображению водяного знака в документе Word.

Тип WordProcessingImageEffects раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/__init__/) | Инициализирует новый экземпляр класса [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/). |

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
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark, Color
from groupdocs.watermark.options.word_processing import (
    WordProcessingLoadOptions, WordProcessingWatermarkSectionOptions, WordProcessingImageEffects,
)

def add_watermark_with_effects():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        with ImageWatermark("./logo.png") as watermark:
            effects = WordProcessingImageEffects()
            effects.brightness = 0.7
            effects.contrast = 0.6
            effects.chroma_key = Color.red

            options = WordProcessingWatermarkSectionOptions()
            options.name = "Shape 1"
            options.alternative_text = "Company logo watermark"
            options.effects = effects
            watermarker.add(watermark, options)

        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_watermark_with_effects()
```

### См. также
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
