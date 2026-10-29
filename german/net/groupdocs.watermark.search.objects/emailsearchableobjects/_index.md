---
title: "EmailSearchableObjects"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Gibt Flags an, die E‑Mail‑Nachrichtenobjekte repräsentieren und in einer Wasserzeichensuche enthalten sein sollen."
type: docs
weight: 2520
url: /de/net/groupdocs.watermark.search.objects/emailsearchableobjects/
---
## EmailSearchableObjects enumeration

Gibt Flags an, die E‑Mail‑Nachrichtenobjekte repräsentieren und in einer Wasserzeichensuche enthalten sein sollen.

```csharp
[Flags]
public enum EmailSearchableObjects
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Gibt an, dass keine Suchobjekte vorhanden sind. |
| Subject | `1` | Suche im Betreff der Nachricht. |
| PlainTextBody | `2` | Suche im Nur-Text-Body der Nachricht. |
| HtmlBody | `4` | Suche im HTML-Body der Nachricht. |
| AttachedImages | `8` | Suche in angehängten Bildern. |
| EmbeddedImages | `10` | Suche in eingebetteten Bildern. |
| All | `1F` | Suche in allen E-Mail-Objekten. |

### Siehe auch

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
