---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "PagesSetup sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.watermarks/pagessetup/__init__/
is_root: false
weight: 10
---


## __init__

Yeni bir [`PagesSetup`](/watermark/python-net/groupdocs.watermark.watermarks/pagessetup/) sınıfı örneği başlatır.

```python
def __init__(self):
    ...
```

## __init__ {#all_pages-first_page-last_page-odd_pages-even_pages-pages-page_number}

Belirtilen parametrelerle yeni bir PagesSetup örneği başlatır.

```python
def __init__(self, all_pages, first_page, last_page, odd_pages, even_pages, pages, page_number):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| all_pages | `bool` | Tüm sayfaları dahil edip etmeyeceği. |
| first_page | `bool` | İlk sayfayı dahil edip etmeyeceği. |
| last_page | `bool` | Son sayfayı dahil edip etmeyeceği. |
| odd_pages | `bool` | Tek sayfaları dahil edip etmeyeceği. |
| even_pages | `bool` | Çift sayfaları dahil edip etmeyeceği. |
| pages | `List[int]` | Dahil edilecek belirli sayfa numaralarının listesi. |
| page_number | `Optional[int]` | Mevcut sayfanın indeksi. |

### Ayrıca Bakınız
* class [`PagesSetup`](/watermark/python-net/groupdocs.watermark.watermarks/pagessetup/)
