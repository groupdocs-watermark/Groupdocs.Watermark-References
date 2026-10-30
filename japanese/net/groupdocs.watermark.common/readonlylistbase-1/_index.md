---
title: "ReadOnlyListBaseT"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "型安全な読み取り専用リストの抽象基底クラスを提供します。"
type: docs
weight: 110
url: /ja/net/groupdocs.watermark.common/readonlylistbase-1/
---
## ReadOnlyListBase&lt;T&gt; class

型安全な読み取り専用リストの抽象基底クラスを提供します。

```csharp
public abstract class ReadOnlyListBase<T> : IList, IList<T>
```

| パラメーター | 説明 |
| --- | --- |
| T | 要素の型です。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | コレクションに含まれる要素数を取得します。 |
| virtual [IsReadOnly](../../groupdocs.watermark.common/readonlylistbase-1/isreadonly) { get; } | コレクションが読み取り専用かどうかを示す値を取得します。 |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | コレクション内の指定インデックスにある要素を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(T) | コレクションが特定の項目を含むかどうかを判断します。 |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() | コレクションを反復処理する列挙子を返します。 |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(T) | コレクション内の特定項目のインデックスを決定します。 |

### 関連項目

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
