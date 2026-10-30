---
title: "ReleasePageStream"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een methode voor die de door de CreatePageStream./createpagestream delegate gemaakte stream vrijgeeft."
type: docs
weight: 2160
url: /nl/net/groupdocs.watermark.options/releasepagestream/
---
## ReleasePageStream delegate

Stelt een methode voor die de door de [`CreatePageStream`](../createpagestream) delegate gemaakte stream vrijgeeft.

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageNumber | Int32 | Het paginanummer van een gegenereerde paginavoorbeeld. |
| pageStream | Stream | De stream die de gegenereerde paginavoorbeeld bevat. |

### Zie ook

* namespace [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
