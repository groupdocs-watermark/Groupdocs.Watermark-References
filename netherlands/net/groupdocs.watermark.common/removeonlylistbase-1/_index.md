---
title: "RemoveOnlyListBaseT"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Biedt de abstracte basisklasse voor een sterk getypeerde removeonly-lijst."
type: docs
weight: 130
url: /nl/net/groupdocs.watermark.common/removeonlylistbase-1/
---
## RemoveOnlyListBase&lt;T&gt; class

Biedt de abstracte basisklasse voor een sterk getypeerde alleen-verwijderlijst.

```csharp
public abstract class RemoveOnlyListBase<T> : ReadOnlyListBase<T>
```

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van het element. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Haalt het aantal elementen op dat in de collectie zit. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Haalt een waarde op die aangeeft of de collectie alleen-lezen is. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Haalt het element op op de opgegeven index in de collectie. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() | Verwijdert alle items uit de collectie. |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(T) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(T) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(T) | Verwijdert de eerste voorkoming van een specifiek object uit de collectie. |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) | Verwijdert het item op de opgegeven index. |

### Zie ook

* class [ReadOnlyListBase&lt;T&gt;](../readonlylistbase-1)
* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
