---
title: "PageMarginType"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Получает или задает поля страниц pdf, используемые при добавлении водяного знака."
type: docs
weight: 20
url: /ru/net/groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype/
---
## PdfContent.PageMarginType property

Получает или задает поля страниц pdf, используемые при добавлении водяного знака.

```csharp
public PdfPageMarginType PageMarginType { get; set; }
```

### Property Value

Поля PDF‑страницы, используемые при добавлении водяного знака.

### Примечания

Это свойство работает только когда [`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) установлено в true. Если [`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) равно false, используется pdf CropBox в качестве области для водяного знака.

Значение по умолчанию — TrimBox.

### См. также

* enum [PdfPageMarginType](../../pdfpagemargintype)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
