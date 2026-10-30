---
title: "SpreadsheetWatermarkModernWordArtOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет параметры при добавлении современного ворд-арт водяного знака в лист Spreadsheet."
type: docs
weight: 2280
url: /ru/net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/
---
## SpreadsheetWatermarkModernWordArtOptions class

Представляет параметры при добавлении современного ворд-арт водяного знака в лист Spreadsheet.

```csharp
public sealed class SpreadsheetWatermarkModernWordArtOptions : SpreadsheetWatermarkBaseOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SpreadsheetWatermarkModernWordArtOptions](spreadsheetwatermarkmodernwordartoptions)() | Инициализирует новый экземпляр класса [`SpreadsheetWatermarkModernWordArtOptions`](../spreadsheetwatermarkmodernwordartoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternativetext) { get; set; } | Получает или задает описательный (альтернативный) текст, который будет связан с фигурой. |
| [IsLocked](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/islocked) { get; set; } | Получает или задает значение, указывающее, запрещено ли редактирование фигуры в Excel. |
| [Name](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name) { get; set; } | Получает или задает имя фигуры. |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/worksheetindex) { get; set; } | Получает или задает индекс листа, в который будет добавлен водяной знак. |

### Примечания

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Примеры

Добавляет современный WordArt‑водяной знак в Excel‑документ.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.xls", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));

    SpreadsheetWatermarkModernWordArtOptions options = new SpreadsheetWatermarkModernWordArtOptions();
    options.WorksheetIndex = -1; // default
    options.IsLocked = false; // default

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### См. также

* class [SpreadsheetWatermarkBaseOptions](../spreadsheetwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
