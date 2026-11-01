---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "WatermarkResult クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.internal/watermarkresult/__init__/
is_root: false
weight: 10
---


## __init__

[`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/) クラスの新しいインスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#source_document_size-processing_time-final_document_size-number_watermarks_applied}

特定の値を使用して新しい WatermarkResult インスタンスを初期化します。

```python
def __init__(self, source_document_size, processing_time, final_document_size, number_watermarks_applied):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| source_document_size | `int` | 元のドキュメントのサイズ（バイト単位）。 |
| processing_time | `timedelta` | ミリ秒単位の処理時間。 |
| final_document_size | `int` | 最終的に処理されたドキュメントのサイズ（バイト単位）。 |
| number_watermarks_applied | `int` | ドキュメントに適用された透かしの総数。 |

### 関連項目
* class [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/)
