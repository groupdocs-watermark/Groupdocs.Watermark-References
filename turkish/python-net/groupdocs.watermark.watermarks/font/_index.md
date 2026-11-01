---
title: "Font sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bir yazı tipini temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.watermarks/font/
is_root: false
weight: 20
---


## Font class

Bir yazı tipini temsil eder.

Font türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size) | Belirtilen yazı tipi ailesi adı ve boyutuyla yeni bir Font örneği oluşturur. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size-style) | Belirtilen yazı tipi ailesi adı, boyut ve stil ile yeni bir Font örneği oluşturur. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size) | Özel bir yazı tipi ailesi adı, TrueType yazı tiplerini içeren bir klasör, bir boyut ve bir stil ile yeni bir Font örneği oluşturur. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size-style) | Özel bir yazı tipi ailesi adı, TrueType yazı tipi dosyalarını içeren klasör ve bir boyut ile yeni bir Font örneği oluşturur. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [bold](/watermark/python-net/groupdocs.watermark.watermarks/font/bold/) | Yazı tipi kalındır. |
| [family_name](/watermark/python-net/groupdocs.watermark.watermarks/font/family_name/) | Bu Font'un aile adı. |
| [folder_path](/watermark/python-net/groupdocs.watermark.watermarks/font/folder_path/) | TrueType yazı tipi dosyalarını içeren klasör. |
| [italic](/watermark/python-net/groupdocs.watermark.watermarks/font/italic/) | Yazı tipi italiktir. |
| [size](/watermark/python-net/groupdocs.watermark.watermarks/font/size/) | Bu Yazı tipinin boyutu. |
| [strikeout](/watermark/python-net/groupdocs.watermark.watermarks/font/strikeout/) | Yazı tipi, metnin üzerinden yatay bir çizgi belirtir. |
| [style](/watermark/python-net/groupdocs.watermark.watermarks/font/style/) | Bu Yazı tipinin stil bilgileri. |
| [underline](/watermark/python-net/groupdocs.watermark.watermarks/font/underline/) | Yazı tipi altı çizili. |

### Örnek

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
`Font` kullanan görev kılavuzları:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Ayrıca Bakınız
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
