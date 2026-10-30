---
title: "PageMarginType"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Hämtar eller anger pdf-sidmarginaler som ska användas vid tillägg av vattenmärke."
type: docs
weight: 20
url: /sv/net/groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype/
---
## PdfContent.PageMarginType property

Hämtar eller anger pdf-sidmarginaler som ska användas vid tillägg av vattenmärke.

```csharp
public PdfPageMarginType PageMarginType { get; set; }
```

### Property Value

Pdf-sidmarginaler som ska användas vid tillägg av vattenstämpel.

### Anmärkningar

Denna egenskap fungerar endast när [`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) är satt till true. Om [`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) är false, när pdf CropBox används som vattenstämpelområde.

Standardvärdet är TrimBox.

### Se även

* enum [PdfPageMarginType](../../pdfpagemargintype)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
