---
title: "Watermarker"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt eine Klasse für die Verwaltung von Wasserzeichen in einem Dokument dar."
type: docs
weight: 3140
url: /de/net/groupdocs.watermark/watermarker/
---
## Watermarker class

Stellt eine Klasse für die Verwaltung von Wasserzeichen in einem Dokument dar.

```csharp
public class Watermarker : IDisposable
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | Initialisiert eine neue Instanz der [`Watermarker`](../watermarker)-Klasse mit dem angegebenen Stream. |
| [Watermarker](watermarker#constructor_4)(string) | Initialisiert eine neue Instanz der [`Watermarker`](../watermarker)-Klasse mit dem angegebenen Dokumentpfad. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | Initialisiert eine neue Instanz der [`Watermarker`](../watermarker)-Klasse mit dem angegebenen Stream und den Ladeoptionen. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | Initialisiert eine neue Instanz der [`Watermarker`](../watermarker)-Klasse mit dem angegebenen Stream und den Einstellungen. |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | Initialisiert eine neue Instanz der [`Watermarker`](../watermarker)-Klasse mit dem angegebenen Dokumentpfad und den Ladeoptionen. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | Initialisiert eine neue Instanz der [`Watermarker`](../watermarker)-Klasse mit dem angegebenen Dokumentpfad und den Einstellungen. |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | Initialisiert eine neue Instanz der [`Watermarker`](../watermarker)-Klasse mit dem angegebenen Stream, den Ladeoptionen und den Einstellungen. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | Initialisiert eine neue Instanz der [`Watermarker`](../watermarker)-Klasse mit dem angegebenen Dokumentpfad, den Ladeoptionen und den Einstellungen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | Liest oder setzt die Inhaltsobjekte, die in einer Wasserzeichen-Suche einbezogen werden sollen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | Fügt dem geladenen Dokument ein Wasserzeichen hinzu. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | Fügt dem geladenen Dokument ein Wasserzeichen mithilfe von Wasserzeichen-Optionen hinzu. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | Gibt die aktuelle Instanz frei. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | Erstellt Vorschaubilder für das Dokument. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | Gibt das [`Content`](../../groupdocs.watermark.contents/content)-Objekt für das geladene Dokument zurück. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | Liest die Informationen über das Format des geladenen Dokuments. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | Findet alle Bilder im Dokument. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | Findet Bilder gemäß den angegebenen Suchkriterien. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | Entfernt das Wasserzeichen aus dem Dokument. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | Entfernt alle Wasserzeichen in der Sammlung aus dem Dokument. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | Speichert die Dokumentdaten in den zugrunde liegenden Stream. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | Speichert die Dokumentdaten in den zugrunde liegenden Stream unter Verwendung von Speicheroptionen. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | Speichert das Dokument in den angegebenen Stream. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | Speichert das Dokument am angegebenen Dateipfad. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | Speichert das Dokument in den angegebenen Stream unter Verwendung von Speicheroptionen. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | Speichert das Dokument am angegebenen Dateipfad unter Verwendung von Speicheroptionen. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | Durchsucht das Dokument nach allen möglichen Wasserzeichen. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | Durchsucht mögliche Wasserzeichen gemäß den angegebenen Suchkriterien. |

### Beispiele

Lädt und speichert Inhalte in einem beliebigen unterstützten Format.

```csharp
// Lädt Inhalte aus einer Datei.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Verwenden Sie Methoden der Watermarker class, um Wasserzeichen hinzuzufügen, zu suchen oder zu entfernen.

    // Änderungen speichern.
    watermarker.Save("D:\\output.pdf");
}
```

### Siehe auch

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
