---
title: "EmailAttachment"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "メールメッセージに添付されたファイルを表します。"
type: docs
weight: 320
url: /ja/net/groupdocs.watermark.contents.email/emailattachment/
---
## EmailAttachment class

メールメッセージに添付されたファイルを表します。

```csharp
public class EmailAttachment : EmailAttachmentBase
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Content](../../groupdocs.watermark.contents.email/emailattachmentbase/content) { get; set; } | 添付ファイルの内容を取得または設定します。 |
| [ContentId](../../groupdocs.watermark.contents.email/emailattachmentbase/contentid) { get; } | この [`EmailAttachmentBase`](../emailattachmentbase) のコンテンツ ID を取得します。 |
| [MediaType](../../groupdocs.watermark.contents.email/emailattachmentbase/mediatype) { get; } | この [`EmailAttachmentBase`](../emailattachmentbase) のメディアタイプを取得します。 |
| [Name](../../groupdocs.watermark.contents.email/emailattachment/name) { get; set; } | 添付ファイルの名前を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | 添付ファイルからコンテンツを読み込みます。 |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | 指定されたロードオプションを使用して、添付ファイルからコンテンツを読み込みます。 |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | 指定されたロードオプションと設定を使用して、添付ファイルからコンテンツを読み込みます。 |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | 添付ファイルに保存されているドキュメントに関する情報を取得します。 |

### 関連項目

* class [EmailAttachmentBase](../emailattachmentbase)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
