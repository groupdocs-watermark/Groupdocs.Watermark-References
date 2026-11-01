---
title: "Класс Font"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет шрифт."
type: docs
url: /ru/python-net/groupdocs.watermark.watermarks/font/
is_root: false
weight: 20
---


## Font class

Представляет шрифт.

Тип Font раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size) | Инициализирует новый экземпляр Font с указанным названием семейства шрифтов и размером. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size-style) | Инициализирует новый экземпляр Font с указанным названием семейства шрифтов, размером и стилем. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size) | Инициализирует новый экземпляр Font с пользовательским названием семейства шрифтов, папкой, содержащей TrueType шрифты, размером и стилем. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size-style) | Инициализирует новый экземпляр Font с пользовательским названием семейства шрифтов, папкой, содержащей файлы TrueType шрифтов, и размером. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [bold](/watermark/python-net/groupdocs.watermark.watermarks/font/bold/) | Шрифт жирный. |
| [family_name](/watermark/python-net/groupdocs.watermark.watermarks/font/family_name/) | Название семейства этого Font. |
| [folder_path](/watermark/python-net/groupdocs.watermark.watermarks/font/folder_path/) | Папка, содержащая файлы TrueType шрифтов. |
| [italic](/watermark/python-net/groupdocs.watermark.watermarks/font/italic/) | Шрифт курсивный. |
| [size](/watermark/python-net/groupdocs.watermark.watermarks/font/size/) | Размер этого шрифта. |
| [strikeout](/watermark/python-net/groupdocs.watermark.watermarks/font/strikeout/) | Шрифт задает горизонтальную линию через текст. |
| [style](/watermark/python-net/groupdocs.watermark.watermarks/font/style/) | Информация о стиле этого шрифта. |
| [underline](/watermark/python-net/groupdocs.watermark.watermarks/font/underline/) | Шрифт подчеркивается. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Guides
Руководства задач, использующие `Font`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### См. также
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
