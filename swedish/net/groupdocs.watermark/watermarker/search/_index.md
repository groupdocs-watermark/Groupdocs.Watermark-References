---
title: "Sök"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Söker igenom alla möjliga vattenmärken i dokumentet."
type: docs
weight: 110
url: /sv/net/groupdocs.watermark/watermarker/search/
---
## Search() {#search}

Söker igenom alla möjliga vattenmärken i dokumentet.

```csharp
public PossibleWatermarkCollection Search()
```

### Returvärde

Samlingen av möjliga vattenmärken.

### Anmärkningar

Sökningen utförs i objekt som anges i [`SearchableObjects`](../searchableobjects).

Läs mer om att söka vattenmärken [Söka vattenmärken](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Exempel

Räkna de möjliga vattenmärkena i ett dokument av någon stödd typ.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    PossibleWatermarkCollection watermarks = watermarker.Search();
    Console.WrileLine(watermarks.Count);
}
```

### Se även

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Search(SearchCriteria) {#search_1}

Söker möjliga vattenmärken enligt angivna sökkriterier.

```csharp
public PossibleWatermarkCollection Search(SearchCriteria searchCriteria)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchCriteria | SearchCriteria | Sökkriterierna att använda. |

### Returvärde

Samlingen av möjliga vattenmärken.

### Anmärkningar

Sökningen utförs i objekt som anges i [`SearchableObjects`](../searchableobjects).

Läs mer om att söka vattenmärken [Söka vattenmärken](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Exempel

Hitta och ta bort alla möjliga vattenmärken som innehåller särskild text eller bild från ett dokument av någon stödd typ.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    watermarks.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### Se även

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [SearchCriteria](../../../groupdocs.watermark.search.searchcriteria/searchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
