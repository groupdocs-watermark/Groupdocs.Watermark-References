---
title: "Search"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Durchsucht das Dokument nach allen möglichen Wasserzeichen."
type: docs
weight: 110
url: /de/net/groupdocs.watermark/watermarker/search/
---
## Search() {#search}

Durchsucht das Dokument nach allen möglichen Wasserzeichen.

```csharp
public PossibleWatermarkCollection Search()
```

### Rückgabewert

Die Sammlung möglicher Wasserzeichen.

### Hinweise

Die Suche wird in den in [`SearchableObjects`](../searchableobjects) angegebenen Objekten durchgeführt.

Erfahren Sie mehr über das Suchen von Wasserzeichen [Suchen von Wasserzeichen](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Beispiele

Zählen Sie die möglichen Wasserzeichen in einem Dokument eines beliebigen unterstützten Typs.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    PossibleWatermarkCollection watermarks = watermarker.Search();
    Console.WrileLine(watermarks.Count);
}
```

### Siehe auch

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Search(SearchCriteria) {#search_1}

Durchsucht mögliche Wasserzeichen gemäß den angegebenen Suchkriterien.

```csharp
public PossibleWatermarkCollection Search(SearchCriteria searchCriteria)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| searchCriteria | SearchCriteria | Die zu verwendenden Suchkriterien. |

### Rückgabewert

Die Sammlung möglicher Wasserzeichen.

### Hinweise

Die Suche wird in den in [`SearchableObjects`](../searchableobjects) angegebenen Objekten durchgeführt.

Erfahren Sie mehr über das Suchen von Wasserzeichen [Suchen von Wasserzeichen](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Beispiele

Finden und entfernen Sie alle möglichen Wasserzeichen, die bestimmten Text oder ein Bild enthalten, aus einem Dokument eines beliebigen unterstützten Typs.

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

### Siehe auch

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [SearchCriteria](../../../groupdocs.watermark.search.searchcriteria/searchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
