---
title: "PdfContent 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示可以放置水印的 PDF 文档。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents.pdf/pdfcontent/
is_root: false
weight: 100
---


## PdfContent class

表示可以放置水印的 PDF 文档。

了解更多：
- [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)
- [Existing objects in PDF document](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+PDF+document)
- [Rasterize document or page](https://docs.groupdocs.com/display/watermarknet/Rasterize+document+or+page)
- [Watermarks in PDF document](https://docs.groupdocs.com/display/watermarknet/Watermarks+in+PDF+document)

PdfContent 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/decrypt/) | 解密内容。 |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/#password) | 使用与用户密码和所有者密码相同的密码加密文档。 |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/#user_password-owner_password-permissions-crypto_algorithm) | 加密内容。 |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt_string/) |  |
| [rasterize](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/#horizontal_resolution-vertical_resolution-image_format) | 将所有内容页转换为图像。 |
| [rasterize_int32](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize_int32/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | 释放当前实例。（继承自 [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)） |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | 根据指定的搜索条件查找图像。搜索在 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) 指定的对象中进行。(inherited from [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (inherited from [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | 根据指定的搜索条件查找可能的水印。搜索在 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) 列出的对象上执行。(inherited from [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (inherited from [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### 属性
| 属性 | 描述 |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/attachments/) | 此 [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/) 的所有附件集合。 |
| [page_margin_type](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/) | 在添加水印期间使用的 PDF 页面边距。 |
| [pages](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/pages/) | 此 [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/) 的所有页面集合。 |

### 示例

```python
from groupdocs.watermark import Watermarker

# 加载 PDF 文件
watermarker = Watermarker("sample.pdf")

# 检索 PDF 内容树
pdf_content = watermarker.get_content()

# 遍历页面并打印其尺寸
for page in pdf_content.pages:
    print(page.width, page.height)
```

### 另请参见
* module [`groupdocs.watermark.contents.pdf`](/watermark/python-net/groupdocs.watermark.contents.pdf/)
