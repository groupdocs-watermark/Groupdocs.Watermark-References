---
title: "Görüntü filigranları ekleyin"
linkTitle: "Add image watermarks"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bu makale, bir belgeye görüntü filigranı eklemeyi ve sonucu .NET üzerinden Python için GroupDocs.Watermark ile kaydetmeyi gösterir."
type: docs
url: /tr/python-net/guides/add-image/
is_root: false
weight: 50
---


GroupDocs.Watermark'ın temel özelliklerinden biri, belgelere görüntü filigranları eklemektir. Filigranları yerel bir yoldan ya da bir akıştan belgeye veya görüntülere ekleyebilirsiniz. Desteklenen belge formatları için [Desteklenen belge formatları](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/) adresine bakın.

## Add an image watermark

Bir görüntü filigranı eklemek için şu adımları izleyin:

1. Belgeyi, yolunu (veya bir akışı) [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) sınıfına geçirerek açın.
2. Filigran görüntü dosyasından (veya bir akıştan) bir [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) oluşturun.
3. Filigranı konumlandırın — örneğin, `horizontal_alignment`, `vertical_alignment` ve `opacity` değerlerini ayarlayın.
4. Filigranı uygulamak için `add()` ve sonucu yazmak için `save()` metodunu çağırın.

{{< tabs "code-example-add-image">}}
{{< tab "add_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_image_watermark():
    with Watermarker("./sample.docx") as watermarker:
        # Bir logo dosyasından görüntü filigranı oluşturun ve ortalayın
        watermark = ImageWatermark("./logo.png")
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.opacity = 0.7

        watermarker.add(watermark)
        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_image_watermark()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` ve `logo.png` bu örnekte kullanılan örnek dosyalardır. [sample.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/sample.docx) ve [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/logo.png) dosyalarını indirin.

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 127 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-image/add_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}

## What's next

GroupDocs.Watermark, görüntü filigranları için akıştan yükleme, ölçeklendirme, döşeme ve mutlak ya da göreceli konumlandırma gibi daha fazla özellik sunar. Gelişmiş kılavuzda [Adding image watermarks](https://docs.groupdocs.com/watermark/python-net/adding-image-watermarks/) bölümüne bakın.
