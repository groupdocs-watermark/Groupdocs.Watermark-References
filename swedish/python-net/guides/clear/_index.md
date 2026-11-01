---
title: "Rensa vattenstämplar"
linkTitle: "Clear watermarks"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Sök efter och ta bort befintliga text- eller bildvattenstämplar med hjälp av GroupDocs.Watermark för Python via .NET."
type: docs
url: /sv/python-net/guides/clear/
is_root: false
weight: 100
---


Du kan söka i ett dokument efter befintliga vattenstämplar och ta bort dem. Exemplet nedan hittar en "CONFIDENTIAL"-textvattenstämpel och tar bort den, vilket ger ett rent dokument.

## Remove text watermarks

Iterera sökresultaten i omvänd ordning så att borttagning av ett objekt inte förskjuter de index som fortfarande ska besökas, och anropa `remove()` för varje matchning.

{{< tabs "code-example-clear">}}
{{< tab "clear_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def clear_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        # Ta bort i omvänd ordning så att indexen förblir giltiga när objekt raderas.
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    clear_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.pdf) för att ladda ner den.

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

Bildvattenmärken kan hittas med perceptuell hashning och tas bort på samma sätt:

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
        # Ta bort i omvänd ordning så att indexen förblir giltiga när objekt raderas.
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")

if __name__ == "__main__":
    clear_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx` och `logo.png` är exempelfilerna som används i detta exempel. Ladda ner [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.docx) och [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/logo.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 13 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
