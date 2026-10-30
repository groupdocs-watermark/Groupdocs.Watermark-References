---
title: "SizingType"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "透かしサイズの計算方法を指定します。"
type: docs
weight: 3300
url: /ja/net/groupdocs.watermark.watermarks/sizingtype/
---
## SizingType enumeration

透かしサイズの計算方法を指定します。

```csharp
public enum SizingType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Auto | `0` | 透かしはコンテンツに応じて自動的にサイズ設定されるべきです。 |
| Absolute | `1` | 透かしは正確な [`Width`](../../groupdocs.watermark/watermark/width) と [`Height`](../../groupdocs.watermark/watermark/height) にサイズ設定されるべきです。 |
| ScaleToParentDimensions | `2` | 透かしは指定された [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor) を使用して、親の寸法に対してスケーリングされるべきです。 |
| ScaleToParentArea | `3` | 透かしは指定された [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor) を使用して、親領域に対してスケーリングされるべきです。 |

### 関連項目

* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
