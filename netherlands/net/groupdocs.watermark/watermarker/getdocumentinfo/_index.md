---
title: "GetDocumentInfo"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Haalt de informatie op over het formaat van het geladen document."
type: docs
weight: 70
url: /nl/net/groupdocs.watermark/watermarker/getdocumentinfo/
---
## Watermarker.GetDocumentInfo method

Haalt de informatie op over het formaat van het geladen document.

```csharp
public IDocumentInfo GetDocumentInfo()
```

### Retourwaarde

De [`IDocumentInfo`](../../../groupdocs.watermark.common/idocumentinfo) instantie die gedetecteerde informatie bevat.

### Opmerkingen

Meer informatie over het ophalen van documentinformatie [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info).

### Voorbeelden

Haal informatie op over een document van elk ondersteund type.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.ppt"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### Zie ook

* interface [IDocumentInfo](../../../groupdocs.watermark.common/idocumentinfo)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
