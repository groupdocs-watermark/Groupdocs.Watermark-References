---
title: "IDocumentInfo クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "基本的なドキュメント情報の取得に必要なメソッドを提供します。"
type: docs
url: /ja/python-net/groupdocs.watermark.common/idocumentinfo/
is_root: false
weight: 70
---


## IDocumentInfo class

基本的なドキュメント情報の取得に必要なメソッドを提供します。

詳しくは: ドキュメント情報の取得。

IDocumentInfo 型は次のメンバーを公開します：

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/file_type/) | ファイル形式の説明です。 |
| [is_encrypted](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/is_encrypted/) | このプロパティは、ドキュメントが暗号化されており、開くのにパスワードが必要かどうかを示します。 |
| [page_count](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/page_count/) | 総ページ数です。 |
| [pages](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/pages/) | ドキュメントページの説明コレクションです。 |
| [size](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/size/) | ドキュメントのサイズ（バイト単位）です。 |

### 例

```python
from groupdocs.watermark import Watermarker

with Watermarker(r"D:\input.pdf") as watermarker:
    doc_info = watermarker.get_document_info()
    print(f"Document size: {doc_info.size}")
    print(f"Document format: {doc_info.file_type.file_format_name}")
    print(f"Document contains {doc_info.page_count} pages")
```

### 関連項目
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
