---
title: "set_license Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Wenden Sie eine Lizenz auf den aktuellen Prozess an."
type: docs
url: /de/python-net/groupdocs.watermark/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Wenden Sie eine Lizenz auf den aktuellen Prozess an.

```python
def set_license(self, license_source):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| license_source |  | Entweder ein Zeichenkettenpfad zu einer ``.lic``-Datei oder ein lesbares file‑like‑Objekt, das die Lizenzbytes liefert. File‑like‑Eingaben werden in eine temporäre Datei geschrieben, bevor sie an die Bridge übergeben werden. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `TypeError` | Falls ``license_source`` weder ein Zeichenkettenpfad noch ein lesbares file‑like‑Objekt ist. |

### Siehe auch
* class [`License`](/watermark/python-net/groupdocs.watermark/license/)
