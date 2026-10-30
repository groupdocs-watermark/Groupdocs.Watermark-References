---
title: "MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет параметры добавления водяного знака при добавлении его в многокадровое изображение."
type: docs
weight: 1870
url: /ru/net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/
---
## MultiframeImageWatermarkOptions class

Представляет параметры добавления водяного знака при добавлении водяного знака к многокадровому изображению.

```csharp
public class MultiframeImageWatermarkOptions : WatermarkOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor)() | Инициализирует новый экземпляр класса [`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions). |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor_1)(int) | Инициализирует новый экземпляр класса [`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions) с указанным индексом кадра. |

## Свойства

| Имя | Описание |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Получает или задает индекс кадра для добавления водяного знака. |

### Примечания

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Примеры

Добавить водяной знак в определённый кадр многокадрового изображения.

```csharp
ImageLoadOptions loadOptions = new ImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.gif", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    MultiframeImageWatermarkOptions options = new MultiframeImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### См. также

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
