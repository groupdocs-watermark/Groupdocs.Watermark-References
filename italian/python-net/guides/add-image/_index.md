---
title: "Aggiungi filigrane immagine"
linkTitle: "Add image watermarks"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Questo articolo mostra come aggiungere una filigrana immagine a un documento e salvare il risultato con GroupDocs.Watermark per Python tramite .NET."
type: docs
url: /it/python-net/guides/add-image/
is_root: false
weight: 50
---


Una delle principali funzionalità di GroupDocs.Watermark è l'aggiunta di filigrane immagine ai documenti. È possibile aggiungere filigrane a documenti o immagini da un percorso locale, così come da uno stream. Per un elenco completo dei formati supportati, consulta [Formati di documento supportati](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add an image watermark

Per aggiungere una filigrana immagine, segui questi passaggi:

1. Apri il documento passando il suo percorso (o uno stream) alla classe [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/).
2. Crea un [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) dal file immagine della filigrana (o da uno stream).
3. Posiziona la filigrana — ad esempio, imposta `horizontal_alignment`, `vertical_alignment` e `opacity`.
4. Chiama `add()` per applicare la filigrana e `save()` per scrivere il risultato.

{{< tabs "code-example-add-image">}}
{{< tab "add_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_image_watermark():
    with Watermarker("./sample.docx") as watermarker:
        # Crea una filigrana immagine da un file logo e centrala
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

`sample.docx` e `logo.png` sono i file di esempio utilizzati in questo esempio. Scarica [sample.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/sample.docx) e [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/logo.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 127 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-image/add_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}

## What's next

GroupDocs.Watermark offre ulteriori funzionalità per le filigrane immagine — caricamento da stream, ridimensionamento, mosaico e posizionamento assoluto o relativo. Vedi [Aggiunta di filigrane immagine](https://docs.groupdocs.com/watermark/python-net/adding-image-watermarks/) nella guida avanzata.
