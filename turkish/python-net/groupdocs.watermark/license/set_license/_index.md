---
title: "set_license yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Mevcut sürece bir lisans uygula."
type: docs
url: /tr/python-net/groupdocs.watermark/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Mevcut sürece bir lisans uygula.

```python
def set_license(self, license_source):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| license_source |  | Bir ``.lic`` dosyasına giden dize yolu ya da lisans baytlarını sağlayan okunabilir bir dosya benzeri nesne. Dosya benzeri girdiler, köprüye aktarılmadan önce geçici bir dosyaya yazılır. |

| Yükseltir | Açıklama |
| :- | :- |
| `TypeError` | Eğer ``license_source`` bir dize yolu ya da okunabilir bir dosya benzeri nesne değilse. |

### Ayrıca Bakınız
* class [`License`](/watermark/python-net/groupdocs.watermark/license/)
