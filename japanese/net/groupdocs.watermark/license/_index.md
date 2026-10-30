---
title: "License"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "コンポーネントのライセンスを付与するメソッドを提供します。"
type: docs
weight: 1680
url: /ja/net/groupdocs.watermark/license/
---
## License class

コンポーネントのライセンスを付与するメソッドを提供します。

```csharp
public sealed class License
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [License](license)() | [`License`](../license) クラスの新しいインスタンスを初期化します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense)(Stream) | コンポーネントにライセンスを適用します。 |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense_1)(string) | コンポーネントにライセンスを適用します。 |

### 備考

* More about licensing: [GroupDocs Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### 例

この例では、ローカルファイルからライセンスを設定する方法を示します。

```csharp
// License クラスを初期化します。
License license = new License();

// .lic ファイルへのパスを設定します。
license.SetLicense("C:\\GroupDocs.Watermark.lic");
```

### 関連項目

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
