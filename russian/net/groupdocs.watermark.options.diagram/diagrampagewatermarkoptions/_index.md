---
title: "DiagramPageWatermarkOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет параметры добавления водяного знака при добавлении формы водяного знака на определённую страницу документа Visio."
type: docs
weight: 1720
url: /ru/net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/
---
## DiagramPageWatermarkOptions class

Представляет параметры добавления водяного знака при добавлении формы водяного знака на определённую страницу документа Visio.

```csharp
public sealed class DiagramPageWatermarkOptions : DiagramWatermarkOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DiagramPageWatermarkOptions](diagrampagewatermarkoptions)() | Инициализирует новый экземпляр класса [`DiagramPageWatermarkOptions`](../diagrampagewatermarkoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Получает или задает значение, указывающее, запрещено ли редактирование фигуры в Visio. |
| [PageIndex](../../groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/pageindex) { get; set; } | Получает или задает индекс страницы, к которой будет добавлен водяной знак. |

### Примечания

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### Примеры

Добавить защищённый водяной знак на первую страницу документа Visio.

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
    options.IsLocked = true;
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### См. также

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
