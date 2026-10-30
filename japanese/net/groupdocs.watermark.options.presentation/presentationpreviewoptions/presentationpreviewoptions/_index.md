---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "PresentationPreviewOptionsgroupdocs.watermark.options.presentation/presentationpreviewoptions クラスの新しいインスタンスを初期化し、出力ストリームを閉じます。"
type: docs
weight: 10
url: /ja/net/groupdocs.watermark.options.presentation/presentationpreviewoptions/presentationpreviewoptions/
---
## PresentationPreviewOptions(CreatePageStream) {#constructor}

[`PresentationPreviewOptions`](../../presentationpreviewoptions) クラスの新しいインスタンスを初期化し、出力ストリームを閉じます。

```csharp
public PresentationPreviewOptions(CreatePageStream createPageStream)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 特定のページプレビュー用のストリームを作成します。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [PresentationPreviewOptions](../../presentationpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../../)

---

## PresentationPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

[`PresentationPreviewOptions`](../../presentationpreviewoptions) クラスの新しいインスタンスを初期化し、出力ストリームがクライアントに返され、さらに使用できるようにします。

```csharp
public PresentationPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 特定のページプレビュー用のストリームを作成します。 |
| releasePageStream | ReleasePageStream | ページプレビューの生成が完了したことを通知し、出力ストリームを取得します。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [PresentationPreviewOptions](../../presentationpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
