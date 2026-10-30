---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет изображение внутри документа."
type: docs
weight: 470
url: /ru/net/groupdocs.watermark.contents.image/watermarkableimage/
---
## WatermarkableImage class

Представляет изображение внутри документа.

```csharp
public abstract class WatermarkableImage : ContentPart
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Получает высоту этого [`WatermarkableImage`](../watermarkableimage) в пикселях. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Получает ширину этого [`WatermarkableImage`](../watermarkableimage) в пикселях. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Добавляет водяной знак к этому [`WatermarkableImage`](../watermarkableimage). Этот метод предполагает, что смещение и размер водяного знака измеряются в пикселях (если они заданы). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Находит все изображения в контенте. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Находит изображения согласно указанным критериям поиска. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Получает изображение в виде массива байтов. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Находит все возможные водяные знаки в контенте. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Находит возможные водяные знаки в соответствии с указанными критериями поиска. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Примечания

**Learn more:**

* [Adding watermark to images inside a document](https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document)

### Примеры

Добавьте водяной знак ко всем изображениям внутри документа любого поддерживаемого типа.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // Инициализировать текстовый или графический водяной знак.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // Найдите все изображения в содержимом.
    WatermarkableImageCollection images = watermarker.GetImages();

    // Добавить водяной знак.
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.Add(watermark);
    }

    // Сохраняет изменения.
    watermarker.Save(@"D:\output.doc");
}
```

### См. также

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
