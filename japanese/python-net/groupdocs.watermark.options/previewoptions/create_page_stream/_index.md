---
title: "create_page_stream プロパティ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "各レンダリングページの書き込み可能なストリームを取得するために使用されるページストリーム作成デリゲートです。"
type: docs
url: /ja/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/
is_root: false
weight: 2010
---


## create_page_stream property

各レンダリングページの書き込み可能なストリームを取得するために使用されるページストリーム作成デリゲートです。

GroupDocs.Watermark はドキュメントページを画像としてレンダリングします。ページ番号（`int`）を受け取り、書き込み可能な `io.RawIOBase` ストリームを返す呼び出し可能オブジェクトを提供してください。ライブラリはレンダリングされた画像をストリームに書き込み、ストリームを閉じます。

### Definition:
```python
@property
def create_page_stream(self):
    ...
@create_page_stream.setter
def create_page_stream(self, value):
    ...
```

### 関連項目
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
