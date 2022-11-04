---
title: PdfSearchableObjects
second_title: GroupDocs.Watermark für .NET-API-Referenz
description: Gibt Flags an die PDFInhaltsobjekte darstellen die in eine Wasserzeichensuche eingeschlossen werden sollen.
type: docs
weight: 2490
url: /de/net/groupdocs.watermark.search.objects/pdfsearchableobjects/
---
## PdfSearchableObjects enumeration

Gibt Flags an, die PDF-Inhaltsobjekte darstellen, die in eine Wasserzeichensuche eingeschlossen werden sollen.

```csharp
[Flags]
public enum PdfSearchableObjects
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Gibt keine Suchobjekte an. |
| XObjects | `1` | Suche in XObjects. |
| Artifacts | `2` | Suche in Artefakten. |
| Annotations | `4` | Suche in Anmerkungen. |
| Text | `8` | Suche im Inhaltstext. |
| Hyperlinks | `10` | Suche in Hyperlinks. |
| AttachedImages | `20` | Suche in angehängten Bildern. |
| All | `3F` | Suche in allen Inhaltsobjekten. |

### Siehe auch

* namensraum [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* Montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->