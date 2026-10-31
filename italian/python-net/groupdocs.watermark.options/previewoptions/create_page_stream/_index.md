---
title: "proprietà create_page_stream"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Il delegato di creazione dello stream di pagina usato per ottenere uno stream scrivibile per ogni pagina renderizzata."
type: docs
url: /it/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/
is_root: false
weight: 2010
---


## create_page_stream property

Il delegato di creazione dello stream di pagina usato per ottenere uno stream scrivibile per ogni pagina renderizzata.

GroupDocs.Watermark rende le pagine dei documenti come immagini. Fornisci un callable che riceve un numero di pagina (`int`) e restituisce uno stream scrivibile `io.RawIOBase`; la libreria scrive l'immagine renderizzata nello stream e lo chiude.

### Definition:
```python
@property
def create_page_stream(self):
    ...
@create_page_stream.setter
def create_page_stream(self, value):
    ...
```

### Vedi anche
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
