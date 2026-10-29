---
title: "FromExtension"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Ordnet die Dateierweiterung dem Dateityp zu."
type: docs
weight: 590
url: /de/net/groupdocs.watermark.common/filetype/fromextension/
---
## FileType.FromExtension method

Ordnet die Dateierweiterung dem Dateityp zu.

```csharp
public static FileType FromExtension(string extension)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Erweiterung | String | Die Dateierweiterung (einschließlich des Punktes "."). |

### Rückgabewert

Wenn der Dateityp unterstützt wird, wird er zurückgegeben, andernfalls wird der Standard‑[`Unknown`](../unknown)‑Dateityp zurückgegeben.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *extension* null oder ein leerer String ist. |

### Siehe auch

* class [FileType](../../filetype)
* namespace [GroupDocs.Watermark.Common](../../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
