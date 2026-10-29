---
title: "保存"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "将文档数据保存到底层流。"
type: docs
weight: 100
url: /zh/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

将文档数据保存到底层流。

```csharp
public WatermarkResult Save()
```

### 备注

了解更多关于保存文档的信息 [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents)。

### 示例

从电子邮件正文/主题中移除特定文本片段并保存电子邮件。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // 注意，只有在将 TextSearchCriteria 实例传递给 Search 方法时才会执行搜索
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // 删除已找到的文本片段
    watermarker.Remove(watermarks);
    // 保存更改
    watermarker.Save();
}
```

### 另请参阅

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

将文档保存到指定的文件位置。

```csharp
public WatermarkResult Save(string filePath)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| filePath | String | 用于保存文档数据的文件路径。 |

### 备注

了解更多关于保存文档的信息 [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents)。

### 示例

添加水印并将文档保存到另一个文件。

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### 另请参阅

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

将文档保存到指定的流。

```csharp
public WatermarkResult Save(Stream document)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| 文档 | Stream | 用于保存文档数据的流。 |

### 备注

了解更多关于保存文档的信息 [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents)。

### 示例

添加水印并将文档保存到内存流。

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream);
        // ...
    }
}
```

### 另请参阅

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

使用保存选项将文档数据保存到底层流。

```csharp
public WatermarkResult Save(SaveOptions options)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| 选项 | SaveOptions | 保存文档时使用的其他选项。 |

### 备注

了解更多关于保存文档的信息 [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents)。

### 示例

添加水印并使用默认的[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions)保存文档。

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### 另请参阅

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

使用保存选项将文档保存到指定的文件位置。

```csharp
public WatermarkResult Save(string filePath, SaveOptions options)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| filePath | String | 用于保存文档数据的文件路径。 |
| 选项 | SaveOptions | 保存文档时使用的其他选项。 |

### 备注

了解更多关于保存文档的信息 [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents)。

### 示例

添加水印并使用默认的[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions)将文档保存到另一个文件。

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### 另请参阅

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

使用保存选项将文档保存到指定的流。

```csharp
public WatermarkResult Save(Stream document, SaveOptions options)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| 文档 | Stream | 用于保存文档数据的流。 |
| 选项 | SaveOptions | 保存文档时使用的其他选项。 |

### 备注

了解更多关于保存文档的信息 [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents)。

### 示例

添加水印并使用默认的[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions)将文档保存到内存流。

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream, new SaveOptions());
        // ...
    }
}
```

### 另请参阅

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
