---
title: Save
second_title: .NET API 参考的 GroupDocs.Watermark
description: 将文档数据保存到底层流
type: docs
weight: 100
url: /zh/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

将文档数据保存到底层流。

```csharp
public void Save()
```

### 评论

了解有关保存文档的更多信息 [保存文件](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 例子

从电子邮件正文/主题中删除特定的文本片段并保存电子邮件。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // 注意，只有将 TextSearchCriteria 实例传递给 Search 方法时才会执行搜索
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // 删除找到的文本片段
    watermarker.Remove(watermarks);
    // 保存更改
    watermarker.Save();
}
```

### 也可以看看

* class [Watermarker](../../watermarker)
* 命名空间 [GroupDocs.Watermark](../../watermarker)
* 部件 [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

将文档保存到指定的文件位置。

```csharp
public void Save(string filePath)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 保存文档数据的文件路径。 |

### 评论

了解有关保存文档的更多信息 [保存文件](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 例子

添加水印并将文档保存到另一个文件。

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### 也可以看看

* class [Watermarker](../../watermarker)
* 命名空间 [GroupDocs.Watermark](../../watermarker)
* 部件 [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

将文档保存到指定的流中。

```csharp
public void Save(Stream document)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Stream | 将文档数据保存到的流。 |

### 评论

了解有关保存文档的更多信息 [保存文件](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 例子

添加水印并将文档保存到内存流中。

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

### 也可以看看

* class [Watermarker](../../watermarker)
* 命名空间 [GroupDocs.Watermark](../../watermarker)
* 部件 [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

使用保存选项将文档数据保存到底层流。

```csharp
public void Save(SaveOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| options | SaveOptions | 保存文档时使用的其他选项。 |

### 评论

了解有关保存文档的更多信息 [保存文件](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 例子

添加水印并默认保存文档[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### 也可以看看

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* 命名空间 [GroupDocs.Watermark](../../watermarker)
* 部件 [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

使用保存选项将文档保存到指定的文件位置。

```csharp
public void Save(string filePath, SaveOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 保存文档数据的文件路径。 |
| options | SaveOptions | 保存文档时使用的其他选项。 |

### 评论

了解有关保存文档的更多信息 [保存文件](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 例子

添加水印并将文档默认保存到另一个文件[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### 也可以看看

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* 命名空间 [GroupDocs.Watermark](../../watermarker)
* 部件 [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

使用保存选项将文档保存到指定的流中。

```csharp
public void Save(Stream document, SaveOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Stream | 将文档数据保存到的流。 |
| options | SaveOptions | 保存文档时使用的其他选项。 |

### 评论

了解有关保存文档的更多信息 [保存文件](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 例子

添加水印并将文档默认保存到内存流中[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

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

### 也可以看看

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* 命名空间 [GroupDocs.Watermark](../../watermarker)
* 部件 [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
