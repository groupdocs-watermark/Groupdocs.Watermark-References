---
title: "create_page_stream Eigenschaft"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Der Delegat zur Erstellung des Seitenstreams, der verwendet wird, um für jede gerenderte Seite einen beschreibbaren Stream zu erhalten."
type: docs
url: /de/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/
is_root: false
weight: 2010
---


## create_page_stream property

Der Delegat zur Erstellung des Seitenstreams, der verwendet wird, um für jede gerenderte Seite einen beschreibbaren Stream zu erhalten.

GroupDocs.Watermark rendert Dokumentseiten als Bilder. Stellen Sie ein Callable bereit, das eine Seitennummer (`int`) empfängt und einen beschreibbaren `io.RawIOBase`-Stream zurückgibt; die Bibliothek schreibt das gerenderte Bild in den Stream und schließt ihn.

### Definition:
```python
@property
def create_page_stream(self):
    ...
@create_page_stream.setter
def create_page_stream(self, value):
    ...
```

### Siehe auch
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
