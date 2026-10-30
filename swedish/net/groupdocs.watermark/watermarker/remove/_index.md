---
title: "Ta bort"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Tar bort vattenmärke från dokumentet."
type: docs
weight: 90
url: /sv/net/groupdocs.watermark/watermarker/remove/
---
## Remove(PossibleWatermark) {#remove}

Tar bort vattenmärke från dokumentet.

```csharp
public void Remove(PossibleWatermark possibleWatermark)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| possibleWatermark | PossibleWatermark | Vattenmärket att ta bort. |

### Anmärkningar

Läs mer om att ta bort vattenmärken: [Ta bort hittade vattenmärken](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks).

### Exempel

Hitta och ta bort det första möjliga vattenmärket som innehåller särskild text eller bild från ett dokument av någon stödd typ.

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

### Se även

* class [PossibleWatermark](../../../groupdocs.watermark.search/possiblewatermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Remove(PossibleWatermarkCollection) {#remove_1}

Tar bort alla vattenmärken i samlingen från dokumentet.

```csharp
public void Remove(PossibleWatermarkCollection possibleWatermarks)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| possibleWatermarks | PossibleWatermarkCollection | Samlingen av vattenmärken att ta bort. |

### Anmärkningar

Läs mer om att ta bort vattenmärken [Ta bort hittade vattenmärken](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks).

### Exempel

Hitta och ta bort alla möjliga vattenmärken som innehåller särskild text eller bild från ett dokument av någon stödd typ.

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

### Se även

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
