---
title: ReleasePageStream
second_title: GroupDocs.Watermark voor .NET API-referentie
description: Vertegenwoordigt een methode die de stream vrijgeeft die is gemaakt door deCreatePageStream./createpagestream delegeren.
type: docs
weight: 2090
url: /nl/net/groupdocs.watermark.options/releasepagestream/
---
## ReleasePageStream delegate

Vertegenwoordigt een methode die de stream vrijgeeft die is gemaakt door de[`CreatePageStream`](../createpagestream) delegeren.

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageNumber | Int32 | Het paginanummer van een gegenereerd paginavoorbeeld. |
| pageStream | Stream | De stream met het gegenereerde paginavoorbeeld. |

### Zie ook

* naamruimte [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
