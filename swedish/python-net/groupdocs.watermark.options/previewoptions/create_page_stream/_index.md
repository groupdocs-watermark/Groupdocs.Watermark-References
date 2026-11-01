---
title: "create_page_stream egenskap"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Delegaten för skapande av sidström som används för att erhålla ett skrivbart flöde för varje renderad sida."
type: docs
url: /sv/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/
is_root: false
weight: 2010
---


## create_page_stream property

Delegaten för skapande av sidström som används för att erhålla ett skrivbart flöde för varje renderad sida.

GroupDocs.Watermark renderar dokumentsidor som bilder. Tillhandahåll en callable som tar emot ett sidnummer (`int`) och returnerar en skrivbar `io.RawIOBase`-ström; biblioteket skriver den renderade bilden till strömmen och stänger den.

### Definition:
```python
@property
def create_page_stream(self):
    ...
@create_page_stream.setter
def create_page_stream(self, value):
    ...
```

### Se även
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
