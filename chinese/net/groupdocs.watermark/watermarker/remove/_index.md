---
title: "Remove"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "从文档中移除水印。"
type: docs
weight: 90
url: /zh/net/groupdocs.watermark/watermarker/remove/
---
## Remove(PossibleWatermark) {#remove}

从文档中移除水印。

```csharp
public void Remove(PossibleWatermark possibleWatermark)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| possibleWatermark | PossibleWatermark | 要移除的水印。 |

### 备注

了解更多关于移除水印的信息: [Removing found watermarks](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks)。

### 示例

在任何受支持类型的文档中查找并移除第一个包含特定文本或图像的可能水印。

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

### 另请参阅

* class [PossibleWatermark](../../../groupdocs.watermark.search/possiblewatermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Remove(PossibleWatermarkCollection) {#remove_1}

从文档中移除集合中的所有水印。

```csharp
public void Remove(PossibleWatermarkCollection possibleWatermarks)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| possibleWatermarks | PossibleWatermarkCollection | 要移除的水印集合。 |

### 备注

了解更多关于移除水印的信息 [Removing found watermarks](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks)。

### 示例

查找并删除任何受支持类型文档中包含特定文本或图像的所有可能水印。

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

### 另请参阅

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
