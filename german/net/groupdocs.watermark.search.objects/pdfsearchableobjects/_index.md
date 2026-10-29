---
title: "PdfSearchableObjects"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Gibt Flags an, die PDF‑Inhaltsobjekte repräsentieren und in einer Wasserzeichensuche enthalten sein sollen."
type: docs
weight: 2530
url: /de/net/groupdocs.watermark.search.objects/pdfsearchableobjects/
---
## PdfSearchableObjects enumeration

Gibt Flags an, die PDF‑Inhaltsobjekte repräsentieren und in einer Wasserzeichensuche enthalten sein sollen.

```csharp
[Flags]
public enum PdfSearchableObjects
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Gibt an, dass keine Suchobjekte vorhanden sind. |
| XObjects | `1` | Suche in XObjects. |
| Artifacts | `2` | Suche in Artefakten. |
| Annotations | `4` | Suche in Anmerkungen. |
| Text | `8` | Suche im Inhaltstext. |
| Hyperlinks | `10` | Suche in Hyperlinks. |
| AttachedImages | `20` | Suche in angehängten Bildern. |
| Vector | `40` | Suche in Operatoren. |
| All | `7F` | Suche in allen Inhaltsobjekten. |

### Siehe auch

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
