---
title: "create_page_stream 属性"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "用于获取每个渲染页面的可写流的页面流创建委托。"
type: docs
url: /zh/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/
is_root: false
weight: 2010
---


## create_page_stream property

用于获取每个渲染页面的可写流的页面流创建委托。

GroupDocs.Watermark 将文档页面渲染为图像。提供一个可调用对象，接受页面编号（`int`）并返回可写的 `io.RawIOBase` 流；库会将渲染的图像写入该流并关闭它。

### Definition:
```python
@property
def create_page_stream(self):
    ...
@create_page_stream.setter
def create_page_stream(self, value):
    ...
```

### 另请参见
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
