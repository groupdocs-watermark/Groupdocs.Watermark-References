---
title: "添加"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "向已加载的文档添加水印。"
type: docs
weight: 30
url: /zh/net/groupdocs.watermark/watermarker/add/
---
## Add(Watermark) {#add}

向已加载的文档添加水印。

```csharp
public AddWatermarkResult Add(Watermark watermark)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| 水印 | 水印 | 要添加到文档的水印。 |

### 备注

了解更多关于添加水印的信息: [Adding watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks)。

### 示例

向任何受支持类型的文档添加图像和文本水印。

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

### 另请参阅

* class [AddWatermarkResult](../../../groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [Watermark](../../watermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Add(Watermark, WatermarkOptions) {#add_1}

使用水印选项向已加载的文档添加水印。

```csharp
public AddWatermarkResult Add(Watermark watermark, WatermarkOptions options)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| 水印 | 水印 | 要添加到文档的水印。 |
| 选项 | WatermarkOptions | 添加水印时使用的其他选项。 |

### 备注

了解更多关于添加水印的信息 [Adding watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks)。

### 示例

在 PDF 文档的特定页面添加图像水印。

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

### 另请参阅

* class [AddWatermarkResult](../../../groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [Watermark](../../watermark)
* class [WatermarkOptions](../../../groupdocs.watermark.options/watermarkoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
