---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "初始化 PdfPreviewOptionsgroupdocs.watermark.options.pdf/pdfpreviewoptions 类的新实例，并导致输出流被关闭。"
type: docs
weight: 10
url: /zh/net/groupdocs.watermark.options.pdf/pdfpreviewoptions/pdfpreviewoptions/
---
## PdfPreviewOptions(CreatePageStream) {#constructor}

初始化 [`PdfPreviewOptions`](../../pdfpreviewoptions) 类的新实例，并导致输出流被关闭。

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 为特定页面预览创建流。 |

### 另请参阅

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../../)

---

## PdfPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

初始化 [`PdfPreviewOptions`](../../pdfpreviewoptions) 类的新实例，使输出流返回给客户端以供进一步使用。

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 为特定页面预览创建流。 |
| releasePageStream | ReleasePageStream | 通知页面预览生成已完成并获取输出流。 |

### 另请参阅

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
