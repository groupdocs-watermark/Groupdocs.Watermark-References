---
title: "Bonjour, le monde!"
linkTitle: "Hello, World!"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Commencez rapidement avec GroupDocs.Watermark pour Python via .NET en créant et exécutant un exemple simple."
type: docs
url: /fr/python-net/guides/hello-world/
is_root: false
weight: 20
---


## Introduction
Un exemple "Hello, World!" est souvent la première étape lors de l'exploration de GroupDocs.Watermark pour Python via .NET. Il sert de test simple pour confirmer que votre environnement de développement est correctement configuré et que la bibliothèque fonctionne comme prévu.

## Overview
GroupDocs.Watermark pour Python via .NET vous permet d'ajouter, de rechercher et de supprimer des filigranes dans divers formats de documents. Une large gamme de [supported formats](https://docs.groupdocs.com/watermark/python-net/getting-started/supported-document-formats/) le rend polyvalent pour différents cas d'utilisation.

## How to add a watermark
Les étapes suivantes montrent comment ajouter un filigrane texte à un document en utilisant GroupDocs.Watermark pour Python via .NET :

1. Importez les classes `groupdocs.watermark` dont vous avez besoin.
2. Ouvrez un [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) avec le chemin vers le document d'exemple.
3. Créez un [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) avec le texte et la police souhaités, puis stylisez‑le.
4. Appliquez le filigrane avec `add()`.
5. Enregistrez le résultat.

## Complete example
L'exemple ci‑dessous ajoute un filigrane texte « Hello, Watermark! » semi‑transparent et diagonal, puis enregistre le résultat :

{{< tabs \"code-example-hello-world\" >}}
{{< tab \"hello_world.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

def hello_world():
    # Ouvrez le document, ajoutez un seul filigrane texte et enregistrez le résultat
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

`sample.pdf` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/watermark/python-net/_sample_files/getting-started/hello-world/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 315 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/getting-started/hello-world/hello_world/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Le filigrane est enregistré de nouveau au même format PDF que `output.pdf`. Pour marquer un autre document, modifiez le chemin d'entrée et l'extension de sortie — GroupDocs.Watermark enregistre dans le format du document d'origine.

## Additional resources
Cette démo fait référence aux [exemples de code](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET/) de GroupDocs.Watermark pour Python via .NET.
