---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет параметры при добавлении водяного знака в качестве фона листа таблицы Spreadsheet."
type: docs
weight: 2190
url: /ru/net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/
---
## SpreadsheetBackgroundWatermarkOptions class

Представляет параметры при добавлении водяного знака в качестве фона листа таблицы Spreadsheet.

```csharp
public sealed class SpreadsheetBackgroundWatermarkOptions : WatermarkOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SpreadsheetBackgroundWatermarkOptions](spreadsheetbackgroundwatermarkoptions)() | Инициализирует новый экземпляр класса [`SpreadsheetBackgroundWatermarkOptions`](../spreadsheetbackgroundwatermarkoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [BackgroundHeight](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/backgroundheight) { get; set; } | Получает или задает желаемую высоту фонового изображения в пикселях. |
| [BackgroundWidth](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/backgroundwidth) { get; set; } | Получает или задает желаемую ширину фонового изображения в пикселях. |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/worksheetindex) { get; set; } | Получает или задает индекс листа, в который будет добавлен водяной знак. |

### Примечания

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Примеры

Добавляет текстовый водяной знак в лист Excel‑документа в качестве фона.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.xlsx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));

    SpreadsheetBackgroundWatermarkOptions options = new SpreadsheetBackgroundWatermarkOptions();
    options.WorksheetIndex = -1; // default
    options.BackgroundWidth = 800;
    options.BackgroundHeight = 600;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### См. также

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
