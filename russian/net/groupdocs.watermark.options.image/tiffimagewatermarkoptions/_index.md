---
title: "TiffImageWatermarkOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет параметры добавления водяного знака при добавлении водяного знака к TIFF‑изображению."
type: docs
weight: 1900
url: /ru/net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/
---
## TiffImageWatermarkOptions class

Представляет параметры добавления водяного знака при добавлении водяного знака к TIFF‑изображению.

```csharp
public sealed class TiffImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor)() | Инициализирует новый экземпляр класса [`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions). |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor_1)(int) | Инициализирует новый экземпляр класса [`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions) с указанным индексом кадра. |

## Свойства

| Имя | Описание |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Получает или задает индекс кадра для добавления водяного знака. |

### Примечания

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Примеры

Добавьте водяной знак в определённый кадр TIFF‑изображения.

```csharp
TiffImageLoadOptions loadOptions = new TiffImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.tiff", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    TiffImageWatermarkOptions options = new TiffImageWatermarkOptions();
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
