---
title: "méthode set_license"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Appliquer une licence au processus actuel."
type: docs
url: /fr/python-net/groupdocs.watermark/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Appliquer une licence au processus actuel.

```python
def set_license(self, license_source):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| license_source |  | Peut être un chemin de chaîne vers un fichier ``.lic`` ou un objet de type fichier lisible qui fournit les octets de licence. Les entrées de type fichier sont écrites dans un fichier temporaire avant d'être transmises au pont. |

| Lève | Description |
| :- | :- |
| `TypeError` | Si ``license_source`` n'est ni un chemin de chaîne ni un objet de type fichier lisible. |

### Voir aussi
* class [`License`](/watermark/python-net/groupdocs.watermark/license/)
