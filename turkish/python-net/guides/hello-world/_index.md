---
title: "Merhaba, Dünya!"
linkTitle: "Hello, World!"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "GroupDocs.Watermark for Python via .NET ile hızlıca başlayın; basit bir örnek oluşturarak ve çalıştırarak."
type: docs
url: /tr/python-net/guides/hello-world/
is_root: false
weight: 20
---


## Introduction
"Hello, World!" örneği, GroupDocs.Watermark for Python via .NET keşfederken genellikle ilk adımdır. Geliştirme ortamınızın doğru şekilde kurulduğunu ve kütüphanenin beklendiği gibi çalıştığını doğrulamak için basit bir test olarak hizmet eder.

## Overview
GroupDocs.Watermark for Python via .NET, çeşitli belge formatlarında filigran eklemenize, aramanıza ve kaldırmanıza olanak tanır. Geniş bir [desteklenen formatlar](https://docs.groupdocs.com/watermark/python-net/getting-started/supported-document-formats/) yelpazesi, farklı kullanım senaryoları için çok yönlülük sağlar.

## How to add a watermark
Aşağıdaki adımlar, GroupDocs.Watermark for Python via .NET kullanarak bir belgeye metin filigranı eklemenin nasıl yapılacağını gösterir:

1. İhtiyacınız olan `groupdocs.watermark` sınıflarını içe aktarın.
2. Örnek belgeye giden yolu kullanarak bir [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) açın.
3. İstenen metin ve yazı tipiyle bir [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) oluşturun ve stilini ayarlayın.
4. Filigranı `add()` ile uygulayın.
5. Sonucu kaydedin.

## Complete example
Aşağıdaki örnek, yarı saydam, çapraz "Hello, Watermark!" metin filigranı ekler ve sonucu kaydeder:

{{< tabs "code-example-hello-world" >}}
{{< tab "hello_world.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

def hello_world():
    # `sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/watermark/python-net/_sample_files/getting-started/hello-world/sample.pdf) tıklayın.
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("Hello, Watermark!", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.opacity = 0.5
        watermark.rotate_angle = 45.0
        watermarker.add(watermark)
        watermarker.save("./output.pdf")

    print("Watermark added successfully. Output saved to ./output.pdf.")

if __name__ == "__main__":
    hello_world()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

Filigran, `output.pdf` ile aynı PDF formatında kaydedilir. Farklı bir belgeye damga eklemek için giriş yolunu ve çıktı uzantısını değiştirin — GroupDocs.Watermark, giriş belgesinin formatında kaydeder.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 315 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/getting-started/hello-world/hello_world/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Bu demo, GroupDocs.Watermark for Python via .NET [kod örneklerine](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET/) referans verir.

## Additional resources
Özellikler Genel Bakışı
