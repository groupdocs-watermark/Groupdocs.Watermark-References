---
title: "ReleasePageStream"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar en metod som frigör strömmen som skapats av delegaten CreatePageStream./createpagestream."
type: docs
weight: 2160
url: /sv/net/groupdocs.watermark.options/releasepagestream/
---
## ReleasePageStream delegate

Representerar en metod som frigör strömmen som skapats av delegaten [`CreatePageStream`](../createpagestream).

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | Int32 | Sidnumret för en genererad sidförhandsgranskning. |
| pageStream | Stream | Strömmen som innehåller den genererade sidförhandsgranskningen. |

### Se även

* namespace [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
