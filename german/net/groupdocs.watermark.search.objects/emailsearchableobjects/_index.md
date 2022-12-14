---
title: EmailSearchableObjects
second_title: GroupDocs.Watermark für .NET-API-Referenz
description: Gibt Flags an die EMailNachrichtenobjekte darstellen die in eine Wasserzeichensuche eingeschlossen werden sollen.
type: docs
weight: 2480
url: /de/net/groupdocs.watermark.search.objects/emailsearchableobjects/
---
## EmailSearchableObjects enumeration

Gibt Flags an, die E-Mail-Nachrichtenobjekte darstellen, die in eine Wasserzeichensuche eingeschlossen werden sollen.

```csharp
[Flags]
public enum EmailSearchableObjects
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Gibt keine Suchobjekte an. |
| Subject | `1` | Im Betreff der Nachricht suchen. |
| PlainTextBody | `2` | Suche im Klartexttext der Nachricht. |
| HtmlBody | `4` | Suche im HTML-Text der Nachricht. |
| AttachedImages | `8` | Suche in angehängten Bildern. |
| EmbeddedImages | `10` | Suche in eingebetteten Bildern. |
| All | `1F` | Suche in allen E-Mail-Objekten. |

### Siehe auch

* namensraum [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* Montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
