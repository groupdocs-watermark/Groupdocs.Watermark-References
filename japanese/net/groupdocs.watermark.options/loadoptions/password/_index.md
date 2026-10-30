---
title: "Password"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "暗号化されたドキュメントを開くためのパスワードを取得または設定します。"
type: docs
weight: 50
url: /ja/net/groupdocs.watermark.options/loadoptions/password/
---
## LoadOptions.Password property

暗号化されたドキュメントを開くためのパスワードを取得または設定します。

```csharp
public string Password { get; set; }
```

### Property Value

暗号化されたドキュメントを開くためのパスワードです。

### 備考

パスワードは null または空文字列にできます。デフォルト値は null です。コンテンツが暗号化されていない場合は、null または空文字列に設定してください。

### 例

パスワードで保護されたコンテンツをロードします。

```csharp
LoadOptions loadOptions = new LoadOptions
{
    Password = "pwd123"
};
using (Watermarker watermarker = new Watermarker(@"D:\doc.vsdx", loadOptions))
{
    // ...
}
```

### 関連項目

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
