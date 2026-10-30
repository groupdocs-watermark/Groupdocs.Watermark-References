---
title: "GetDocumentInfo"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "読み込まれたドキュメントの形式に関する情報を取得します。"
type: docs
weight: 70
url: /ja/net/groupdocs.watermark/watermarker/getdocumentinfo/
---
## Watermarker.GetDocumentInfo method

読み込まれたドキュメントの形式に関する情報を取得します。

```csharp
public IDocumentInfo GetDocumentInfo()
```

### 戻り値

検出された情報を含む[`IDocumentInfo`](../../../groupdocs.watermark.common/idocumentinfo)インスタンスです。

### 備考

ドキュメント情報の取得について詳しくは、[Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)をご覧ください。

### 例

サポートされている任意のタイプのドキュメントに関する情報を取得します。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.ppt"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### 関連項目

* interface [IDocumentInfo](../../../groupdocs.watermark.common/idocumentinfo)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
