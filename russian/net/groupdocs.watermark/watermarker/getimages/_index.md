---
title: "GetImages"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Находит изображения согласно указанным критериям поиска."
type: docs
weight: 80
url: /ru/net/groupdocs.watermark/watermarker/getimages/
---
## GetImages(ImageSearchCriteria) {#getimages_1}

Находит изображения согласно указанным критериям поиска.

```csharp
public WatermarkableImageCollection GetImages(ImageSearchCriteria searchCriteria)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchCriteria | ImageSearchCriteria | Критерии поиска для использования. |

### Возвращаемое значение

Коллекция найденных изображений.

### Примечания

Поиск проводится в объектах, указанных в [`SearchableObjects`](../searchableobjects).

Узнайте больше о поиске водяных знаков [Поиск водяных знаков](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Примеры

Удалить все изображения, похожие на образец, из документа любого поддерживаемого типа.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageThumbnailSearchCriteria criteria = new ImageThumbnailSearchCriteria("reference.png");
    WatermarkableImageCollection images = watermarker.GetImages(criteria);
    images.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### См. также

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [ImageSearchCriteria](../../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## GetImages() {#getimages}

Находит все изображения в документе.

```csharp
public WatermarkableImageCollection GetImages()
```

### Возвращаемое значение

Коллекция найденных изображений.

### Примечания

Поиск проводится в объектах, указанных в [`SearchableObjects`](../searchableobjects).

Узнайте больше о поиске водяных знаков [Поиск водяных знаков](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Примеры

Добавьте водяной знак ко всем изображениям в документе любого поддерживаемого типа.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // Инициализировать текстовый или графический водяной знак.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // Найдите все изображения в документе.
    WatermarkableImageCollection images = watermarker.GetImages();

    // Добавить водяной знак.
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.AddWatermark(watermark);
    }

    // Сохраняет изменения.
    watermarker.Save(@"D:\output.doc");
}
```

### См. также

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
