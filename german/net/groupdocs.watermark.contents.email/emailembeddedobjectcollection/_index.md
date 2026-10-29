---
title: "EmailEmbeddedObjectCollection"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt eine Sammlung eingebetteter Objekte in einer E‑Mail-Nachricht dar."
type: docs
weight: 380
url: /de/net/groupdocs.watermark.contents.email/emailembeddedobjectcollection/
---
## EmailEmbeddedObjectCollection class

Stellt eine Sammlung eingebetteter Objekte in einer E‑Mail-Nachricht dar.

```csharp
public class EmailEmbeddedObjectCollection : RemoveOnlyListBase<EmailEmbeddedObject>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Liefert die Anzahl der in der Sammlung enthaltenen Elemente. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Liefert einen Wert, der angibt, ob die Sammlung schreibgeschützt ist. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Liefert das Element am angegebenen Index in der Sammlung. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.email/emailembeddedobjectcollection/add)(byte[], string) | Fügt eine eingebettete Ressource zu dem [`EmailContent`](../emailcontent) hinzu. |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(EmailEmbeddedObject) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(EmailEmbeddedObject) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(EmailEmbeddedObject) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Hinweise

Diese Sammlung enthält Elemente des Typs [`EmailEmbeddedObject`](../emailembeddedobject).

### Siehe auch

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [EmailEmbeddedObject](../emailembeddedobject)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
