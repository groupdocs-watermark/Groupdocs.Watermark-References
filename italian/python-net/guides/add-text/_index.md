---
title: "Aggiungi filigrane di testo"
linkTitle: "Add text watermarks"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Questo articolo mostra come aggiungere una filigrana di testo a un documento e salvare il risultato con GroupDocs.Watermark per Python via .NET."
type: docs
url: /it/python-net/guides/add-text/
is_root: false
weight: 40
---


Una delle principali funzionalità di GroupDocs.Watermark è l'aggiunta di filigrane di testo ai documenti. Puoi aggiungere filigrane a documenti o immagini da un percorso locale, così come da uno stream. Per un elenco completo dei formati supportati, consulta [Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add a text watermark

Per aggiungere una filigrana di testo, segui questi passaggi:

1. Apri il documento passando il suo percorso (o uno stream) alla classe [Watermarker](https://reference.groupdocs.com/watermark/python-net/) usando un blocco `with` in modo che il documento venga rilasciato automaticamente.
2. Crea un [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) con il testo desiderato e un [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/).
3. Stila la filigrana — ad esempio, imposta `foreground_color` e l'allineamento.
4. Chiama `add()` per applicare la filigrana e `save()` per scrivere il risultato.

{{< tabs \"code-example-add-text\">}}
{{< tab \"add_text_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_text_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        # Crea la filigrana di testo e stilala
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
{{< tab "sample.pdf" >}}

`sample.pdf` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-text/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-text/add_text_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Esegui il programma. Un nuovo documento con filigrana appare nel percorso specificato.

## What's next

GroupDocs.Watermark offre molte altre funzionalità per le filigrane di testo — colori di sfondo e di primo piano, caratteri personalizzati, opacità, rotazione, piastrellatura e posizionamento assoluto o relativo. Vedi [Adding text watermarks](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/) nella guida avanzata.
