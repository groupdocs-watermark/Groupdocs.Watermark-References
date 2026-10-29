---
title: "FormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل مجموعة قابلة للتعديل من قطع النص المنسق."
type: docs
weight: 2460
url: /ar/net/groupdocs.watermark.search/formattedtextfragmentcollection/
---
## FormattedTextFragmentCollection class

يمثل مجموعة قابلة للتعديل من قطع النص المنسق.

```csharp
public class FormattedTextFragmentCollection : RemoveOnlyListBase<FormattedTextFragment>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CollectionType](../../groupdocs.watermark.search/formattedtextfragmentcollection/collectiontype) { get; } | يحصل على نوع مجموعة الشظايا المنسقة. |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | يحصل على عدد العناصر الموجودة في المجموعة. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | يحصل على العنصر في الفهرس المحدد داخل المجموعة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add#add)(string) | يضيف شظية نص منسقة إلى المجموعة. |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add#add_1)(string, Font) | يضيف شظية نص منسقة إلى المجموعة. |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add#add_2)(string, Font, Color) | يضيف شظية نص منسقة إلى المجموعة. |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add#add_3)(string, Font, Color, Color) | يضيف شظية نص منسقة إلى المجموعة. |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(FormattedTextFragment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(FormattedTextFragment) |  |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert#insert)(int, string) | يدرج شظية نص منسقة في المجموعة عند فهرس معين. |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert#insert_1)(int, string, Font) | يدرج شظية نص منسقة في المجموعة عند فهرس معين. |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert#insert_2)(int, string, Font, Color) | يدرج شظية نص منسقة في المجموعة عند فهرس معين. |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert#insert_3)(int, string, Font, Color, Color) | يدرج شظية نص منسقة في المجموعة عند فهرس معين. |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(FormattedTextFragment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### ملاحظات

تحتوي هذه المجموعة على عناصر من النوع الأساسي [`FormattedTextFragment`](../formattedtextfragment).

### انظر أيضاً

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [FormattedTextFragment](../formattedtextfragment)
* namespace [GroupDocs.Watermark.Search](../../groupdocs.watermark.search)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
