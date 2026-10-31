---
title: "Rimuovi filigrane"
linkTitle: "Clear watermarks"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Cerca e rimuovi le filigrane di testo o immagine esistenti utilizzando GroupDocs.Watermark per Python tramite .NET."
type: docs
url: /it/python-net/guides/clear/
is_root: false
weight: 100
---


Puoi cercare in un documento le filigrane esistenti e rimuoverle. L'esempio seguente trova una filigrana di testo "CONFIDENTIAL" e la rimuove, producendo un documento pulito.

## Remove text watermarks

Itera i risultati della ricerca in ordine inverso in modo che la rimozione di un elemento non sposti gli indici ancora da visitare, e chiama `remove()` per ogni corrispondenza.

{{< tabs "code-example-clear">}}
{{< tab "clear_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def clear_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        # Rimuovi in ordine inverso così gli indici rimangono validi mentre gli elementi vengono eliminati
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    clear_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.pdf) per scaricarlo.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 360 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Remove outdated labels such as "Draft" or "Internal Use Only" before sharing a document externally.

## Remove image watermarks

Le filigrane immagine possono essere trovate con l'hashing percettivo e rimosse allo stesso modo:

{{< tabs "code-example-clear-image">}}
{{< tab "clear_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def clear_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        # Rimuovi in ordine inverso così gli indici rimangono validi mentre gli elementi vengono eliminati
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")

if __name__ == "__main__":
    clear_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx` e `logo.png` sono i file di esempio utilizzati in questo esempio. Scarica [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.docx) e [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/logo.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 13 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
