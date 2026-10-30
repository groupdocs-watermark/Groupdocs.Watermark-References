---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "PreviewOptionsgroupdocs.watermark.options/previewoptions クラスの新しいインスタンスを初期化し、出力ストリームを閉じます。"
type: docs
weight: 10
url: /ja/net/groupdocs.watermark.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream) {#constructor}

[`PreviewOptions`](../../previewoptions) クラスの新しいインスタンスを初期化し、出力ストリームを閉じます。

```csharp
public PreviewOptions(CreatePageStream createPageStream)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 特定のページプレビュー用のストリームを作成します。 |

### 関連項目

* delegate [CreatePageStream](../../createpagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

[`PreviewOptions`](../../previewoptions) クラスの新しいインスタンスを初期化し、出力ストリームをクライアントに返してさらに使用できるようにします。

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 特定のページプレビュー用のストリームを作成します。 |
| releasePageStream | ReleasePageStream | ページプレビューの生成が完了したことを通知し、出力ストリームを取得します。 |

### 関連項目

* delegate [CreatePageStream](../../createpagestream)
* delegate [ReleasePageStream](../../releasepagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
