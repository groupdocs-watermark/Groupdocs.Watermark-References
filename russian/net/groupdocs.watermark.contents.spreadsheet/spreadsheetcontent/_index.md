---
title: "SpreadsheetContent"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет документ Excel, в котором можно разместить водяной знак."
type: docs
weight: 1170
url: /ru/net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/
---
## SpreadsheetContent class

Представляет документ Excel, в котором можно разместить водяной знак.

```csharp
public class SpreadsheetContent : Content
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Worksheets](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/worksheets) { get; } | Получает коллекцию всех листов этого [`SpreadsheetContent`](../spreadsheetcontent). |

## Методы

| Имя | Описание |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/decrypt)() | Расшифровывает документ. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Освобождает текущий экземпляр. |
| [Encrypt](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt)(string) | Шифрует содержимое. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Находит все изображения в контенте. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Находит изображения согласно указанным критериям поиска. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Находит все возможные водяные знаки в контенте. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Находит возможные водяные знаки в соответствии с указанными критериями поиска. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Примечания

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)
* [Shapes in spreadsheet document](https://docs.groupdocs.com/display/watermarknet/Shapes+in+spreadsheet+document)
* [Working with spreadsheet document attachments](https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments)
* [Working with worksheet backgrounds](https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+backgrounds)
* [Working with worksheet headers and footers](https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+headers+and+footers)

### Примеры

Загружайте и сохраняйте документ Excel любого поддерживаемого типа.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.xls", loadOptions))
{
    // Используйте метод Add, чтобы добавить водяной знак к отдельному листу или ко всем листам.

    // Сохраняет изменения.
    watermarker.Save(@"D:\output.xls");
}
```

### См. также

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
