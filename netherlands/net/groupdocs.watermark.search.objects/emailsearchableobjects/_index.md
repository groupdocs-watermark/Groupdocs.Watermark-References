---
title: "EmailSearchableObjects"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Specificeert vlaggen die e-mailberichtobjecten vertegenwoordigen die moeten worden opgenomen in een watermerkzoekopdracht."
type: docs
weight: 2520
url: /nl/net/groupdocs.watermark.search.objects/emailsearchableobjects/
---
## EmailSearchableObjects enumeration

Specificeert vlaggen die e-mailberichtobjecten vertegenwoordigen die moeten worden opgenomen in een watermerkzoekopdracht.

```csharp
[Flags]
public enum EmailSearchableObjects
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | `0` | Specificeert geen zoekobjecten. |
| Subject | `1` | Zoek in onderwerp van het bericht. |
| PlainTextBody | `2` | Zoek in platte-tekst body van bericht. |
| HtmlBody | `4` | Zoek in HTML-body van bericht. |
| AttachedImages | `8` | Zoek in bijgevoegde afbeeldingen. |
| EmbeddedImages | `10` | Zoek in ingesloten afbeeldingen. |
| All | `1F` | Zoek in alle e-mailobjecten. |

### Zie ook

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
