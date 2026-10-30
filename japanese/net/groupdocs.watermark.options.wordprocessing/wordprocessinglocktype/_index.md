---
title: "WordProcessingLockType"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "Word 文書における透かしロックタイプを指定します。"
type: docs
weight: 2350
url: /ja/net/groupdocs.watermark.options.wordprocessing/wordprocessinglocktype/
---
## WordProcessingLockType enumeration

Word 文書における透かしロックタイプを指定します。

```csharp
public enum WordProcessingLockType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| AllowOnlyRevisions | `0` | ユーザーはドキュメントに改訂マークのみを追加できます。 |
| AllowOnlyComments | `1` | ユーザーはドキュメント内のコメントのみを編集できます。 |
| AllowOnlyFormFields | `2` | ユーザーはドキュメントのフォームフィールドにデータのみ入力できます。 |
| ReadOnly | `3` | ドキュメント全体が読み取り専用です。 |
| ReadOnlyWithEditableContent | `4` | ドキュメントは読み取り専用ですが、透かしを除くすべてのコンテンツは編集可能としてマークされています。 |
| NoLock | `-1` | 透かしとドキュメントのロックをすべて無効にします。 |

### 関連項目

* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
