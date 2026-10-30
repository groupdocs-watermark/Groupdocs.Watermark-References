---
title: "RemoveOnlyListBaseT"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Tillhandahåller den abstrakta basklassen för en starkt typad removeonly-lista."
type: docs
weight: 130
url: /sv/net/groupdocs.watermark.common/removeonlylistbase-1/
---
## RemoveOnlyListBase&lt;T&gt; class

Tillhandahåller den abstrakta basklassen för en starkt typad endast‑borttagningslista.

```csharp
public abstract class RemoveOnlyListBase<T> : ReadOnlyListBase<T>
```

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av elementet. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Hämtar antalet element som finns i samlingen. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Hämtar elementet på det angivna indexet i samlingen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() | Tar bort alla objekt från samlingen. |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(T) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(T) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(T) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) | Tar bort objektet på det angivna indexet. |

### Se även

* class [ReadOnlyListBase&lt;T&gt;](../readonlylistbase-1)
* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
