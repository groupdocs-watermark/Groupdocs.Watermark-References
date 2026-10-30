---
title: "PageMarginType"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Ottiene o imposta i margini della pagina pdf da utilizzare durante l'aggiunta della filigrana."
type: docs
weight: 20
url: /it/net/groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype/
---
## PdfContent.PageMarginType property

Ottiene o imposta i margini della pagina pdf da utilizzare durante l'aggiunta della filigrana.

```csharp
public PdfPageMarginType PageMarginType { get; set; }
```

### Property Value

Margini della pagina PDF da utilizzare durante l'aggiunta della filigrana.

### Osservazioni

Questa proprietà funziona solo quando [`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) è impostata su true. Se [`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) è false, quando il CropBox PDF è usato come area di filigrana.

Il valore predefinito è TrimBox.

### Vedi anche

* enum [PdfPageMarginType](../../pdfpagemargintype)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
