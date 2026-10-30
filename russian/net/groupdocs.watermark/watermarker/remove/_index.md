---
title: "Remove"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Удаляет водяной знак из документа."
type: docs
weight: 90
url: /ru/net/groupdocs.watermark/watermarker/remove/
---
## Remove(PossibleWatermark) {#remove}

Удаляет водяной знак из документа.

```csharp
public void Remove(PossibleWatermark possibleWatermark)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| possibleWatermark | PossibleWatermark | Водяной знак для удаления. |

### Примечания

Узнайте больше о удалении водяных знаков: [Удаление найденных водяных знаков](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks).

### Примеры

Найдите и удалите первый возможный водяной знак, содержащий определённый текст или изображение, из документа любого поддерживаемого типа.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    if (watermarks.Count > 0)
    {
        watermarker.Remove(watermarks[0]);
    }

    watermarker.Save(@"D:\output.doc");
}
```

### См. также

* class [PossibleWatermark](../../../groupdocs.watermark.search/possiblewatermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Remove(PossibleWatermarkCollection) {#remove_1}

Удаляет все водяные знаки из коллекции в документе.

```csharp
public void Remove(PossibleWatermarkCollection possibleWatermarks)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| possibleWatermarks | PossibleWatermarkCollection | Коллекция водяных знаков для удаления. |

### Примечания

Узнайте больше об удалении водяных знаков [Удаление найденных водяных знаков](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks).

### Примеры

Найти и удалить все возможные водяные знаки, содержащие определённый текст или изображение, из документа любого поддерживаемого типа.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    watermarker.Remove(watermarks);
    watermarker.Save(@"D:\output.doc");
}
```

### См. также

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
