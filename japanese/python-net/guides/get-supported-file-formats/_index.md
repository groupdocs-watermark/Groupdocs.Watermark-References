---
title: "サポートされているファイル形式を取得する"
linkTitle: "Get supported file formats"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: ".NET 経由で Python 用の GroupDocs.Watermark がサポートするすべてのファイル形式を一覧表示します。"
type: docs
url: /ja/python-net/guides/get-supported-file-formats/
is_root: false
weight: 130
---


GroupDocs.Watermark がサポートするファイル形式の完全なリストをすばやく取得できます。これにより、ドキュメントを処理する前にアプリケーションが動的に互換性をチェックでき、たとえばユーザーがアップロードしたファイルの検証に役立ちます。

## List supported file formats

`FileType.get_supported_file_types()` はサポートされているすべてのファイルタイプを返します。各項目は `extension` と分かりやすい説明を提供します。

{{< tabs \"code-example-get-supported-file-formats\">}}
{{< tab \"list_supported_formats.py\" >}}
```python
from groupdocs.watermark.common import FileType

def list_supported_formats():
    # ライブラリが開くことのできるすべてのファイルタイプを列挙してください
    supported_file_types = FileType.get_supported_file_types()
    for file_type in sorted(supported_file_types, key=lambda x: x.extension):
        print(file_type)

if __name__ == "__main__":
    list_supported_formats()
```
{{< /tab >}}
{{< tab \"list-supported-formats.txt\" >}}
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
