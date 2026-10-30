---
title: "ImageInpaintingPossibleWatermark"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет вручную указанную область изображения, которую следует заполнить методом inpainting, используя окружающие пиксели."
type: docs
weight: 2900
url: /ru/net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/
---
## ImageInpaintingPossibleWatermark class

Представляет вручную заданную область изображения, которую следует заполнить (используя окружающие пиксели).

```csharp
public class ImageInpaintingPossibleWatermark : PossibleWatermark
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageInpaintingPossibleWatermark](imageinpaintingpossiblewatermark)() | Инициализирует новый экземпляр класса [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark). |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [FormattedTextFragments](../../groupdocs.watermark.search/possiblewatermark/formattedtextfragments) { get; } | Получает коллекцию отформатированных текстовых фрагментов этого [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Height](../../groupdocs.watermark.search/possiblewatermark/height) { get; } | Получает высоту этого [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | Получает или задает изображение этого [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| [Method](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/method) { get; set; } | Получает или задает алгоритм inpainting. По умолчанию — PatchBased. |
| virtual [PageNumber](../../groupdocs.watermark.search/possiblewatermark/pagenumber) { get; } | Получает страницу, на которой размещен водяной знак. |
| override [Parent](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/parent) { get; } | Получает родительский объект этого [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark). Всегда возвращает `null`, потому что область указана вручную. |
| [PatchSize](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/patchsize) { get; set; } | Получает или задает размер патча, используемый алгоритмом (нечетный, 5‑11). По умолчанию — 7. Для Telea используется как HalfPatchSize. |
| [Polygons](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/polygons) { get; set; } | Получает или задает полигональные области для inpainting в пикселях изображения. Каждый полигон представляет собой массив вершин. Необходимо указать либо [`Rectangles`](./rectangles), либо [`Polygons`](./polygons), но не оба. |
| [Rectangles](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/rectangles) { get; set; } | Получает или задает прямоугольные области для inpainting в пикселях изображения. Необходимо указать либо [`Rectangles`](./rectangles), либо [`Polygons`](./polygons), но не оба. |
| virtual [RotateAngle](../../groupdocs.watermark.search/possiblewatermark/rotateangle) { get; } | Получает угол поворота этого [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) в градусах. |
| virtual [Text](../../groupdocs.watermark.search/possiblewatermark/text) { get; set; } | Получает или задает текст этого [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [UnitOfMeasurement](../../groupdocs.watermark.search/possiblewatermark/unitofmeasurement) { get; } | Получает единицу измерения этого [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Width](../../groupdocs.watermark.search/possiblewatermark/width) { get; } | Получает ширину этого [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [X](../../groupdocs.watermark.search/possiblewatermark/x) { get; } | Получает координату x этого [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Y](../../groupdocs.watermark.search/possiblewatermark/y) { get; } | Получает координату y этого [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |

### См. также

* class [PossibleWatermark](../../groupdocs.watermark.search/possiblewatermark)
* namespace [GroupDocs.Watermark.Search.Watermarks](../../groupdocs.watermark.search.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
