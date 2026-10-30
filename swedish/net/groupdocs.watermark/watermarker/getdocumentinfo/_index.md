---
title: "GetDocumentInfo"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Hämtar information om formatet för det inlästa dokumentet."
type: docs
weight: 70
url: /sv/net/groupdocs.watermark/watermarker/getdocumentinfo/
---
## Watermarker.GetDocumentInfo method

Hämtar information om formatet för det inlästa dokumentet.

```csharp
public IDocumentInfo GetDocumentInfo()
```

### Returvärde

Den [`IDocumentInfo`](../../../groupdocs.watermark.common/idocumentinfo)‑instansen som innehåller upptäckt information.

### Anmärkningar

Läs mer om att hämta dokumentinformationen [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info).

### Exempel

Hämta information om ett dokument av någon stödd typ.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.ppt"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### Se även

* interface [IDocumentInfo](../../../groupdocs.watermark.common/idocumentinfo)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
