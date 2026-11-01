---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "出力ストリームが閉じられるようにする WordProcessingPreviewOptions の新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.options.word_processing/wordprocessingpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

出力ストリームが閉じられるようにする WordProcessingPreviewOptions の新しいインスタンスを初期化します。

```python
def __init__(self, create_page_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 特定のページプレビュー用のストリームを作成します。 |

## __init__ {#create_page_stream-release_page_stream}

出力ストリームがクライアントに返され、さらに使用できるようにする WordProcessingPreviewOptions クラスの新しいインスタンスを初期化します。

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 特定のページプレビュー用のストリームを作成します。 |
| release_page_stream | `ReleasePageStream` | ページプレビューの生成が完了したことを通知し、出力ストリームを取得します。 |

### 関連項目
* class [`WordProcessingPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingpreviewoptions/)
