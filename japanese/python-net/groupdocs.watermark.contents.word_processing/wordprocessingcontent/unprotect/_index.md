---
title: "unprotect メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "パスワードに関係なくドキュメントの保護を解除します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/
is_root: false
weight: 1090
---


## unprotect

パスワードに関係なくドキュメントの保護を解除します。

```python
def unprotect(self):
    ...
```

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

def unprotect_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.unprotect()
        watermarker.save("./output.docx")

if __name__ == "__main__":
    unprotect_document()
```

### 関連項目
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
