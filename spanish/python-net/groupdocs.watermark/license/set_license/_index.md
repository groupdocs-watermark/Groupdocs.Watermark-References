---
title: "método set_license"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Aplica una licencia al proceso actual."
type: docs
url: /es/python-net/groupdocs.watermark/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Aplica una licencia al proceso actual.

```python
def set_license(self, license_source):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| license_source |  | Una ruta de cadena a un archivo ``.lic`` o un objeto similar a un archivo legible que devuelva los bytes de la licencia. Las entradas tipo archivo se escriben en un archivo temporal antes de ser pasadas al puente. |

| Lanza | Descripción |
| :- | :- |
| `TypeError` | Si ``license_source`` no es ni una ruta de cadena ni un objeto similar a un archivo legible. |

### Ver también
* class [`License`](/watermark/python-net/groupdocs.watermark/license/)
