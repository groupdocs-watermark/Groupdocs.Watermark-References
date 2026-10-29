---
title: "GetDocumentInfo"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "获取已加载文档格式的信息。"
type: docs
weight: 70
url: /zh/net/groupdocs.watermark/watermarker/getdocumentinfo/
---
## Watermarker.GetDocumentInfo method

获取已加载文档格式的信息。

```csharp
public IDocumentInfo GetDocumentInfo()
```

### 返回值

包含检测信息的[`IDocumentInfo`](../../../groupdocs.watermark.common/idocumentinfo)实例。

### 备注

了解有关获取文档信息的更多内容 [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)。

### 示例

获取有关任何受支持类型的文档的信息。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.ppt"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### 另请参阅

* interface [IDocumentInfo](../../../groupdocs.watermark.common/idocumentinfo)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
