---
title: "获取支持的文件格式"
linkTitle: "Get supported file formats"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "列出通过 .NET 的 Python 版 GroupDocs.Watermark 支持的所有文件格式。"
type: docs
url: /zh/python-net/guides/get-supported-file-formats/
is_root: false
weight: 130
---


快速获取 GroupDocs.Watermark 支持的完整文件格式列表。这使您的应用程序在处理文档之前能够动态检查兼容性，例如验证用户上传的文件。

## List supported file formats

`FileType.get_supported_file_types()` 返回所有受支持的文件类型。每个条目都提供其 `extension` 和友好的描述。

{{< tabs "code-example-get-supported-file-formats">}}
{{< tab "list_supported_formats.py" >}}
```python
from groupdocs.watermark.common import FileType

def list_supported_formats():
    # 列举库可以打开的所有文件类型
    supported_file_types = FileType.get_supported_file_types()
    for file_type in sorted(supported_file_types, key=lambda x: x.extension):
        print(file_type)

if __name__ == "__main__":
    list_supported_formats()
```
{{< /tab >}}
{{< tab "list-supported-formats.txt" >}}
```text
Bmp (.bmp) - Image
Doc (.doc) - WordProcessing
Docm (.docm) - WordProcessing
Docx (.docx) - WordProcessing
Dot (.dot) - WordProcessing
Dotm (.dotm) - WordProcessing
Dotx (.dotx) - WordProcessing
Eml (.eml) - Email
Emlx (.emlx) - Email
Gif (.gif) - Image
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/get-supported-file-formats/list_supported_formats/list-supported-formats.txt)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Build flexible applications that validate user-uploaded files and tell the user whether watermarking is supported.
