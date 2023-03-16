---
title: ReleasePageStream
second_title: GroupDocs.Watermark for .NET API-referens
description: Representerar en metod som släpper strömmen som skapats avCreatePageStream./createpagestream delegat.
type: docs
weight: 2090
url: /sv/net/groupdocs.watermark.options/releasepagestream/
---
## ReleasePageStream delegate

Representerar en metod som släpper strömmen som skapats av[`CreatePageStream`](../createpagestream) delegat.

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | Int32 | Sidnumret för en genererad förhandsvisning av sidan. |
| pageStream | Stream | Strömmen som innehåller den genererade förhandsvisningen av sidan. |

### Se även

* namnutrymme [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* hopsättning [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->