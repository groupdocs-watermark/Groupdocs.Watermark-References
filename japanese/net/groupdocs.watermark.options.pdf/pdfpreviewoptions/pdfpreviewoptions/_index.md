---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "PdfPreviewOptionsgroupdocs.watermark.options.pdf/pdfpreviewoptions クラスの新しいインスタンスを初期化し、出力ストリームを閉じます。"
type: docs
weight: 10
url: /ja/net/groupdocs.watermark.options.pdf/pdfpreviewoptions/pdfpreviewoptions/
---
## PdfPreviewOptions(CreatePageStream) {#constructor}

[`PdfPreviewOptions`](../../pdfpreviewoptions) クラスの新しいインスタンスを初期化し、出力ストリームを閉じます。

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 特定のページプレビュー用のストリームを作成します。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../../)

---

## PdfPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

[`PdfPreviewOptions`](../../pdfpreviewoptions) クラスの新しいインスタンスを初期化し、出力ストリームがクライアントに返され、さらに使用できるようにします。

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 特定のページプレビュー用のストリームを作成します。 |
| releasePageStream | ReleasePageStream | ページプレビューの生成が完了したことを通知し、出力ストリームを取得します。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
