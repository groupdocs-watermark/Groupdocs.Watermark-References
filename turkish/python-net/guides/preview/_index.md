---
title: "Belge önizlemesi"
linkTitle: "Document preview"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: ".NET üzerinden Python için GroupDocs.Watermark kullanarak belge sayfaları için önizleme görselleri (PNG/JPG/BMP) oluşturun."
type: docs
url: /tr/python-net/guides/preview/
is_root: false
weight: 110
---


GroupDocs.Watermark, belge sayfalarını görüntü olarak render edebilir, böylece bir belgeyi görüntüleyicide tamamen açmadan sayfa küçük resimlerini gösterebilirsiniz. Render'ı, her sayfa için yazılabilir bir dosya akışı sağlayan `create_page_stream` geri çağrısı ile yönlendirirsiniz — kütüphane sayfa görüntüsünü ona yazar ve sizin için kapatır.

## Generate a document preview

Bir `create_page_stream` geri çağrısı ile [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/) ayarlayın, `preview_format` seçin ve render edilecek `page_numbers` listesini belirtin.

{{< tabs "code-example-preview">}}
{{< tab "generate_preview.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Her sayfayı renderlemek için yazılabilir bir dosya akışı sağlayın
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` bu örnekte kullanılan iki sayfalı örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/preview/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "generate-preview-outputs.zip" >}}
```text
output-page-1.png (600 KB)
output-page-2.png (94 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/preview/generate_preview/generate-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Sayfa görüntüleri geçerli dizine yazılır — istenen her sayfa için bir PNG. Diğer formatlar için `PreviewFormats.JPEG` veya `PreviewFormats.BMP` kullanın ve render boyutunu kontrol etmek için `options.width` / `options.height` ayarlayın.

Kütüphane, sayfa yazıldıktan sonra `create_page_stream` tarafından döndürülen her dosyayı kapatır. Sayfa hazır olduğunda harekete geçmek için ikinci bir geri çağrı verin: `PreviewOptions(create_page_stream, release_page_stream)` `release_page_stream(page_number, stream)` metodunu, o sayfa için döndürülen `create_page_stream` nesnesiyle, bütün görüntü akışına alındıktan sonra çağırır. Tek parametreli `release_page_stream(page_number)` da çalışır. `create_page_stream` ayrıca bir `io.BytesIO` döndürebilir: bu açık kalır ve `release_page_stream` ona ulaşana kadar sayfa görüntüsünü tutar.

**Use case:** Generate page previews to display in a web app, dashboard, or document-management system without requiring users to download the full file.
