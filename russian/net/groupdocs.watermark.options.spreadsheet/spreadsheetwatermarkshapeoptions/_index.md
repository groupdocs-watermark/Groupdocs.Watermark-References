---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет параметры при добавлении фигурного водяного знака в лист Spreadsheet."
type: docs
weight: 2290
url: /ru/net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/
---
## SpreadsheetWatermarkShapeOptions class

Представляет параметры при добавлении фигурного водяного знака в лист Spreadsheet.

```csharp
public sealed class SpreadsheetWatermarkShapeOptions : SpreadsheetWatermarkBaseOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SpreadsheetWatermarkShapeOptions](spreadsheetwatermarkshapeoptions)() | Инициализирует новый экземпляр класса [`SpreadsheetWatermarkShapeOptions`](../spreadsheetwatermarkshapeoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternativetext) { get; set; } | Получает или задает описательный (альтернативный) текст, который будет связан с фигурой. |
| [Effects](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/effects) { get; set; } | Получает или задает значение [`SpreadsheetImageEffects`](../spreadsheetimageeffects) или [`SpreadsheetTextEffects`](../spreadsheettexteffects) для эффектов, которые должны быть применены к водяному знаку. |
| [IsLocked](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/islocked) { get; set; } | Получает или задает значение, указывающее, запрещено ли редактирование фигуры в Excel. |
| [Name](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name) { get; set; } | Получает или задает имя фигуры. |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/worksheetindex) { get; set; } | Получает или задает индекс листа, в который будет добавлен водяной знак. |

### Примечания

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Примеры

Добавляет водяной знак в конкретный лист Excel‑документа.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.xls", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
    watermark.HorizontalAlignment = HorizontalAlignment.Center;
    watermark.VerticalAlignment = VerticalAlignment.Center;

    SpreadsheetWatermarkShapeOptions options = new SpreadsheetWatermarkShapeOptions();
    options.WorksheetIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### См. также

* class [SpreadsheetWatermarkBaseOptions](../spreadsheetwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
