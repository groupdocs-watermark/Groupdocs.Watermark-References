---
title: "PresentationLoadOptions クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "プレゼンテーション ドキュメントの読み込みオプションを表します。"
type: docs
url: /ja/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/
is_root: false
weight: 30
---


## PresentationLoadOptions class

プレゼンテーション ドキュメントの読み込みオプションを表します。

PresentationLoadOptions 型は以下のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/) | [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/) クラスの新しいインスタンスを初期化します。 |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/#password) | 指定されたパスワードで PresentationLoadOptions クラスの新しいインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | ファイルの種類で、フォーマットを示します（例: docx、pdf、xlsx など）。(継承元: [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | ドキュメントのフォーマットファミリで、タイプを示します（例: Image、Pdf、Spreadsheet など）。(継承元: [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | 暗号化されたドキュメントを開くためのパスワードです。(継承元: [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### フィールド
| フィールド | 説明 |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/default/) | クラスのデフォルト値を取得します。 |

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
    # ドキュメントを操作する
    pass
```

### 関連項目
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
