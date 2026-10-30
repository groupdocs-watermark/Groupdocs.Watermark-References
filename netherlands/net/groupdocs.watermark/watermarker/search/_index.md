---
title: "Search"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Zoekt alle mogelijke watermerken in het document."
type: docs
weight: 110
url: /nl/net/groupdocs.watermark/watermarker/search/
---
## Search() {#search}

Zoekt alle mogelijke watermerken in het document.

```csharp
public PossibleWatermarkCollection Search()
```

### Retourwaarde

De collectie van mogelijke watermerken.

### Opmerkingen

Het zoeken wordt uitgevoerd in objecten gespecificeerd in [`SearchableObjects`](../searchableobjects).

Meer informatie over het zoeken naar watermerken [Zoeken naar watermerken](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Voorbeelden

Tel de mogelijke watermerken in een document van elk ondersteund type.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    PossibleWatermarkCollection watermarks = watermarker.Search();
    Console.WrileLine(watermarks.Count);
}
```

### Zie ook

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Search(SearchCriteria) {#search_1}

Zoekt mogelijke watermerken volgens de opgegeven zoekcriteria.

```csharp
public PossibleWatermarkCollection Search(SearchCriteria searchCriteria)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchCriteria | SearchCriteria | De te gebruiken zoekcriteria. |

### Retourwaarde

De collectie van mogelijke watermerken.

### Opmerkingen

Het zoeken wordt uitgevoerd in objecten gespecificeerd in [`SearchableObjects`](../searchableobjects).

Meer informatie over het zoeken naar watermerken [Zoeken naar watermerken](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Voorbeelden

Zoek en verwijder alle mogelijke watermerken die specifieke tekst of afbeelding bevatten uit een document van elk ondersteund type.

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

### Zie ook

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [SearchCriteria](../../../groupdocs.watermark.search.searchcriteria/searchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
