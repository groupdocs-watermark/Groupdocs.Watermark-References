---
title: "PdfPermissions"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示用户对 PDF 文档的权限。"
type: docs
weight: 760
url: /zh/net/groupdocs.watermark.contents.pdf/pdfpermissions/
---
## PdfPermissions enumeration

表示用户对 PDF 文档的权限。

```csharp
[Flags]
public enum PdfPermissions
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| PrintDocument | `4` | 打印内容。 |
| ModifyContent | `8` | 修改内容。 |
| ExtractContent | `10` | 复制或以其他方式提取文档中的文本和图形。 |
| ModifyTextAnnotations | `20` | 添加或修改文本注释。 |
| FillForm | `100` | 填写现有的交互式表单字段。 |
| ExtractContentWithDisabilities | `200` | 提取文本和图形。 |
| AssembleDocument | `400` | 组装内容。 |
| PrintingQuality | `800` | 将内容打印为一种表示形式，以便可以生成 PDF 文档的忠实数字副本。 |

### 另请参阅

* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
