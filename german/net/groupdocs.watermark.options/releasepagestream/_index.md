---
title: "ReleasePageStream"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt eine Methode dar, die den von dem CreatePageStream./createpagestream-Delegaten erstellten Stream freigibt."
type: docs
weight: 2160
url: /de/net/groupdocs.watermark.options/releasepagestream/
---
## ReleasePageStream delegate

Stellt eine Methode dar, die den von dem [`CreatePageStream`](../createpagestream)-Delegaten erstellten Stream freigibt.

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Die Seitenzahl einer erzeugten Seitenvorschau. |
| pageStream | Stream | Der Stream, der die erzeugte Seitenvorschau enthält. |

### Siehe auch

* namespace [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
