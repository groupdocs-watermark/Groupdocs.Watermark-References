---
title: "RemoveOnlyListBaseT"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "型安全な removeonly リストの抽象基底クラスを提供します。"
type: docs
weight: 130
url: /ja/net/groupdocs.watermark.common/removeonlylistbase-1/
---
## RemoveOnlyListBase&lt;T&gt; class

型安全な削除専用リストの抽象基底クラスを提供します。

```csharp
public abstract class RemoveOnlyListBase<T> : ReadOnlyListBase<T>
```

| パラメーター | 説明 |
| --- | --- |
| T | 要素の型です。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | コレクションに含まれる要素数を取得します。 |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | コレクションが読み取り専用かどうかを示す値を取得します。 |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | コレクション内の指定インデックスにある要素を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() | コレクションからすべての項目を削除します。 |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(T) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(T) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(T) | コレクションから特定オブジェクトの最初の出現を削除します。 |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) | 指定されたインデックスの項目を削除します。 |

### 関連項目

* class [ReadOnlyListBase&lt;T&gt;](../readonlylistbase-1)
* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
