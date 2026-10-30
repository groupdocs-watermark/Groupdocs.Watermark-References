---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Инициализирует новый экземпляр класса SpreadsheetPreviewOptionsgroupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions, закрывающий поток вывода."
type: docs
weight: 10
url: /ru/net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/spreadsheetpreviewoptions/
---
## SpreadsheetPreviewOptions(CreatePageStream) {#constructor}

Инициализирует новый экземпляр класса [`SpreadsheetPreviewOptions`](../../spreadsheetpreviewoptions), закрывающий поток вывода.

```csharp
public SpreadsheetPreviewOptions(CreatePageStream createPageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Создаёт поток для предварительного просмотра конкретной страницы. |

### См. также

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [SpreadsheetPreviewOptions](../../spreadsheetpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

---

## SpreadsheetPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Инициализирует новый экземпляр класса [`SpreadsheetPreviewOptions`](../../spreadsheetpreviewoptions), возвращающий поток вывода клиенту для дальнейшего использования.

```csharp
public SpreadsheetPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Создаёт поток для предварительного просмотра конкретной страницы. |
| releasePageStream | ReleasePageStream | Уведомляет о завершении генерации предварительного просмотра страницы и получает выходной поток. |

### См. также

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [SpreadsheetPreviewOptions](../../spreadsheetpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
