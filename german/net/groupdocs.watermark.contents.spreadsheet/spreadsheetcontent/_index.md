---
title: SpreadsheetContent
second_title: GroupDocs.Watermark für .NET-API-Referenz
description: Stellt ein ExcelDokument dar in dem ein Wasserzeichen platziert werden kann.
type: docs
weight: 1100
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
| [Worksheets](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/worksheets) { get; } | Ruft die Sammlung aller Arbeitsblätter davon ab[`SpreadsheetContent`](../spreadsheetcontent) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/decrypt)() | Entschlüsselt das Dokument. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Verwirft die aktuelle Instanz. |
| [Encrypt](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt)(string) | Verschlüsselt den Inhalt. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Findet alle Bilder im Inhalt. Die Suche wird in den angegebenen Objekten durchgeführt[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Findet Bilder nach den angegebenen Suchkriterien. Die Suche wird in den angegebenen Objekten durchgeführt[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Findet alle möglichen Wasserzeichen im Inhalt. Die Suche wird in den in angegebenen Objekten durchgeführt[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Findet mögliche Wasserzeichen nach vorgegebenen Suchkriterien. Die Suche wird in den in angegebenen Objekten durchgeführt[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |

### Bemerkungen

**Mehr erfahren:**

* [Fügen Sie Tabellendokumenten Wasserzeichen hinzu](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)
* [Formen im Tabellenkalkulationsdokument](https://docs.groupdocs.com/display/watermarknet/Shapes+in+spreadsheet+document)
* [Arbeiten mit Anhängen von Tabellendokumenten](https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments)
* [Arbeiten mit Arbeitsblatthintergründen](https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+backgrounds)
* [Arbeiten mit Kopf- und Fußzeilen von Arbeitsblättern](https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+headers+and+footers)

### Beispiele

Laden und speichern Sie Excel-Dokumente aller unterstützten Typen.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.xls", loadOptions))
{
    // Add-Methode verwenden, um Wasserzeichen zu einem bestimmten oder allen Arbeitsblättern hinzuzufügen.

    // Änderungen speichern.
    watermarker.Save(@"D:\output.xls");
}
```

### Siehe auch

* class [Content](../../groupdocs.watermark.contents/content)
* namensraum [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* Montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->