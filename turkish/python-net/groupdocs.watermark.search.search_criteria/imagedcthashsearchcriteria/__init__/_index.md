---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belirtilen dosya yolu ile yeni bir ImageDctHashSearchCriteria örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Belirtilen dosya yolu ile yeni bir ImageDctHashSearchCriteria örneği başlatır.

```python
def __init__(self, file_path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Görüntünün yükleneceği dosya yolu. |

### Örnek

```python
    from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

    criteria = ImageDctHashSearchCriteria("./logo.png")
    ```

## __init__ {#stream}

Sağlanan görüntü akışı ile yeni bir ImageDctHashSearchCriteria örneği başlatır.

```python
def __init__(self, stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | `io.RawIOBase` | Görüntünün yükleneceği akış. |

### Ayrıca Bakınız
* class [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)
