---
title: "EmailPreviewOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "EmailPreviewOptionsgroupdocs.watermark.options.email/emailpreviewoptions クラスの新しいインスタンスを初期化し、出力ストリームを閉じます。"
type: docs
weight: 10
url: /ja/net/groupdocs.watermark.options.email/emailpreviewoptions/emailpreviewoptions/
---
## EmailPreviewOptions(CreatePageStream) {#constructor}

[`EmailPreviewOptions`](../../emailpreviewoptions) クラスの新しいインスタンスを初期化し、出力ストリームを閉じます。

```csharp
public EmailPreviewOptions(CreatePageStream createPageStream)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 特定のページプレビュー用のストリームを作成します。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [EmailPreviewOptions](../../emailpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../../)

---

## EmailPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

[`EmailPreviewOptions`](../../emailpreviewoptions) クラスの新しいインスタンスを初期化し、出力ストリームをクライアントに返してさらに使用できるようにします。

```csharp
public EmailPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 特定のページプレビュー用のストリームを作成します。 |
| releasePageStream | ReleasePageStream | ページプレビューの生成が完了したことを通知し、出力ストリームを取得します。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [EmailPreviewOptions](../../emailpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
