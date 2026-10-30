---
title: "TextWatermark"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет текстовый водяной знак."
type: docs
weight: 3320
url: /ru/net/groupdocs.watermark.watermarks/textwatermark/
---
## TextWatermark class

Представляет текстовый водяной знак.

```csharp
public class TextWatermark : Watermark
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextWatermark](textwatermark)(string, Font) | Инициализирует новый экземпляр класса [`TextWatermark`](../textwatermark) с указанным текстом и шрифтом. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../groupdocs.watermark.watermarks/textwatermark/backgroundcolor) { get; set; } | Получает или задает цвет фона текста. |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Получает или задает значение, указывающее, рассчитываются ли размер и координаты водяного знака с учётом отступов родителя. |
| [Font](../../groupdocs.watermark.watermarks/textwatermark/font) { get; set; } | Получает или задает шрифт текста. |
| [ForegroundColor](../../groupdocs.watermark.watermarks/textwatermark/foregroundcolor) { get; set; } | Получает или задает цвет переднего плана текста. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Получает или задает желаемую высоту этого [`Watermark`](../../groupdocs.watermark/watermark). |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Получает или задает горизонтальное выравнивание этого [`Watermark`](../../groupdocs.watermark/watermark). |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Получает или задает значение, указывающее, следует ли размещать водяной знак на фоне. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Получает или задает параметры отступов этого [`Watermark`](../../groupdocs.watermark/watermark). |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Получает или задает непрозрачность этого [`Watermark`](../../groupdocs.watermark/watermark). |
| [Padding](../../groupdocs.watermark.watermarks/textwatermark/padding) { get; set; } | Получает или задает параметры внутреннего отступа этого [`TextWatermark`](../textwatermark). Это свойство применимо только к файлам изображений. |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | Получает или задает настройки конфигурации страниц этого [`Watermark`](../../groupdocs.watermark/watermark). |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Получает или задает угол поворота этого [`Watermark`](../../groupdocs.watermark/watermark) в градусах. |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | Получает или задает значение, указывающее, сохранять ли информацию о добавленных водяных знаках в метаданных документа. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Получает или задает значение, определяющее, как размер водяного знака зависит от размера родителя. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Получает или задает значение, указывающее способ масштабирования водяного знака. |
| [Text](../../groupdocs.watermark.watermarks/textwatermark/text) { get; set; } | Получает или задает текст, используемый в качестве водяного знака. |
| [TextAlignment](../../groupdocs.watermark.watermarks/textwatermark/textalignment) { get; set; } | Получает или задает выравнивание текста водяного знака. |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | Получает или задает параметры для определения повторяющегося водяного знака |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание этого [`Watermark`](../../groupdocs.watermark/watermark). |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Получает или задает желаемую ширину этого [`Watermark`](../../groupdocs.watermark/watermark). |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Получает или задает координату x этого [`Watermark`](../../groupdocs.watermark/watermark). |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Получает или задает координату y этого [`Watermark`](../../groupdocs.watermark/watermark). |

### Примечания

**Learn more:**

* [Adding text watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks)

### Примеры

Масштабировать текстовый водяной знак в зависимости от размера родительского элемента.

```csharp
foreach (string file in Directory.GetFiles("C:\\test"))
{
    using (Watermarker watermarker = new Watermarker(file))
    {
        TextWatermark watermark = new TextWatermark("test watermark", new Font("Arial", 36));
        watermark.HorizontalAlignment = HorizontalAlignment.Center;
        watermark.VerticalAlignment = VerticalAlignment.Center;
        watermark.SizingType = SizingType.ScaleToParentDimensions;
        watermark.RotateAngle = 45;
        watermark.ScaleFactor = 0.4;

        watermarker.Add(watermark);
        watermarker.Save();
    }
}
```

### См. также

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
