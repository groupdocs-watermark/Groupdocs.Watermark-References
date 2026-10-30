---
title: "ShapePossibleWatermarkT"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет форму водяного знака в содержимом любого поддерживаемого формата."
type: docs
weight: 2770
url: /ru/net/groupdocs.watermark.search/shapepossiblewatermark-1/
---
## ShapePossibleWatermark&lt;T&gt; class

Представляет форму водяного знака в содержимом любого поддерживаемого формата.

```csharp
public abstract class ShapePossibleWatermark<T> : TwoDObjectPossibleWatermark
    where T : ShapeSearchAdapter, ITwoDObject
```

| Параметр | Описание |
| --- | --- |
| T | Тип фигуры. |

## Свойства

| Имя | Описание |
| --- | --- |
| override [FormattedTextFragments](../../groupdocs.watermark.search/shapepossiblewatermark-1/formattedtextfragments) { get; } | Получает коллекцию отформатированных текстовых фрагментов формы. |
| override [Height](../../groupdocs.watermark.search/twodobjectpossiblewatermark/height) { get; } | Получает высоту 2D-объекта. |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | Получает или задает изображение этого [`PossibleWatermark`](../possiblewatermark). |
| override [PageNumber](../../groupdocs.watermark.search/shapepossiblewatermark-1/pagenumber) { get; } | Получает страницу, на которой размещен водяной знак. |
| abstract [Parent](../../groupdocs.watermark.search/possiblewatermark/parent) { get; } | Получает родителя этого [`PossibleWatermark`](../possiblewatermark). |
| override [RotateAngle](../../groupdocs.watermark.search/shapepossiblewatermark-1/rotateangle) { get; } | Получает угол поворота формы в градусах. |
| override [Text](../../groupdocs.watermark.search/shapepossiblewatermark-1/text) { get; set; } | Получает или задает текст формы. |
| override [UnitOfMeasurement](../../groupdocs.watermark.search/twodobjectpossiblewatermark/unitofmeasurement) { get; } | Получает единицу измерения 2D-объекта. |
| override [Width](../../groupdocs.watermark.search/twodobjectpossiblewatermark/width) { get; } | Получает ширину 2D-объекта. |
| override [X](../../groupdocs.watermark.search/twodobjectpossiblewatermark/x) { get; } | Получает координату x 2D-объекта. |
| override [Y](../../groupdocs.watermark.search/twodobjectpossiblewatermark/y) { get; } | Получает координату y 2D-объекта. |

### См. также

* class [TwoDObjectPossibleWatermark](../twodobjectpossiblewatermark)
* class [ShapeSearchAdapter](../shapesearchadapter)
* interface [ITwoDObject](../itwodobject)
* namespace [GroupDocs.Watermark.Search](../../groupdocs.watermark.search)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
