---
title: "create_page_stream eigenschap"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "De delegate voor het maken van paginastromen die wordt gebruikt om een beschrijfbare stroom voor elke gerenderde pagina te verkrijgen."
type: docs
url: /nl/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/
is_root: false
weight: 2010
---


## create_page_stream property

De delegate voor het maken van paginastromen die wordt gebruikt om een beschrijfbare stroom voor elke gerenderde pagina te verkrijgen.

GroupDocs.Watermark rendert documentpagina's als afbeeldingen. Lever een callable die een paginanummer (`int`) ontvangt en een beschrijfbare `io.RawIOBase` stream retourneert; de bibliotheek schrijft de gerenderde afbeelding naar de stream en sluit deze.

### Definition:
```python
@property
def create_page_stream(self):
    ...
@create_page_stream.setter
def create_page_stream(self, value):
    ...
```

### Zie ook
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
