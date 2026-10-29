---
title: "SpreadsheetContent"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt ein Excel-Dokument dar, in dem ein Wasserzeichen platziert werden kann."
type: docs
weight: 1170
url: /de/net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/
---
## SpreadsheetContent class

Stellt ein Excel-Dokument dar, in dem ein Wasserzeichen platziert werden kann.

```csharp
public class SpreadsheetContent : Content
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Worksheets](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/worksheets) { get; } | Liest die Sammlung aller Arbeitsblätter dieses [`SpreadsheetContent`](../spreadsheetcontent). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/decrypt)() | Entschlüsselt das Dokument. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Gibt die aktuelle Instanz frei. |
| [Encrypt](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt)(string) | Verschlüsselt den Inhalt. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Findet alle Bilder im Inhalt. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Findet Bilder gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Findet alle möglichen Wasserzeichen im Inhalt. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Findet mögliche Wasserzeichen gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |

### Hinweise

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)
* [Shapes in spreadsheet document](https://docs.groupdocs.com/display/watermarknet/Shapes+in+spreadsheet+document)
* [Working with spreadsheet document attachments](https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments)
* [Working with worksheet backgrounds](https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+backgrounds)
* [Working with worksheet headers and footers](https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+headers+and+footers)

### Beispiele

Lädt und speichert Excel-Dokumente jedes unterstützten Typs.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.xls", loadOptions))
{
    // Verwenden Sie die Add-Methode, um ein Wasserzeichen zu einem bestimmten oder allen Arbeitsblättern hinzuzufügen.

    // Änderungen speichern.
    watermarker.Save(@"D:\output.xls");
}
```

### Siehe auch

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
