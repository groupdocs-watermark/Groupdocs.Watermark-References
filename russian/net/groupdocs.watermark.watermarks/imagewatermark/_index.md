---
title: "ImageWatermark"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет изображение водяного знака."
type: docs
weight: 3190
url: /ru/net/groupdocs.watermark.watermarks/imagewatermark/
---
## ImageWatermark class

Представляет изображение водяного знака.

```csharp
public sealed class ImageWatermark : Watermark, IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageWatermark](imagewatermark#constructor)(Stream) | Инициализирует новый экземпляр класса [`ImageWatermark`](../imagewatermark) с указанным потоком. |
| [ImageWatermark](imagewatermark#constructor_1)(string) | Инициализирует новый экземпляр класса [`ImageWatermark`](../imagewatermark) с указанным путём к файлу. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Получает или задает значение, указывающее, рассчитываются ли размер и координаты водяного знака с учётом отступов родителя. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Получает или задает желаемую высоту этого [`Watermark`](../../groupdocs.watermark/watermark). |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Получает или задает горизонтальное выравнивание этого [`Watermark`](../../groupdocs.watermark/watermark). |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Получает или задает значение, указывающее, следует ли размещать водяной знак на фоне. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Получает или задает параметры отступов этого [`Watermark`](../../groupdocs.watermark/watermark). |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Получает или задает непрозрачность этого [`Watermark`](../../groupdocs.watermark/watermark). |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | Получает или задает настройки конфигурации страниц этого [`Watermark`](../../groupdocs.watermark/watermark). |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Получает или задает угол поворота этого [`Watermark`](../../groupdocs.watermark/watermark) в градусах. |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | Получает или задает значение, указывающее, сохранять ли информацию о добавленных водяных знаках в метаданных документа. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Получает или задает значение, определяющее, как размер водяного знака зависит от размера родителя. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Получает или задает значение, указывающее способ масштабирования водяного знака. |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | Получает или задает параметры для определения повторяющегося водяного знака |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание этого [`Watermark`](../../groupdocs.watermark/watermark). |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Получает или задает желаемую ширину этого [`Watermark`](../../groupdocs.watermark/watermark). |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Получает или задает координату x этого [`Watermark`](../../groupdocs.watermark/watermark). |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Получает или задает координату y этого [`Watermark`](../../groupdocs.watermark/watermark). |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../groupdocs.watermark.watermarks/imagewatermark/dispose)() | Освобождает текущий экземпляр. |

### Примечания

**Learn more:**

* [Adding image watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks)

### Примеры

Добавьте изображение‑водяной знак в документ любого поддерживаемого типа.

```csharp
foreach (string filePath in Directory.GetFiles(@"C:\Documents"))
{
    using (Watermarker watermarker = new Watermarker(filePath))
    {
        using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
        {
            watermark.HorizontalAlignment = HorizontalAlignment.Center;
            watermark.VerticalAlignment = VerticalAlignment.Center;
            watermarker.Add(watermark);
        }

        watermarker.Save();
    }
}
```

### См. также

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
