---
title: "Ciao, Mondo!"
linkTitle: "Hello, World!"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizia rapidamente con GroupDocs.Watermark per Python via .NET creando ed eseguendo un semplice esempio."
type: docs
url: /it/python-net/guides/hello-world/
is_root: false
weight: 20
---


## Introduction
Un esempio "Hello, World!" è spesso il primo passo quando si esplora GroupDocs.Watermark per Python via .NET. Serve come un semplice test per confermare che l'ambiente di sviluppo sia configurato correttamente e che la libreria funzioni come previsto.

## Overview
GroupDocs.Watermark per Python via .NET ti consente di aggiungere, cercare e rimuovere filigrane in vari formati di documento. Un'ampia gamma di [supported formats](https://docs.groupdocs.com/watermark/python-net/getting-started/supported-document-formats/) lo rende versatile per diversi casi d'uso.

## How to add a watermark
I passaggi seguenti dimostrano come aggiungere una filigrana di testo a un documento utilizzando GroupDocs.Watermark per Python via .NET:

1. Importa le classi `groupdocs.watermark` di cui hai bisogno.
2. Apri un [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) con il percorso del documento di esempio.
3. Crea un [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) con il testo e il font desiderati e stilizzalo.
4. Applica la filigrana con `add()`.
5. Salva il risultato.

## Complete example
L'esempio seguente aggiunge una filigrana di testo "Hello, Watermark!" semi-trasparente e diagonale e salva il risultato:

{{< tabs "code-example-hello-world" >}}
{{< tab "hello_world.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

def hello_world():
    # Apri il documento, aggiungi una singola filigrana di testo e salva il risultato
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
{{< tab "sample.pdf" >}}

`sample.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/watermark/python-net/_sample_files/getting-started/hello-world/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 315 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/getting-started/hello-world/hello_world/output.pdf)
{{< /tab >}}
{{< /tabs >}}

La filigrana viene salvata nuovamente nello stesso formato PDF di `output.pdf`. Per applicare una filigrana a un documento diverso, modifica il percorso di input e l'estensione di output — GroupDocs.Watermark salva nel formato del documento di input.

## Additional resources
Questa demo fa riferimento ai [campioni di codice](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET/) di GroupDocs.Watermark per Python via .NET.
