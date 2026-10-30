---
title: "GetContent"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Возвращает объект Contentgroupdocs.watermark.contents/content для загруженного документа."
type: docs
weight: 60
url: /ru/net/groupdocs.watermark/watermarker/getcontent/
---
## Watermarker.GetContent&lt;T&gt; method

Возвращает объект [`Content`](../../../groupdocs.watermark.contents/content) для загруженного документа.

```csharp
public T GetContent<T>()
    where T : Content
```

| Параметр | Описание |
| --- | --- |
| T | Запрошенный тип объекта [`Content`](../../../groupdocs.watermark.contents/content). |

### Возвращаемое значение

Объект [`Content`](../../../groupdocs.watermark.contents/content) для загруженного документа.

### Примеры

Растрировать страницу PDF‑документа с добавленным водяным знаком.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\doc.pdf", loadOptions))
{ 
    using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
    {
        watermarker.Add(watermark);
    }

    PdfContent content = watermarker.GetContent<PdfContent>();
    content.Rasterize(300, 300, PdfImageConversionFormat.Png);

    watermarker.Save();
}
```

### См. также

* class [Content](../../../groupdocs.watermark.contents/content)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
