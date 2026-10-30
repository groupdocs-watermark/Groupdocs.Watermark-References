---
title: "DiagramShapeWatermarkOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет параметры добавления водяного знака при добавлении формы водяного знака в документ Visio."
type: docs
weight: 1750
url: /ru/net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/
---
## DiagramShapeWatermarkOptions class

Представляет параметры добавления водяного знака при добавлении формы водяного знака в документ Visio.

```csharp
public sealed class DiagramShapeWatermarkOptions : DiagramWatermarkOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DiagramShapeWatermarkOptions](diagramshapewatermarkoptions)() | Инициализирует новый экземпляр класса [`DiagramShapeWatermarkOptions`](../diagramshapewatermarkoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Получает или задает значение, указывающее, запрещено ли редактирование фигуры в Visio. |
| [PlacementType](../../groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/placementtype) { get; set; } | Получает или задает значение, указывающее, на какие страницы следует добавить водяной знак. |

### Примечания

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### Примеры

Добавить защищённый водяной знак на все страницы документа Visio.

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
    options.IsLocked = true;
    options.PlacementType = DiagramWatermarkPlacementType.AllPages; // default

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### См. также

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
