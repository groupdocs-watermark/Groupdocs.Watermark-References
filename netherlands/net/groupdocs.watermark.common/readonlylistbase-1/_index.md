---
title: "ReadOnlyListBaseT"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Biedt de abstracte basisklasse voor een sterk getypeerde readonly-lijst."
type: docs
weight: 110
url: /nl/net/groupdocs.watermark.common/readonlylistbase-1/
---
## ReadOnlyListBase&lt;T&gt; class

Biedt de abstracte basisklasse voor een sterk getypeerde alleen-lezen lijst.

```csharp
public abstract class ReadOnlyListBase<T> : IList, IList<T>
```

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van het element. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Haalt het aantal elementen op dat in de collectie zit. |
| virtual [IsReadOnly](../../groupdocs.watermark.common/readonlylistbase-1/isreadonly) { get; } | Haalt een waarde op die aangeeft of de collectie alleen-lezen is. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Haalt het element op op de opgegeven index in de collectie. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(T) | Bepaalt of de collectie een specifiek item bevat. |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() | Retourneert een enumerator die door een collectie iterereert. |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(T) | Bepaalt de index van een specifiek item in de collectie. |

### Zie ook

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
