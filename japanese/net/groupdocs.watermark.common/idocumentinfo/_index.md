---
title: "IDocumentInfo"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "基本的なドキュメント情報を取得するために必要なメソッドを定義します。"
type: docs
weight: 70
url: /ja/net/groupdocs.watermark.common/idocumentinfo/
---
## IDocumentInfo interface

基本的なドキュメント情報を取得するために必要なメソッドを定義します。

```csharp
public interface IDocumentInfo
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FileType](../../groupdocs.watermark.common/idocumentinfo/filetype) { get; } | ファイル形式の説明を取得します。 |
| [IsEncrypted](../../groupdocs.watermark.common/idocumentinfo/isencrypted) { get; } | ドキュメントが暗号化されており、開くのにパスワードが必要かどうかを示す値を取得します。 |
| [PageCount](../../groupdocs.watermark.common/idocumentinfo/pagecount) { get; } | 総ページ数を取得します。 |
| [Pages](../../groupdocs.watermark.common/idocumentinfo/pages) { get; } | ドキュメントページの説明コレクションを取得します。 |
| [Size](../../groupdocs.watermark.common/idocumentinfo/size) { get; } | ドキュメントのサイズ（バイト単位）を取得します。 |

### 備考

**Learn more**

* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### 例

次の例は、[`IDocumentInfo`](../idocumentinfo) を使用して一般的なドキュメント情報を取得する方法を示しています。

```csharp
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### 関連項目

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
