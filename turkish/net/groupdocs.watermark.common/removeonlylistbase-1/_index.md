---
title: RemoveOnlyListBaseT
second_title: .NET API Başvurusu için GroupDocs.Watermark
description: Kesin olarak yazılan bir saltkaldır listesi için soyut temel sınıfı sağlar.
type: docs
weight: 100
url: /tr/net/groupdocs.watermark.common/removeonlylistbase-1/
---
## RemoveOnlyListBase&lt;T&gt; class

Kesin olarak yazılan bir salt-kaldır listesi için soyut temel sınıfı sağlar.

```csharp
public abstract class RemoveOnlyListBase<T> : ReadOnlyListBase<T>
```

| Parametre | Tanım |
| --- | --- |
| T | Elemanın türü. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Koleksiyonda bulunan öğelerin sayısını alır. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Koleksiyonun salt okunur olup olmadığını gösteren bir değer alır. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Koleksiyonda belirtilen dizindeki öğeyi alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() | Koleksiyondaki tüm öğeleri kaldırır. |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(T) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(T) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(T) | Belirli bir nesnenin ilk geçtiği yeri koleksiyondan kaldırır. |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) | Belirtilen dizindeki öğeyi kaldırır. |

### Ayrıca bakınız

* class [ReadOnlyListBase&lt;T&gt;](../readonlylistbase-1)
* ad alanı [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* toplantı [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
