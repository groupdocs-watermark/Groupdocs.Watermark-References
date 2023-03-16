---
title: PageMarginType
second_title: GroupDocs.Watermark for .NET API-referens
description: Hämtar eller ställer in pdfsidemarginaler som ska användas vid tillägg av vattenstämpel.
type: docs
weight: 20
url: /sv/net/groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype/
---
## PdfContent.PageMarginType property

Hämtar eller ställer in pdf-sidemarginaler som ska användas vid tillägg av vattenstämpel.

```csharp
public PdfPageMarginType PageMarginType { get; set; }
```

### Fastighetsvärde

Marginaler för pdf-sidor som ska användas vid tillägg av vattenstämpel.

### Anmärkningar

Den här egenskapen fungerar endast när[`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) är satt till true. If[`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) är falskt när pdf CropBox används som vattenmärkningsområde.

Standardvärdet ärTrimBox.

### Se även

* enum [PdfPageMarginType](../../pdfpagemargintype)
* class [PdfContent](../../pdfcontent)
* namnutrymme [GroupDocs.Watermark.Contents.Pdf](../../pdfcontent)
* hopsättning [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->