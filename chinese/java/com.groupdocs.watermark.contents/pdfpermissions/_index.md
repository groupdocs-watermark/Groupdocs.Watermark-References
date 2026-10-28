---
title: "PdfPermissions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示用户对 PDF 文档的权限。"
type: docs
weight: 68
url: /zh/java/com.groupdocs.watermark.contents/pdfpermissions/
---
**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

表示用户对 PDF 文档的权限。

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [PrintDocument](#PrintDocument) | 打印内容。 |
|
|  | [ModifyContent](#ModifyContent) | 修改内容。 |
|
|  | [ExtractContent](#ExtractContent) | 复制或以其他方式从文档中提取文本和图形。 |
|
|  | [ModifyTextAnnotations](#ModifyTextAnnotations) | 添加或修改文本批注。 |
|
|  | [FillForm](#FillForm) | 填写现有的交互式表单字段。 |
|
|  | [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | 提取文本和图形。 |
|
|  | [AssembleDocument](#AssembleDocument) | 组装内容。 |
|
|  | [PrintingQuality](#PrintingQuality) | 将内容打印为一种表示形式，以便能够生成 PDF 文档的忠实数字副本。 |
|
### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


打印内容。

修订版 2 的安全处理程序：打印内容。

修订版 3 或更高版本的安全处理程序：打印内容
(可能未达到最高质量水平，取决于是否
`#PrintingQuality.PrintingQuality` 也已设置)。


### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


修改内容。

通过其他操作修改文档的内容
而不是由 `#ModifyTextAnnotations.ModifyTextAnnotations`、`#FillForm.FillForm` 控制的操作。


### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```


复制或以其他方式从文档中提取文本和图形。

修订版 2 的安全处理程序：复制或以其他方式从内容中提取文本和图形，
包括提取文本和图形（以支持对具有
残障人士或用于其他目的).

安全处理程序（修订版 3 或更高）：复制或以其他方式从中提取文本和图形
内容，通过受控之外的操作
`#ExtractContentWithDisabilities.ExtractContentWithDisabilities`.


### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```


添加或修改文本批注。

添加或修改文本注释，填写交互式表单字段，
并且，如果 `#ModifyContent.ModifyContent` 也已设置，
创建或修改交互式表单字段（包括签名字段）。


### FillForm {#FillForm}
```
public static final int FillForm
```


填写现有的交互式表单字段。

安全处理程序（修订版 3 或更高）：填写现有的交互式表单字段
（包括签名字段），即使 `#ModifyTextAnnotations.ModifyTextAnnotations` 已清除。


### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```


提取文本和图形。

安全处理程序（修订版 3 或更高）：提取文本和图形
（以支持残障用户的可访问性或用于其他目的）。


### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


组装内容。

安全处理程序（修订版 3 或更高）：组装内容（插入、旋转或删除页面
并创建书签或缩略图），即使 `#ModifyContent.ModifyContent` 已清除。


### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```


将内容打印为一种表示形式，以便能够生成 PDF 文档的忠实数字副本。

安全处理程序（修订版 3 或更高）：将内容打印为一种可以忠实
生成 PDF 文档的数字副本。当此位被清除时（且 `#PrintDocument.PrintDocument`
已设置），打印将限制为外观的低级表示，可能质量下降。


