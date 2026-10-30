---
title: "IDocumentInfo"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Definierar de metoder som krävs för att hämta grundläggande dokumentinformation."
type: docs
weight: 70
url: /sv/net/groupdocs.watermark.common/idocumentinfo/
---
## IDocumentInfo interface

Definierar de metoder som krävs för att hämta grundläggande dokumentinformation.

```csharp
public interface IDocumentInfo
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FileType](../../groupdocs.watermark.common/idocumentinfo/filetype) { get; } | Hämtar beskrivningen av filformatet. |
| [IsEncrypted](../../groupdocs.watermark.common/idocumentinfo/isencrypted) { get; } | Hämtar ett värde som indikerar om dokumentet är krypterat och kräver ett lösenord för att öppnas. |
| [PageCount](../../groupdocs.watermark.common/idocumentinfo/pagecount) { get; } | Hämtar det totala antalet sidor. |
| [Pages](../../groupdocs.watermark.common/idocumentinfo/pages) { get; } | Hämtar samlingen av beskrivningar av dokumentets sidor. |
| [Size](../../groupdocs.watermark.common/idocumentinfo/size) { get; } | Hämtar dokumentets storlek i byte. |

### Anmärkningar

**Learn more**

* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Exempel

Följande exempel visar hur man hämtar den allmänna dokumentinformationen med hjälp av [`IDocumentInfo`](../idocumentinfo).

```csharp
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### Se även

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
