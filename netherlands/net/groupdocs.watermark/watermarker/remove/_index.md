---
title: "Remove"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Verwijdert watermerk uit het document."
type: docs
weight: 90
url: /nl/net/groupdocs.watermark/watermarker/remove/
---
## Remove(PossibleWatermark) {#remove}

Verwijdert watermerk uit het document.

```csharp
public void Remove(PossibleWatermark possibleWatermark)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| possibleWatermark | PossibleWatermark | Het watermerk om te verwijderen. |

### Opmerkingen

Meer informatie over het verwijderen van watermerken: [Removing found watermarks](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks).

### Voorbeelden

Zoek en verwijder het eerste mogelijke watermerk dat specifieke tekst of afbeelding bevat uit een document van elk ondersteund type.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    if (watermarks.Count > 0)
    {
        watermarker.Remove(watermarks[0]);
    }

    watermarker.Save(@"D:\output.doc");
}
```

### Zie ook

* class [PossibleWatermark](../../../groupdocs.watermark.search/possiblewatermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Remove(PossibleWatermarkCollection) {#remove_1}

Verwijdert alle watermerken in de collectie uit het document.

```csharp
public void Remove(PossibleWatermarkCollection possibleWatermarks)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| possibleWatermarks | PossibleWatermarkCollection | De verzameling watermerken om te verwijderen. |

### Opmerkingen

Meer informatie over het verwijderen van watermerken [Removing found watermarks](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks).

### Voorbeelden

Zoek en verwijder alle mogelijke watermerken die specifieke tekst of afbeelding bevatten uit een document van elk ondersteund type.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    watermarker.Remove(watermarks);
    watermarker.Save(@"D:\output.doc");
}
```

### Zie ook

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
