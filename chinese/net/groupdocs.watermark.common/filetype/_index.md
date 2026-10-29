---
title: "文件类型"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示文件类型。"
type: docs
weight: 40
url: /zh/net/groupdocs.watermark.common/filetype/
---
## FileType class

表示文件类型。

```csharp
public sealed class FileType : IEquatable<FileType>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | 获取文件名后缀（包括句点 "."），例如 ".doc"。 |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | 获取文件类型名称，例如 "Microsoft Word Document"。 |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | 获取格式族。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | 将文件扩展名映射到文件类型。 |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | 确定当前 [`FileType`](../filetype) 是否与指定的 [`FileType`](../filetype) 对象相同。 |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | 确定当前 [`FileType`](../filetype) 是否与指定对象相同。 |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | 返回当前 [`FileType`](../filetype) 对象的哈希码。 |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | 返回表示当前对象的字符串。 |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | 检索受支持的文件类型。 |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | 确定两个 [`FileType`](../filetype) 对象是否相同。 |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | 确定两个 [`FileType`](../filetype) 对象是否不相同。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | 扩展名为 .BMP 的文件表示用于存储位图数字图像的位图图像文件。这些图像与图形适配器无关，也称为设备无关位图（DIB）文件格式。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/bmp/)。 |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | 扩展名为 .doc 的文件表示由 Microsoft Word 或其他文字处理软件生成的二进制文件格式文档。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/doc/)。 |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | DOCM 文件是 Microsoft Word 2007 及以上版本生成的、能够运行宏的文档。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/docm/)。 |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX 是一种广为人知的 Microsoft Word 文档格式。自 2007 年 Microsoft Office 2007 发布起，引入了该格式，其结构从纯二进制更改为 XML 与二进制文件的组合。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/docx/)。 |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | 扩展名为 .DOT 的文件是 Microsoft Word 创建的模板文件，具有预设格式设置，可用于生成后续的 DOC 或 DOCX 文件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/dot/)。 |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | 扩展名为 DOTM 的文件表示由 Microsoft Word 2007 或更高版本创建的模板文件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/dotm/)。 |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | 扩展名为 DOTX 的文件是 Microsoft Word 创建的模板文件，具有预设格式设置，可用于生成后续的 DOCX 文件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/dotx/)。 |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | EML 文件格式表示使用 Outlook 等相关应用程序保存的电子邮件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/email/eml/)。 |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | EMLX 文件格式由 Apple 实现和开发。Apple Mail 应用程序使用 EMLX 文件格式导出电子邮件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/email/emlx/)。 |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML 存储在平面 XML 文件中，而非 ZIP 包（.xml）。了解更多关于此文件格式的信息，请点击[here](https://en.wikipedia.org/wiki/Office_Open_XML)。 |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML 宏启用文档存储在平面 XML 文件中，而非 ZIP 包（.xml）。了解更多关于此文件格式的信息，请点击[here](https://en.wikipedia.org/wiki/Office_Open_XML)。 |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Office Open XML WordprocessingML 模板（无宏）存储在平面 XML 文件中，而非 ZIP 包（.xml）。了解更多关于此文件格式的信息，请点击[here](https://en.wikipedia.org/wiki/Office_Open_XML)。 |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Office Open XML WordprocessingML 宏启用模板存储在平面 XML 文件中，而非 ZIP 包（.xml）。了解更多关于此文件格式的信息，请点击[here](https://en.wikipedia.org/wiki/Office_Open_XML)。 |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | GIF（图形交换格式）是一种高度压缩的图像类型。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/gif/)。 |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | JPEG 是一种使用有损压缩方法保存的图像格式。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/jpeg/)。 |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000（JPF）是一种图像编码系统和先进的图像压缩标准。采用小波技术设计，JPEG 2000 能够一次性以任意质量对无损内容进行编码。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/jp2/)。 |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | JPEG 是一种使用有损压缩方法保存的图像格式。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/jpeg/)。 |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000（JPM）是一种图像编码系统和先进的图像压缩标准。采用小波技术设计，JPEG 2000 能够一次性以任意质量对无损内容进行编码。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/jp2/)。 |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000（JPX）是一种图像编码系统和先进的图像压缩标准。采用小波技术设计，JPEG 2000 能够一次性以任意质量对无损内容进行编码。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/jp2/)。 |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG 是一种文件格式，Microsoft Outlook 和 Exchange 用于存储电子邮件、联系人、约会或其他任务。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/email/msg/)。 |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | ODT 文件是一种基于 OpenDocument 文本文件格式的文档，由文字处理应用程序创建。这些文件可通过诸如免费 OpenOffice Writer 等文字处理软件生成，能够包含文本、图像、对象和样式等内容。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/word-processing/odt/)。 |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | 带有 .OFT 扩展名的文件表示使用 Microsoft Outlook 创建的邮件模板文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/email/oft/)。 |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Office Open XML 文件（.ooxml）。 |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | 便携式文档格式（PDF）是一种由 Adobe 在 1990 年代创建的文档类型。该文件格式的目的是引入一种标准，用于以独立于应用软件、硬件以及操作系统的方式表示文档和其他参考资料。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/view/pdf/)。 |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG（Portable Network Graphics）是一种使用无损压缩的光栅图像文件格式。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/png/)。 |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | 带有 POTM 扩展名的文件是支持宏的 Microsoft PowerPoint 模板文件。POTM 文件由 PowerPoint 2007 或更高版本创建，包含可用于创建后续演示文稿的默认设置。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/presentation/potm/)。 |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | 带有 .POTX 扩展名的文件表示使用 Microsoft PowerPoint 2007 及以上版本创建的 PowerPoint 模板演示文稿。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/presentation/potx/)。 |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS（PowerPoint Slide Show）文件是使用 Microsoft PowerPoint 为幻灯片放映目的创建的。Microsoft PowerPoint 97-2003 支持 PPS 文件的读取和创建。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/presentation/pps/)。 |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | 带有 PPSM 扩展名的文件表示使用 Microsoft PowerPoint 2007 或更高版本创建的支持宏的幻灯片放映文件格式。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/presentation/ppsm/)。 |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX（PowerPoint Slide Show）文件是使用 Microsoft PowerPoint 2007 及以上版本为幻灯片放映目的创建的。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/presentation/ppsx/)。 |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | 带有 PPT 扩展名的文件表示由多个幻灯片组成、用于幻灯片放映的 PowerPoint 文件。它采用 Microsoft PowerPoint 97-2003 使用的二进制文件格式。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/presentation/ppt/)。 |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | 带有 PPTM 扩展名的文件是使用 Microsoft PowerPoint 2007 或更高版本创建的支持宏的演示文稿文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/presentation/pptm/)。 |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | 带有 PPTX 扩展名的文件是使用流行的 Microsoft PowerPoint 应用程序创建的演示文稿文件。不同于之前的二进制 PPT 演示文稿格式，PPTX 格式基于 Microsoft PowerPoint Open XML 演示文稿文件格式。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/presentation/pptx/)。 |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Rich Text Format（RTF）由 Microsoft 引入并文档化，提供了一种在应用程序中编码格式化文本和图形的方法。该格式促进了与其他 Microsoft 产品之间的跨平台文档交换，从而实现了互操作性。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/word-processing/rtf/)。 |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF 或 TIF（Tagged Image File Format）是一种用于在符合此文件格式标准的各种设备上使用的光栅图像。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/tiff/)。 |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF 或 TIF（Tagged Image File Format）是一种用于在符合此文件格式标准的各种设备上使用的光栅图像。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/tiff/)。 |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | 表示未知的文件类型。 |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW 是 Visio Graphics Service 文件格式，指定了渲染 Web 绘图所需的流和存储。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/web/vdw/)。 |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | 在 Microsoft Visio 中创建的任何绘图或图表，如果以 XML 格式保存，则使用 .VDX 扩展名。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vdx/)。 |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | VSD 文件是使用 Microsoft Visio 应用程序创建的绘图，用于表示各种图形对象及其相互连接。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vsd/)。 |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | 带有 VSDM 扩展名的文件是使用支持宏的 Microsoft Visio 应用程序创建的绘图文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vsdm/)。 |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | 带有 .VSDX 扩展名的文件表示自 Microsoft Office 2013 起引入的 Microsoft Visio 文件格式。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vsdx/)。 |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS 是使用 Microsoft Visio 2007 及更早版本创建的模板文件。模板文件提供可包含在 .VSD Visio 绘图中的绘图对象。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vss/)。 |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | 带有 .VSSM 扩展名的文件是支持宏的 Microsoft Visio 模板文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vssm/)。 |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | 带有 .VSSX 扩展名的文件是使用 Microsoft Visio 2013 及以上版本创建的绘图模板。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vssx/)。 |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | 带有 VST 扩展名的文件是使用 Microsoft Visio 创建的矢量图像文件，并充当创建其他文件的模板。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vst/)。 |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | 带有 VSTM 扩展名的文件是使用 Microsoft Visio 创建的模板文件，支持宏。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vstm/)。 |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | 带有 VSTX 扩展名的文件是使用 Microsoft Visio 2013 及以上版本创建的绘图模板文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vstx/)。 |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | 带有 .VSX 扩展名的文件指的是用于在 Microsoft Visio 中创建图表的包含绘图和形状的模板。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vsx/)。 |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | 带有 VTX 扩展名的文件是以 XML 文件格式保存到磁盘的 Microsoft Visio 绘图模板。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vtx/)。 |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP 由 Google 推出，是一种基于无损和有损压缩的现代光栅网络图像文件格式。它在显著减小图像大小的同时提供相同的图像质量。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/webp/)。 |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | 带有 XLS 扩展名的文件代表 Excel 二进制文件格式。这类文件可以由 Microsoft Excel 以及其他类似的电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/specification/spreadsheet/xls/)。 |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | XLSB 文件格式指定了 Excel 二进制文件格式，它是一组记录和结构的集合，用于指定 Excel 工作簿的内容。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/specification/spreadsheet/xlsb/)。 |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | 带有 XLSM 扩展名的文件是一种支持宏的电子表格文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/specification/spreadsheet/xlsm/)。 |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX 是 Microsoft Excel 文档的知名格式，由 Microsoft 在 Microsoft Office 2007 发布时推出。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/specification/spreadsheet/xlsx/)。 |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | 带有 .XLT 扩展名的文件是使用 Microsoft Excel 创建的模板文件，Microsoft Excel 是 Microsoft Office 套件的一部分电子表格应用程序。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/specification/spreadsheet/xlt/)。 |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | XLTM 文件扩展名表示由 Microsoft Excel 生成的宏启用模板文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/specification/spreadsheet/xltm/)。 |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | 带有 XLTX 扩展名的文件代表基于 Office OpenXML 文件格式规范的 Microsoft Excel 模板文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/specification/spreadsheet/xltx/)。 |

### 备注

此类提供方法以获取 **GroupDocs.Watermark** 支持的所有文件类型列表。**了解更多**

* [Supported Document Formats](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Get supported file formats](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### 另请参阅

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
