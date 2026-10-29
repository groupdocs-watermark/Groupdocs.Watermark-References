---
title: "IDocumentInfo"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "定义获取基本文档信息所需的方法。"
type: docs
weight: 70
url: /zh/net/groupdocs.watermark.common/idocumentinfo/
---
## IDocumentInfo interface

定义获取基本文档信息所需的方法。

```csharp
public interface IDocumentInfo
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [FileType](../../groupdocs.watermark.common/idocumentinfo/filetype) { get; } | 获取文件格式描述。 |
| [IsEncrypted](../../groupdocs.watermark.common/idocumentinfo/isencrypted) { get; } | 获取一个值，指示文档是否已加密且需要密码才能打开。 |
| [PageCount](../../groupdocs.watermark.common/idocumentinfo/pagecount) { get; } | 获取总页数。 |
| [Pages](../../groupdocs.watermark.common/idocumentinfo/pages) { get; } | 获取文档页面描述的集合。 |
| [Size](../../groupdocs.watermark.common/idocumentinfo/size) { get; } | 获取文档大小（字节）。 |

### 备注

**Learn more**

* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### 示例

以下示例演示如何使用[`IDocumentInfo`](../idocumentinfo)检索通用文档信息。

```csharp
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### 另请参阅

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
