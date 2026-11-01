---
title: "protect メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "ドキュメントを変更から保護し、保護パスワードを設定します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/
is_root: false
weight: 1050
---


## protect {#protection_type-password}

ドキュメントを変更から保護し、保護パスワードを設定します。

ドキュメントの内容を編集可能にするには、`WordProcessingLockType.allow_only_form_fields` または `WordProcessingLockType.read_only_with_editable_content` パラメータを使用して透かしを追加する適切なメソッドを使用してください。

```python
def protect(self, protection_type, password):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| protection_type | `WordProcessingProtectionType` | ドキュメントの保護タイプを指定します。 |
| password | `str` | ドキュメントを保護するためのパスワードです。 |

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions
from groupdocs.watermark.contents.word_processing import WordProcessingProtectionType

def protect_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.protect(WordProcessingProtectionType.READ_ONLY, "p@ssw0rd")
        watermarker.save("./output.docx")
```

### 関連項目
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
