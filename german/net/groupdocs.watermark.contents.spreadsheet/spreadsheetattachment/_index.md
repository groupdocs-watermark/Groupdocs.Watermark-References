---
title: "SpreadsheetAttachment"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt eine an ein Excel‑Dokument angehängte Datei dar."
type: docs
weight: 1100
url: /de/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/
---
## SpreadsheetAttachment class

Stellt eine an ein Excel‑Dokument angehängte Datei dar.

```csharp
public class SpreadsheetAttachment : Attachment, ITwoDObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/alternativetext) { get; set; } | Ermittelt oder legt den beschreibenden (alternativen) Text fest, der mit der angehängten Datei verknüpft ist. |
| override [Content](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/content) { get; set; } | Liefert oder setzt den Inhalt der angehängten Datei. |
| [Height](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/height) { get; set; } | Ermittelt oder legt die Höhe des Anhangrahmens in Punkten fest. |
| [IsLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/islink) { get; } | Ermittelt einen Wert, der angibt, ob der Inhalt nur einen Link zur Datei enthält. |
| [PreviewImageContent](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/previewimagecontent) { get; set; } | Ermittelt oder legt das Vorschaubild der angehängten Datei als Byte-Array fest. |
| [SourceFullName](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/sourcefullname) { get; } | Ermittelt den vollständigen Namen der angehängten Datei. |
| [Width](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/width) { get; set; } | Ermittelt oder legt die Breite des Anhangrahmens in Punkten fest. |
| [X](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/x) { get; set; } | Ermittelt oder legt den horizontalen Versatz des Anhangrahmens vom linken Rand des Arbeitsblatts in Punkten fest. |
| [Y](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/y) { get; set; } | Ermittelt oder legt den vertikalen Versatz des Anhangrahmens vom oberen Rand des Arbeitsblatts in Punkten fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | Lädt einen Inhalt aus der angehängten Datei. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | Lädt einen Inhalt aus der angehängten Datei mit den angegebenen Ladeoptionen. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | Lädt einen Inhalt aus der angehängten Datei mit den angegebenen Ladeoptionen und Einstellungen. |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | Liefert die Informationen zu einem im Anhang gespeicherten Dokument. |

### Siehe auch

* class [Attachment](../../groupdocs.watermark.common/attachment)
* interface [ITwoDObject](../../groupdocs.watermark.search/itwodobject)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
