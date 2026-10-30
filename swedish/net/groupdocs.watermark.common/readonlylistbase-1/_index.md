---
title: "ReadOnlyListBaseT"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Tillhandahåller den abstrakta basklassen för en starkt typad readonly-lista."
type: docs
weight: 110
url: /sv/net/groupdocs.watermark.common/readonlylistbase-1/
---
## ReadOnlyListBase&lt;T&gt; class

Tillhandahåller den abstrakta basklassen för en starkt typad skrivskyddad lista.

```csharp
public abstract class ReadOnlyListBase<T> : IList, IList<T>
```

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av elementet. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Hämtar antalet element som finns i samlingen. |
| virtual [IsReadOnly](../../groupdocs.watermark.common/readonlylistbase-1/isreadonly) { get; } | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Hämtar elementet på det angivna indexet i samlingen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(T) | Avgör om samlingen innehåller ett specifikt objekt. |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() | Returnerar en enumerator som itererar genom en samling. |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(T) | Avgör indexet för ett specifikt objekt i samlingen. |

### Se även

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
