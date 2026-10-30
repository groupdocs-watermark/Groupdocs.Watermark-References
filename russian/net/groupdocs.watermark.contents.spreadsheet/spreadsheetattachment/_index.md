---
title: "SpreadsheetAttachment"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет файл, вложенный в документ Excel."
type: docs
weight: 1100
url: /ru/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/
---
## SpreadsheetAttachment class

Представляет файл, вложенный в документ Excel.

```csharp
public class SpreadsheetAttachment : Attachment, ITwoDObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/alternativetext) { get; set; } | Получает или задает описательный (альтернативный) текст, связанный с прикрепленным файлом. |
| override [Content](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/content) { get; set; } | Получает или задает содержимое вложенного файла. |
| [Height](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/height) { get; set; } | Получает или задает высоту рамки вложения в пунктах. |
| [IsLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/islink) { get; } | Получает значение, указывающее, содержит ли содержимое только ссылку на файл. |
| [PreviewImageContent](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/previewimagecontent) { get; set; } | Получает или задает изображение предварительного просмотра прикрепленного файла в виде массива байтов. |
| [SourceFullName](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/sourcefullname) { get; } | Получает полное имя прикрепленного файла. |
| [Width](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/width) { get; set; } | Получает или задает ширину рамки вложения в пунктах. |
| [X](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/x) { get; set; } | Получает или задает горизонтальное смещение рамки вложения от левого края листа в пунктах. |
| [Y](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/y) { get; set; } | Получает или задает вертикальное смещение рамки вложения от верхнего края листа в пунктах. |

## Методы

| Имя | Описание |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | Загружает содержимое из вложенного файла. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | Загружает содержимое из вложенного файла с указанными параметрами загрузки. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | Загружает содержимое из вложенного файла с указанными параметрами загрузки и настройками. |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | Получает информацию о документе, хранящемся во вложенном файле. |

### См. также

* class [Attachment](../../groupdocs.watermark.common/attachment)
* interface [ITwoDObject](../../groupdocs.watermark.search/itwodobject)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
