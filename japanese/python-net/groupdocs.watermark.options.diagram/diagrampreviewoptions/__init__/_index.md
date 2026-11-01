---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "DiagramPreviewOptions クラスの新しいインスタンスを初期化し、出力ストリームを閉じます。"
type: docs
url: /ja/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

[`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/) クラスの新しいインスタンスを初期化し、出力ストリームを閉じます。

```python
def __init__(self, create_page_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 特定のページプレビュー用のストリームを作成します。 |

## __init__ {#create_page_stream-release_page_stream}

新しい [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/) のインスタンスを初期化し、出力ストリームがクライアントに返され、以降の使用が可能になります。

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 特定のページプレビュー用のストリームを作成します。 |
| release_page_stream | `ReleasePageStream` | ページプレビューの生成が完了したことを通知し、出力ストリームを取得します。 |

### 関連項目
* class [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/)
