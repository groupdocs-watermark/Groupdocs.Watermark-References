---
title: "功能概览"
linkTitle: "Features overview"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "GroupDocs.Watermark for Python via .NET 通过单一的、与格式无关的 API 添加、搜索和移除文本和图像水印 —— 支持特定格式的定位、内容树编辑、锁定和光栅化。"
type: docs
url: /zh/python-net/guides/features-overview/
is_root: false
weight: 30
---


GroupDocs.Watermark for Python via .NET 在广泛的 [受支持文档格式](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/) 中添加、搜索和移除水印。每个操作遵循相同的工作流：使用 [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) 打开文档，调用 `add()`, `search()` 或 `remove()`, 然后 `save()` 将结果保存回原始格式。以下功能可以在一次处理过程中自由组合。

## Text and image watermarks

添加带样式的文本或图像水印，可全面控制字体、颜色、不透明度、旋转、对齐和尺寸。图像水印可以从文件或流中加载。参见 [添加文本水印](/watermark/python-net/guides/add-text/) 和 [添加图像水印](/watermark/python-net/guides/add-image/)。

## Customization and tiling

使用绝对坐标或相对父级的对齐和边距来定位水印，按页面比例缩放，旋转，并在整页以重复模式平铺。参见 [自定义水印](/watermark/python-net/guides/customize/)、[添加重复水印](/watermark/python-net/guides/adding-repeated-watermarks/) 和 [添加文本水印](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/)。

## Format-specific placement

使用适用于各格式的选项放置水印——PDF 人工制品、批注和仅打印批注；演示文稿幻灯片、母版、布局和备注；电子表格工作表、背景以及页眉/页脚；Visio 页面；以及受锁定的 Word 部分和页面。参见 [向 PDF 文档添加水印](https://docs.groupdocs.com/watermark/python-net/add-watermarks-to-pdf-documents/) 以及 [开发者指南](https://docs.groupdocs.com/watermark/python-net/adding-watermarks/) 中的其他格式主题。

## Searching, modifying, and removing

通过精确文本、正则表达式、图像相似度或文本格式，在文档中查找已存在的水印——包括第三方工具添加的水印——并可使用 `and_`/`or_`/`not_` 组合条件。找到后，可替换其文本或图像，或将其移除。参见 [搜索水印](/watermark/python-net/guides/searching-watermarks/)、[修改已发现水印属性](https://docs.groupdocs.com/watermark/python-net/modifying-found-watermark-properties/) 和 [移除已发现水印](https://docs.groupdocs.com/watermark/python-net/removing-found-watermarks/)。

## Working with existing content

`Watermarker.get_content()` 公开了特定格式的内容树，您可以检查和编辑现有形状、PDF XObject/人工制品/批注、附件、背景以及页眉/页脚——并且可以使用 `get_images()` 为文档内部嵌入的图像添加水印。参见 [向文档内的图像添加水印](https://docs.groupdocs.com/watermark/python-net/adding-watermark-to-images-inside-a-document/)。

## Tamper resistance

通过锁定水印、保护 Word 文档、添加仅打印的 PDF 批注或对 PDF 页面进行光栅化，使水印难以被移除。参见 [在文字处理文档中锁定水印](https://docs.groupdocs.com/watermark/python-net/locking-watermark-in-word-processing-document/) 和 [光栅化文档或页面](https://docs.groupdocs.com/watermark/python-net/rasterize-document-or-page/)。

## Document inspection

在不修改文档的情况下读取文档的文件类型、页数和大小，并列出库支持的所有文件格式。参见 [获取文档信息](/watermark/python-net/guides/get-document-info/) 和 [获取受支持的文件格式](/watermark/python-net/guides/get-supported-file-formats/)。

## On-premise

GroupDocs.Watermark for Python via .NET 完全运行在您自己的基础设施上——文档永不离开您的环境。该包是一个自包含的 wheel，捆绑了所有必需的内容，无需安装 Microsoft Office、OpenOffice 或其他运行时。参见 [系统要求](https://docs.groupdocs.com/watermark/python-net/system-requirements/) 了解受支持的平台和本机依赖项。
