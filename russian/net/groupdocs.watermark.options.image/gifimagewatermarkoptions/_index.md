---
title: "GifImageWatermarkOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет параметры добавления водяного знака при добавлении его к GIF‑изображению."
type: docs
weight: 1830
url: /ru/net/groupdocs.watermark.options.image/gifimagewatermarkoptions/
---
## GifImageWatermarkOptions class

Представляет параметры добавления водяного знака при добавлении его к GIF‑изображению.

```csharp
public sealed class GifImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor)() | Инициализирует новый экземпляр класса [`GifImageWatermarkOptions`](../gifimagewatermarkoptions). |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor_1)(int) | Инициализирует новый экземпляр класса [`GifImageWatermarkOptions`](../gifimagewatermarkoptions) с указанным индексом кадра. |

## Свойства

| Имя | Описание |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Получает или задает индекс кадра для добавления водяного знака. |

### Примечания

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Примеры

Добавьте водяной знак в определённый кадр GIF‑изображения.

```csharp
GifImageLoadOptions loadOptions = new GifImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.gif", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    GifImageWatermarkOptions options = new GifImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### См. также

* class [MultiframeImageWatermarkOptions](../multiframeimagewatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
