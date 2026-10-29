---
title: "PageMarginType"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Obtient ou définit les marges de page pdf à utiliser lors de l'ajout de filigrane."
type: docs
weight: 20
url: /fr/net/groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype/
---
## PdfContent.PageMarginType property

Obtient ou définit les marges de page pdf à utiliser lors de l'ajout de filigrane.

```csharp
public PdfPageMarginType PageMarginType { get; set; }
```

### Property Value

Marges de page PDF à utiliser lors de l'ajout de filigrane.

### Remarques

Cette propriété ne fonctionne que lorsque [`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) est définie sur true. Si [`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) est false, lorsque le CropBox du PDF est utilisé comme zone de filigrane.

La valeur par défaut est TrimBox.

### Voir aussi

* enum [PdfPageMarginType](../../pdfpagemargintype)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
