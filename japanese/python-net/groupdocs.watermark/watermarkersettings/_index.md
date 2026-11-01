---
title: "WatermarkerSettings クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "Watermarker の動作をカスタマイズする設定を定義します。"
type: docs
url: /ja/python-net/groupdocs.watermark/watermarkersettings/
is_root: false
weight: 70
---


## WatermarkerSettings class

Watermarker の動作をカスタマイズする設定を定義します。

WatermarkerSettings 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarkersettings/__init__/) | WatermarkerSettings の新しいインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [logger](/watermark/python-net/groupdocs.watermark/watermarkersettings/logger/) | 透かし処理中のイベントとエラーのログ記録に使用されるロガーです。 |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarkersettings/searchable_objects/) | 透かし検索に含める検索可能なオブジェクトです。 |

### フィールド
| フィールド | 説明 |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark/watermarkersettings/default/) | クラスのデフォルト値を取得します。 |

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
`WatermarkerSettings` を使用したタスクガイド：

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### 関連項目
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
