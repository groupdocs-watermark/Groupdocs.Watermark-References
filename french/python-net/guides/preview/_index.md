---
title: "Aperçu du document"
linkTitle: "Document preview"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Générez des images d'aperçu (PNG/JPG/BMP) pour les pages de documents en utilisant GroupDocs.Watermark pour Python via .NET."
type: docs
url: /fr/python-net/guides/preview/
is_root: false
weight: 110
---


GroupDocs.Watermark peut rendre les pages de documents en images afin que vous puissiez afficher des miniatures de page sans ouvrir complètement le document dans un visualiseur. Vous pilotez le rendu avec un rappel `create_page_stream` qui fournit un flux de fichier inscriptible pour chaque page — la bibliothèque écrit l'image de la page dans ce flux et le ferme pour vous.

## Generate a document preview

Définissez [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/) avec un rappel `create_page_stream`, choisissez le `preview_format` et indiquez les `page_numbers` à rendre.

{{< tabs "code-example-preview">}}
{{< tab "generate_preview.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Fournissez un flux de fichier inscriptible pour chaque page à rendre
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

`sample.pdf` est le fichier d'exemple de deux pages utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/preview/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab "generate-preview-outputs.zip" >}}
```text
output-page-1.png (600 KB)
output-page-2.png (94 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/preview/generate_preview/generate-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Les images des pages sont écrites dans le répertoire actuel — un PNG par page demandée. Utilisez `PreviewFormats.JPEG` ou `PreviewFormats.BMP` pour d'autres formats, et définissez `options.width` / `options.height` pour contrôler la taille rendue.

La bibliothèque ferme chaque fichier que `create_page_stream` renvoie une fois la page écrite. Pour agir sur une page dès qu'elle est prête, passez un deuxième rappel : `PreviewOptions(create_page_stream, release_page_stream)` appelle `release_page_stream(page_number, stream)` avec l'objet `create_page_stream` retourné pour cette page, après que l'image complète y soit. Un `release_page_stream(page_number)` à un seul argument fonctionne également. `create_page_stream` peut aussi renvoyer un `io.BytesIO` : il reste ouvert et conserve l'image de la page jusqu'à ce que `release_page_stream` la récupère.

**Use case:** Generate page previews to display in a web app, dashboard, or document-management system without requiring users to download the full file.
