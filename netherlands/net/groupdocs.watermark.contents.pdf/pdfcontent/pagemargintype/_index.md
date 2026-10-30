---
title: "PageMarginType"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Haalt op of stelt pdf-paginamarges in die worden gebruikt tijdens het toevoegen van een watermerk."
type: docs
weight: 20
url: /nl/net/groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype/
---
## PdfContent.PageMarginType property

Haalt op of stelt pdf-paginamarges in die worden gebruikt tijdens het toevoegen van een watermerk.

```csharp
public PdfPageMarginType PageMarginType { get; set; }
```

### Property Value

Pdf-paginamarges die gebruikt worden tijdens het toevoegen van een watermerk.

### Opmerkingen

Deze eigenschap werkt alleen wanneer [`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) is ingesteld op true. Als [`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) false is, wordt de pdf CropBox gebruikt als watermerkgebied.

De standaardwaarde is TrimBox.

### Zie ook

* enum [PdfPageMarginType](../../pdfpagemargintype)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
