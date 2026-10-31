---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza della classe PresentationPreviewOptions facendo chiudere lo stream di output."
type: docs
url: /it/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Inizializza una nuova istanza della classe PresentationPreviewOptions facendo chiudere lo stream di output.

```python
def __init__(self, create_page_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Crea uno stream per l'anteprima di una pagina specifica. |

## __init__ {#create_page_stream-release_page_stream}

Inizializza una nuova istanza di [`PresentationPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/) facendo restituire lo stream di output al client per un ulteriore utilizzo.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Crea uno stream per l'anteprima di una pagina specifica. |
| release_page_stream | `ReleasePageStream` | Notifica che la generazione dell'anteprima della pagina è completata e ottiene lo stream di output. |

### Vedi anche
* class [`PresentationPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/)
