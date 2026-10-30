---
title: "AddAttachment"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Добавляет вложение к объекту SpreadsheetWorksheetgroupdocs.watermark.contents.spreadsheet/spreadsheetworksheet."
type: docs
weight: 10
url: /ru/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addattachment/
---
## SpreadsheetAttachmentCollection.AddAttachment method

Добавляет вложение к [`SpreadsheetWorksheet`](../../spreadsheetworksheet).

```csharp
public void AddAttachment(byte[] fileContent, string sourceFullName, byte[] previewImageContent, 
    double x, double y, double width, double height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileContent | Byte[] | Содержимое файла, которое будет вложено. |
| sourceFullName | String | Полное имя вложенного файла (расширение используется для определения подходящего приложения для открытия файла). |
| previewImageContent | Byte[] | Предпросмотр вложенного файла в виде массива байтов. |
| x | Double | Координата x рамки вложения (в пунктах). |
| y | Double | Координата y рамки вложения (в пунктах). |
| ширина | Double | Ширина рамки вложения в пунктах. |
| высота | Double | Высота рамки вложения в пунктах. |

### См. также

* class [SpreadsheetAttachmentCollection](../../spreadsheetattachmentcollection)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
