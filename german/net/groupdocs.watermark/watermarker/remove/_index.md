---
title: "Remove"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Entfernt das Wasserzeichen aus dem Dokument."
type: docs
weight: 90
url: /de/net/groupdocs.watermark/watermarker/remove/
---
## Remove(PossibleWatermark) {#remove}

Entfernt das Wasserzeichen aus dem Dokument.

```csharp
public void Remove(PossibleWatermark possibleWatermark)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| possibleWatermark | PossibleWatermark | Das zu entfernende Wasserzeichen. |

### Hinweise

Erfahren Sie mehr über das Entfernen von Wasserzeichen: [Entfernen gefundener Wasserzeichen](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks).

### Beispiele

Finde und entferne das erste mögliche Wasserzeichen, das einen bestimmten Text oder ein Bild in einem Dokument eines beliebigen unterstützten Typs enthält.

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

### Siehe auch

* class [PossibleWatermark](../../../groupdocs.watermark.search/possiblewatermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Remove(PossibleWatermarkCollection) {#remove_1}

Entfernt alle Wasserzeichen in der Sammlung aus dem Dokument.

```csharp
public void Remove(PossibleWatermarkCollection possibleWatermarks)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| possibleWatermarks | PossibleWatermarkCollection | Die Sammlung der zu entfernenden Wasserzeichen. |

### Hinweise

Erfahren Sie mehr über das Entfernen von Wasserzeichen [Entfernen gefundener Wasserzeichen](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks).

### Beispiele

Finden und entfernen Sie alle möglichen Wasserzeichen, die bestimmten Text oder ein Bild enthalten, aus einem Dokument eines beliebigen unterstützten Typs.

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

### Siehe auch

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
