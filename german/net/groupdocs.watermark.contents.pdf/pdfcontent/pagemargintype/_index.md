---
title: "PageMarginType"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Liest oder setzt die PDF-Seitenränder, die beim Hinzufügen von Wasserzeichen verwendet werden."
type: docs
weight: 20
url: /de/net/groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype/
---
## PdfContent.PageMarginType property

Liest oder setzt die PDF-Seitenränder, die beim Hinzufügen von Wasserzeichen verwendet werden.

```csharp
public PdfPageMarginType PageMarginType { get; set; }
```

### Property Value

Pdf-Seitenränder, die beim Hinzufügen von Wasserzeichen verwendet werden.

### Hinweise

Diese Eigenschaft funktioniert nur, wenn [`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) auf true gesetzt ist. Wenn [`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) false ist, wird die PDF‑CropBox als Wasserzeichenbereich verwendet.

Der Standardwert ist TrimBox.

### Siehe auch

* enum [PdfPageMarginType](../../pdfpagemargintype)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
