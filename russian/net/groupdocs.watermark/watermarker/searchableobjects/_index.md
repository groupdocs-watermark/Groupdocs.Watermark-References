---
title: "SearchableObjects"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Получает или задает объекты контента, которые должны быть включены в поиск водяных знаков."
type: docs
weight: 20
url: /ru/net/groupdocs.watermark/watermarker/searchableobjects/
---
## Watermarker.SearchableObjects property

Получает или задает объекты контента, которые должны быть включены в поиск водяных знаков.

```csharp
public SearchableObjects SearchableObjects { get; set; }
```

### Property Value

Объекты, которые должны быть включены в поиск водяных знаков.

### Примечания

Это свойство также указывает объектные элементы, используемые при поиске изображений. Для получения дополнительной информации см. методы [`Search`](../search) и [`GetImages`](../getimages).

Узнайте больше о поиске водяных знаков: [Поиск водяных знаков](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Примеры

Удалить все XObjects и Artifacts из PDF‑документа.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf"))
{
    // Укажите, что следует искать только XObjects и Artifacts.
    watermarker.SearchableObjects.PdfSearchableObjects
        = PdfSearchableObjects.XObjects | PdfSearchableObjects.Artifacts; 

    PossibleWatermarkCollection watermarks = watermarker.Search();

    // Удалить все найденные объекты.
    watermarks.Clear();

    // Сохраняет изменения.
    watermarker.Save();
}
```

### См. также

* class [SearchableObjects](../../../groupdocs.watermark.search.objects/searchableobjects)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
