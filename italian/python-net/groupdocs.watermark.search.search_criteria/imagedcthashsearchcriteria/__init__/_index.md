---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza di ImageDctHashSearchCriteria con un percorso file specificato."
type: docs
url: /it/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Inizializza una nuova istanza di ImageDctHashSearchCriteria con un percorso file specificato.

```python
def __init__(self, file_path):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file da cui caricare l'immagine. |

### Esempio

```python
    from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

    criteria = ImageDctHashSearchCriteria("./logo.png")
    ```

## __init__ {#stream}

Inizializza una nuova istanza di ImageDctHashSearchCriteria con lo stream immagine fornito.

```python
def __init__(self, stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | `io.RawIOBase` | Il flusso da cui caricare l'immagine. |

### Vedi anche
* class [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)
