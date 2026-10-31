---
title: "Mettre à jour les filigranes"
linkTitle: "Update watermarks"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Recherchez les filigranes texte ou image existants et mettez‑les à jour à l'aide de GroupDocs.Watermark pour Python via .NET."
type: docs
url: /fr/python-net/guides/update/
is_root: false
weight: 90
---


Vous pouvez rechercher les filigranes existants dans un document et les modifier sur place — par exemple, remplacer le texte d'un filigrane texte ou échanger l'image d'un filigrane image.

## Update text watermarks

Recherchez un filigrane par son contenu texte, puis attribuez une nouvelle valeur à chaque correspondance. L'exemple ci‑dessous ouvre un document contenant déjà un filigrane "CONFIDENTIAL" et le remplace par "APPROVED".

{{< tabs "code-example-update">}}
{{< tab "update_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def update_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        # Trouvez les filigranes dont le texte correspond aux critères
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s).")
        for watermark in possible:
            try:
                watermark.text = "APPROVED"
            except Exception:
                # Certaines entités trouvées ne prennent pas en charge la modification du texte — ignorez‑les
                pass
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    update_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.pdf) pour le télécharger.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 444 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

## Update image watermarks

Les filigranes image peuvent être trouvés grâce au hachage perceptuel ([`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)) et mis à jour en attribuant de nouveaux octets à `image_data`. L'exemple ci‑dessous trouve le filigrane logo et le remplace par un tampon "APPROVED" :

{{< tabs "code-example-update-image">}}
{{< tab "update_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def update_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        with open("./stamp.png", "rb") as f:
            image_data = f.read()
        for watermark in possible:
            try:
                watermark.image_data = image_data
            except Exception:
                # Certaines entités trouvées ne prennent pas en charge l'édition d'images — les ignorer.
                pass
        watermarker.save("./output.docx")

if __name__ == "__main__":
    update_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx`, `logo.png` et `stamp.png` sont les fichiers d'exemple utilisés dans cet exemple. Téléchargez [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.docx), [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/logo.png) et [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/stamp.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 19 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
