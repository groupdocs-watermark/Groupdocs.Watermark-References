---
title: "EmailEmbeddedObjectCollection"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een verzameling van ingebedde objecten in een e‑mailbericht voor."
type: docs
weight: 380
url: /nl/net/groupdocs.watermark.contents.email/emailembeddedobjectcollection/
---
## EmailEmbeddedObjectCollection class

Stelt een verzameling van ingebedde objecten in een e‑mailbericht voor.

```csharp
public class EmailEmbeddedObjectCollection : RemoveOnlyListBase<EmailEmbeddedObject>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Haalt het aantal elementen op dat in de collectie zit. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Haalt een waarde op die aangeeft of de collectie alleen-lezen is. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Haalt het element op op de opgegeven index in de collectie. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.email/emailembeddedobjectcollection/add)(byte[], string) | Voegt een ingebedde bron toe aan de [`EmailContent`](../emailcontent). |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(EmailEmbeddedObject) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(EmailEmbeddedObject) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(EmailEmbeddedObject) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Opmerkingen

Deze collectie bevat items van het type [`EmailEmbeddedObject`](../emailembeddedobject).

### Zie ook

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [EmailEmbeddedObject](../emailembeddedobject)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
