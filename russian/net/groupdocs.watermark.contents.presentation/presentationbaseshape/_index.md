---
title: "PresentationBaseShape"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Предоставляет абстрактный базовый класс для фигур всех типов в документе PowerPoint."
type: docs
weight: 860
url: /ru/net/groupdocs.watermark.contents.presentation/presentationbaseshape/
---
## PresentationBaseShape class

Предоставляет абстрактный базовый класс для фигур всех типов в документе PowerPoint.

```csharp
public abstract class PresentationBaseShape : ShapeSearchAdapter, IPresentationHyperlinkContainer, 
    ITwoDObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.contents.presentation/presentationbaseshape/alternativetext) { get; set; } | Получает или задает описательный (альтернативный) текст, связанный с этой [`PresentationBaseShape`](../presentationbaseshape). |
| [Height](../../groupdocs.watermark.contents.presentation/presentationbaseshape/height) { get; set; } | Получает или задает высоту этой [`PresentationBaseShape`](../presentationbaseshape) в пунктах. |
| [Id](../../groupdocs.watermark.contents.presentation/presentationbaseshape/id) { get; } | Получает идентификатор этой [`PresentationBaseShape`](../presentationbaseshape). |
| [ImageFillFormat](../../groupdocs.watermark.contents.presentation/presentationbaseshape/imagefillformat) { get; } | Получает настройки формата заливки изображением этой [`PresentationBaseShape`](../presentationbaseshape). |
| [Name](../../groupdocs.watermark.contents.presentation/presentationbaseshape/name) { get; } | Получает имя этой [`PresentationBaseShape`](../presentationbaseshape). |
| [Presentation](../../groupdocs.watermark.contents.presentation/presentationbaseshape/presentation) { get; } | Получает родительскую презентацию этой [`PresentationBaseShape`](../presentationbaseshape). |
| [Width](../../groupdocs.watermark.contents.presentation/presentationbaseshape/width) { get; set; } | Получает или задает ширину этого [`PresentationBaseShape`](../presentationbaseshape) в пунктах. |
| [X](../../groupdocs.watermark.contents.presentation/presentationbaseshape/x) { get; set; } | Получает или задает горизонтальное смещение этого [`PresentationBaseShape`](../presentationbaseshape) от левого края презентации в пунктах. |
| [Y](../../groupdocs.watermark.contents.presentation/presentationbaseshape/y) { get; set; } | Получает или задает вертикальное смещение этого [`PresentationBaseShape`](../presentationbaseshape) от верхнего края презентации в пунктах. |
| [ZOrderPosition](../../groupdocs.watermark.contents.presentation/presentationbaseshape/zorderposition) { get; } | Получает позицию этого [`PresentationBaseShape`](../presentationbaseshape) в порядке Z. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetHyperlink](../../groupdocs.watermark.contents.presentation/presentationbaseshape/gethyperlink)(PresentationHyperlinkActionType) | Получает гиперссылку, связанную с этим [`PresentationBaseShape`](../presentationbaseshape). |
| [SetHyperlink](../../groupdocs.watermark.contents.presentation/presentationbaseshape/sethyperlink)(PresentationHyperlinkActionType, string) | Задает гиперссылку, связанную с этим [`PresentationBaseShape`](../presentationbaseshape). |

### См. также

* class [ShapeSearchAdapter](../../groupdocs.watermark.search/shapesearchadapter)
* interface [IPresentationHyperlinkContainer](../ipresentationhyperlinkcontainer)
* interface [ITwoDObject](../../groupdocs.watermark.search/itwodobject)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
