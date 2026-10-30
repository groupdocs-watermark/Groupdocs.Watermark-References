---
title: "EmailContent"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "メールメッセージを表します。"
type: docs
weight: 360
url: /ja/net/groupdocs.watermark.contents.email/emailcontent/
---
## EmailContent class

メールメッセージを表します。

```csharp
public sealed class EmailContent : Content
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.email/emailcontent/attachments) { get; } | メールメッセージのすべての添付ファイルのコレクションを取得します。 |
| [Bcc](../../groupdocs.watermark.contents.email/emailcontent/bcc) { get; } | メールメッセージの BCC（ブラインド カーボン コピー）受信者のコレクションを取得します。 |
| [Body](../../groupdocs.watermark.contents.email/emailcontent/body) { get; set; } | メッセージ本文のプレーンテキスト表現を取得または設定します。 |
| [BodyType](../../groupdocs.watermark.contents.email/emailcontent/bodytype) { get; } | メールメッセージ本文のタイプを取得します。 |
| [Cc](../../groupdocs.watermark.contents.email/emailcontent/cc) { get; } | メールメッセージの CC（カーボンコピー）受信者のコレクションを取得します。 |
| [EmbeddedObjects](../../groupdocs.watermark.contents.email/emailcontent/embeddedobjects) { get; } | メールメッセージのすべての埋め込みオブジェクトのコレクションを取得します。 |
| [From](../../groupdocs.watermark.contents.email/emailcontent/from) { get; } | メールメッセージの送信元アドレスを取得します。 |
| [HtmlBody](../../groupdocs.watermark.contents.email/emailcontent/htmlbody) { get; set; } | メッセージ本文の HTML 表現を取得または設定します。 |
| [Subject](../../groupdocs.watermark.contents.email/emailcontent/subject) { get; set; } | メールメッセージの件名を取得または設定します。 |
| [To](../../groupdocs.watermark.contents.email/emailcontent/to) { get; } | メールメッセージの受信者のコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | 現在のインスタンスを破棄します。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | コンテンツ内のすべての画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 指定された検索条件に従って画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | コンテンツ内のすべての可能な透かしを検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 指定された検索条件に従って可能性のある透かしを検索します。検索は[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects)で指定されたオブジェクトで実行されます。 |

### 備考

**Learn more:**

* [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
* [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
* [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

### 関連項目

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
