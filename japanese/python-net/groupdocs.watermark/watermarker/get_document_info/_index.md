---
title: "get_document_info メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "読み込まれたドキュメントの形式に関する情報を取得します。"
type: docs
url: /ja/python-net/groupdocs.watermark/watermarker/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

読み込まれたドキュメントの形式に関する情報を取得します。

ドキュメント情報の取得について詳しく知る。

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: The instance that contains detected information.

### 例

```python
    from groupdocs.watermark import Watermarker

    with Watermarker("./sample.docx") as watermarker:
        info = watermarker.get_document_info()
        print("File type:", info.file_type)
        print("Pages:", info.page_count)
        print("Size, bytes:", info.size)
    ```

### 関連項目
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
