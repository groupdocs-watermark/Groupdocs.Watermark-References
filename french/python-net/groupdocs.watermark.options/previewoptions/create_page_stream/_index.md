---
title: "propriété create_page_stream"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Le délégué de création du flux de page utilisé pour obtenir un flux en écriture pour chaque page rendue."
type: docs
url: /fr/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/
is_root: false
weight: 2010
---


## create_page_stream property

Le délégué de création du flux de page utilisé pour obtenir un flux en écriture pour chaque page rendue.

GroupDocs.Watermark rend les pages de document sous forme d'images. Fournissez un callable qui reçoit un numéro de page (`int`) et retourne un flux `io.RawIOBase` inscriptible ; la bibliothèque écrit l'image rendue dans le flux et le ferme.

### Definition:
```python
@property
def create_page_stream(self):
    ...
@create_page_stream.setter
def create_page_stream(self, value):
    ...
```

### Voir aussi
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
