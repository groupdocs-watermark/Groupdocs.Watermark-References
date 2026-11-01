---
title: "MultiframeImageWatermarkOptions sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Çok çerçeveli bir görüntüye filigran eklenirken filigran ekleme seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/
is_root: false
weight: 70
---


## MultiframeImageWatermarkOptions class

Çok çerçeveli bir görüntüye filigran eklenirken filigran ekleme seçeneklerini temsil eder.

Daha fazla bilgi: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images

MultiframeImageWatermarkOptions türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/__init__/) | [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/) sınıfının yeni bir örneğini oluşturur. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/__init__/#frame_index) | [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/) sınıfının, çerçevenin belirtilen indeksine sahip yeni bir örneğini oluşturur. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [frame_index](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frame_index/) | Filigran eklemek için çerçevenin indeksi. |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Sınıf için varsayılan değeri alır. ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/) sınıfından devralınmıştır) |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.image import ImageLoadOptions, MultiframeImageWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = ImageLoadOptions()
with Watermarker(r"C:\test.gif", load_options) as watermarker:
    watermark = TextWatermark("Test", Font("Arial", 12))
    options = MultiframeImageWatermarkOptions()
    options.frame_index = 0
    watermarker.add(watermark, options)
    watermarker.save()
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.options.image`](/watermark/python-net/groupdocs.watermark.options.image/)
