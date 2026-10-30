---
title: "ReleasePageStream"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "CreatePageStream./createpagestream デリゲートによって作成されたストリームを解放するメソッドを表します。"
type: docs
weight: 2160
url: /ja/net/groupdocs.watermark.options/releasepagestream/
---
## ReleasePageStream delegate

[`CreatePageStream`](../createpagestream) デリゲートによって作成されたストリームを解放するメソッドを表します。

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | 生成されたページプレビューのページ番号です。 |
| pageStream | Stream | 生成されたページプレビューを含むストリームです。 |

### 関連項目

* namespace [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
