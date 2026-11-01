---
title: "SearchableObjects クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "透かし検索に含めるドキュメントオブジェクトを指定します。"
type: docs
url: /ja/python-net/groupdocs.watermark.search.objects/searchableobjects/
is_root: false
weight: 50
---


## SearchableObjects class

透かし検索に含めるドキュメントオブジェクトを指定します。

詳しくは:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

SearchableObjects 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/) | 新しい [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) クラスのインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [diagram_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/diagram_searchable_objects/) | 透かし検索に含める Visio ドキュメント内のオブジェクト。 |
| [email_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/email_searchable_objects/) | 透かし検索に含めるメールメッセージ内のオブジェクト。 |
| [pdf_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/pdf_searchable_objects/) | 透かし検索に含める PDF ドキュメント内のオブジェクト。 |
| [presentation_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/presentation_searchable_objects/) | 透かし検索に含める PowerPoint ドキュメント内のオブジェクト。 |
| [spreadsheet_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/spreadsheet_searchable_objects/) | 透かし検索に含める Excel ドキュメント内のオブジェクト。 |
| [word_processing_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/word_processing_searchable_objects/) | 透かし検索に含める Word ドキュメント内のオブジェクト。 |

### 例

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import (
    SearchableObjects, WordProcessingSearchableObjects, PdfSearchableObjects,
)

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS
    | WordProcessingSearchableObjects.TEXT,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

with Watermarker("./document.pdf", settings) as watermarker:
    possible = watermarker.search()
    print("Found", len(possible), "possible watermark(s)")
```

### Guides
`SearchableObjects` を使用したタスク ガイド：

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### 関連項目
* module [`groupdocs.watermark.search.objects`](/watermark/python-net/groupdocs.watermark.search.objects/)
