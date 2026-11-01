---
title: "Metin filigranları ekleyin"
linkTitle: "Add text watermarks"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bu makale, bir belgeye metin filigranı eklemeyi ve sonucu GroupDocs.Watermark for Python via .NET ile kaydetmeyi gösterir."
type: docs
url: /tr/python-net/guides/add-text/
is_root: false
weight: 40
---


GroupDocs.Watermark'ın temel özelliklerinden biri, belgelere metin filigranları eklemektir. Filigranları yerel bir yoldan veya bir akıştan belgeye ya da görüntülere ekleyebilirsiniz. Desteklenen formatların tam listesi için [Desteklenen belge formatları](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/) sayfasına bakın.

## Add a text watermark

Metin filigranı eklemek için şu adımları izleyin:

1. Belgeyi, yolunu (veya bir akışı) [Watermarker](https://reference.groupdocs.com/watermark/python-net/) sınıfına geçirerek açın, belge otomatik olarak serbest bırakılması için bir `with` bloğu kullanın.
2. İstenen metin ve [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/) ile bir [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) oluşturun.
3. Filigranı biçimlendirin — örneğin, `foreground_color` ve hizalamayı ayarlayın.
4. Filigranı uygulamak için `add()` ve sonucu yazmak için `save()` metodunu çağırın.

{{< tabs "code-example-add-text">}}
{{< tab "add_text_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_text_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        # Metin filigranını oluşturun ve biçimlendirin
        watermark = TextWatermark("Top Secret", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.rotate_angle = 45.0
        watermark.opacity = 0.4

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    add_text_watermark()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-text/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-text/add_text_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Programı çalıştırın. Belirtilen yolda yeni bir filigranlı belge ortaya çıkar.

## What's next

GroupDocs.Watermark, metin filigranları için daha birçok özellik sunar — arka plan ve ön plan renkleri, özel yazı tipleri, opaklık, döndürme, döşeme ve mutlak ya da göreli konumlandırma. Gelişmiş kılavuzda [Metin filigranları ekleme](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/) bölümüne bakın.
