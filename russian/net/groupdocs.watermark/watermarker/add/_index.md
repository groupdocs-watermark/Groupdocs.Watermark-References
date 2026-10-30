---
title: "Add"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Добавляет водяной знак в загруженный документ."
type: docs
weight: 30
url: /ru/net/groupdocs.watermark/watermarker/add/
---
## Add(Watermark) {#add}

Добавляет водяной знак в загруженный документ.

```csharp
public AddWatermarkResult Add(Watermark watermark)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| watermark | Watermark | Водяной знак, который будет добавлен в документ. |

### Примечания

Узнайте больше о добавлении водяных знаков: [Добавление водяных знаков](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks).

### Примеры

Добавьте изображение и текстовый водяной знак в документ любого поддерживаемого типа.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.pdf"))
{
    TextWatermark textWatermark = new TextWatermark("DRAFT", new Font("Arial", 19));
    textWatermark.HorizontalAlignment = HorizontalAlignment.Center;
    textWatermark.VerticalAlignment = VerticalAlignment.Top;
    textWatermark.ConsiderParentMargins = true;
    textWatermark.ForegroundColor = Color.Red;
    textWatermark.IsBackground = true;
    textWatermark.Opacity = 0.5;
    watermarker.Add(textWatermark);

    using (ImageWatermark imageWatermark = new ImageWatermark(@"D:\draft.png"))
    {
        imageWatermark.HorizontalAlignment = HorizontalAlignment.Center;
        imageWatermark.VerticalAlignment = VerticalAlignment.Bottom;
        imageWatermark.ConsiderParentMargins = true;
        imageWatermark.IsBackground = true;
        imageWatermark.Opacity = 0.5;
        watermarker.Add(imageWatermark);
    }

    watermarker.Save(@"D:\output.pdf");
}
```

### См. также

* class [AddWatermarkResult](../../../groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [Watermark](../../watermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Add(Watermark, WatermarkOptions) {#add_1}

Добавляет водяной знак в загруженный документ, используя параметры водяного знака.

```csharp
public AddWatermarkResult Add(Watermark watermark, WatermarkOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| watermark | Watermark | Водяной знак, который будет добавлен в документ. |
| options | WatermarkOptions | Дополнительные параметры, используемые при добавлении водяного знака. |

### Примечания

Узнайте больше о добавлении водяных знаков [Adding watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks).

### Примеры

Добавьте изображение водяного знака на определённую страницу PDF‑документа.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\doc.pdf", loadOptions))
using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
{
    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### См. также

* class [AddWatermarkResult](../../../groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [Watermark](../../watermark)
* class [WatermarkOptions](../../../groupdocs.watermark.options/watermarkoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
