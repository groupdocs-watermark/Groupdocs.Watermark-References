---
title: "PdfShape"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Предоставляет базовый класс для артефактов XObjects и аннотаций."
type: docs
weight: 770
url: /ru/net/groupdocs.watermark.contents.pdf/pdfshape/
---
## PdfShape class

Предоставляет базовый класс для XObjects, Artifacts и Annotations.

```csharp
public abstract class PdfShape : ShapeSearchAdapter, IRotatableTwoDObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| [FormattedTextFragments](../../groupdocs.watermark.contents.pdf/pdfshape/formattedtextfragments) { get; } | Получает коллекцию отформатированных текстовых фрагментов этого [`PdfShape`](../pdfshape). |
| abstract [Height](../../groupdocs.watermark.contents.pdf/pdfshape/height) { get; } | Получает высоту объекта. |
| [Image](../../groupdocs.watermark.contents.pdf/pdfshape/image) { get; set; } | Получает или задает изображение этого [`PdfShape`](../pdfshape). |
| abstract [RotateAngle](../../groupdocs.watermark.contents.pdf/pdfshape/rotateangle) { get; } | Получает угол поворота объекта в градусах. |
| virtual [Text](../../groupdocs.watermark.contents.pdf/pdfshape/text) { get; set; } | Получает или задает текст этого [`PdfShape`](../pdfshape). |
| abstract [Width](../../groupdocs.watermark.contents.pdf/pdfshape/width) { get; } | Получает ширину объекта. |
| abstract [X](../../groupdocs.watermark.contents.pdf/pdfshape/x) { get; } | Получает координату x объекта. |
| abstract [Y](../../groupdocs.watermark.contents.pdf/pdfshape/y) { get; } | Получает координату y объекта. |

### См. также

* class [ShapeSearchAdapter](../../groupdocs.watermark.search/shapesearchadapter)
* interface [IRotatableTwoDObject](../../groupdocs.watermark.search/irotatabletwodobject)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
