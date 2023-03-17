---
title: DiagramShapeWatermarkOptions
second_title: GroupDocs.Watermark για Αναφορά API .NET
description: Αντιπροσωπεύει επιλογές προσθήκης υδατογραφήματος κατά την προσθήκη υδατογραφήματος σχήματος σε έγγραφο του Visio.
type: docs
weight: 1680
url: /el/net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/
---
## DiagramShapeWatermarkOptions class

Αντιπροσωπεύει επιλογές προσθήκης υδατογραφήματος κατά την προσθήκη υδατογραφήματος σχήματος σε έγγραφο του Visio.

```csharp
public sealed class DiagramShapeWatermarkOptions : DiagramWatermarkOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [DiagramShapeWatermarkOptions](diagramshapewatermarkoptions)() | Αρχικοποιεί μια νέα παρουσία του[`DiagramShapeWatermarkOptions`](../diagramshapewatermarkoptions) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν απαγορεύεται η επεξεργασία του σχήματος στο Visio. |
| [PlacementType](../../groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/placementtype) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που καθορίζει σε ποιες σελίδες πρέπει να προστεθεί ένα υδατογράφημα. |

### Παρατηρήσεις

**Μάθε περισσότερα:**

* [Προσθήκη υδατογραφημάτων σε έγγραφα διαγράμματος](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### Παραδείγματα

Προσθήκη προστατευμένου υδατογραφήματος σε όλες τις σελίδες του εγγράφου Visio.

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
    options.IsLocked = true;
    options.PlacementType = DiagramWatermarkPlacementType.AllPages; // Προκαθορισμένο

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Δείτε επίσης

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* χώρος ονομάτων [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* συνέλευση [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->