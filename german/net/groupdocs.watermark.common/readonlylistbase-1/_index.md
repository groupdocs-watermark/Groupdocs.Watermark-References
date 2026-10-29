---
title: "ReadOnlyListBaseT"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt die abstrakte Basisklasse für eine stark typisierte schreibgeschützte Liste bereit."
type: docs
weight: 110
url: /de/net/groupdocs.watermark.common/readonlylistbase-1/
---
## ReadOnlyListBase&lt;T&gt; class

Stellt die abstrakte Basisklasse für eine stark typisierte schreibgeschützte Liste bereit.

```csharp
public abstract class ReadOnlyListBase<T> : IList, IList<T>
```

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ des Elements. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Liefert die Anzahl der in der Sammlung enthaltenen Elemente. |
| virtual [IsReadOnly](../../groupdocs.watermark.common/readonlylistbase-1/isreadonly) { get; } | Liefert einen Wert, der angibt, ob die Sammlung schreibgeschützt ist. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Liefert das Element am angegebenen Index in der Sammlung. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(T) | Bestimmt, ob die Sammlung ein bestimmtes Element enthält. |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() | Gibt einen Enumerator zurück, der durch eine Sammlung iteriert. |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(T) | Bestimmt den Index eines bestimmten Elements in der Sammlung. |

### Siehe auch

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
