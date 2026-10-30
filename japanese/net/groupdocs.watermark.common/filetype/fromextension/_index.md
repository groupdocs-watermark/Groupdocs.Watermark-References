---
title: "FromExtension"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "ファイル拡張子をファイルタイプにマッピングします。"
type: docs
weight: 590
url: /ja/net/groupdocs.watermark.common/filetype/fromextension/
---
## FileType.FromExtension method

ファイル拡張子をファイルタイプにマッピングします。

```csharp
public static FileType FromExtension(string extension)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| extension | String | ファイル拡張子（ピリオド \".\" を含む）。 |

### 戻り値

ファイルタイプがサポートされている場合はそれを返し、そうでない場合はデフォルトの [`Unknown`](../unknown) ファイルタイプを返します。

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *extension* が null または空文字列の場合にスローされます。 |

### 関連項目

* class [FileType](../../filetype)
* namespace [GroupDocs.Watermark.Common](../../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
