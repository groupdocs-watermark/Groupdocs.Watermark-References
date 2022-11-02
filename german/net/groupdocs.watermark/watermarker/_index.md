---
title: Watermarker
second_title: GroupDocs.Watermark für .NET-API-Referenz
description: Repräsentiert eine Klasse für die Wasserzeichenverwaltung in einem Dokument.
type: docs
weight: 3060
url: /de/net/groupdocs.watermark/watermarker/
---
## Watermarker class

Repräsentiert eine Klasse für die Wasserzeichenverwaltung in einem Dokument.

```csharp
public class Watermarker : IDisposable
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | Initialisiert eine neue Instanz von[`Watermarker`](../watermarker) Klasse mit dem angegebenen Stream. |
| [Watermarker](watermarker#constructor_4)(string) | Initialisiert eine neue Instanz von[`Watermarker`](../watermarker) Klasse mit dem angegebenen Dokumentpfad. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | Initialisiert eine neue Instanz von[`Watermarker`](../watermarker) Klasse mit den angegebenen stream und Ladeoptionen. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | Initialisiert eine neue Instanz von[`Watermarker`](../watermarker) Klasse mit dem angegebenen stream und settings. |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | Initialisiert eine neue Instanz von[`Watermarker`](../watermarker)Klasse mit dem angegebenen Dokumentpfad und den Ladeoptionen. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | Initialisiert eine neue Instanz von[`Watermarker`](../watermarker) Klasse mit dem angegebenen Dokumentpfad und den Einstellungen. |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | Initialisiert eine neue Instanz von[`Watermarker`](../watermarker) Klasse mit dem angegebenen Stream, Ladeoptionen und Einstellungen. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | Initialisiert eine neue Instanz von[`Watermarker`](../watermarker) Klasse mit dem angegebenen Dokumentpfad, Ladeoptionen und Einstellungen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | Holt oder setzt die Inhaltsobjekte, die in eine Wasserzeichensuche eingeschlossen werden sollen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | Fügt dem geladenen Dokument ein Wasserzeichen hinzu. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | Fügt dem geladenen Dokument mithilfe von Wasserzeichenoptionen ein Wasserzeichen hinzu. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | Verwirft die aktuelle Instanz. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | Erzeugt Vorschaubilder für das Dokument. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | Gibt die zurück[`Content`](../../groupdocs.watermark.contents/content) Objekt für das geladene Dokument. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | Ruft die Informationen über das Format des geladenen Dokuments ab. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | Findet alle Bilder im Dokument. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | Findet Bilder nach festgelegten Suchkriterien. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | Entfernt Wasserzeichen aus dem Dokument. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | Entfernt alle Wasserzeichen in der Sammlung aus dem Dokument. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | Speichert die Dokumentdaten im zugrunde liegenden Stream. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | Speichert die Dokumentdaten mit Speicheroptionen im zugrunde liegenden Stream. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | Speichert das Dokument im angegebenen Stream. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | Speichert das Dokument am angegebenen Speicherort. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | Speichert das Dokument unter Verwendung von Speicheroptionen im angegebenen Stream. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | Speichert das Dokument unter Verwendung von Speicheroptionen am angegebenen Speicherort. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | Durchsucht alle möglichen Wasserzeichen im Dokument. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | Sucht nach möglichen Wasserzeichen nach festgelegten Suchkriterien. |

### Beispiele

Laden und speichern Sie Inhalte in einem beliebigen unterstützten Format.

```csharp
// Inhalt aus einer Datei laden.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Methoden der Watermarker-Klasse verwenden, um Wasserzeichen hinzuzufügen, zu suchen oder zu entfernen.

    // Änderungen speichern.
    watermarker.Save("D:\\output.pdf");
}
```

### Siehe auch

* namensraum [GroupDocs.Watermark](../../groupdocs.watermark)
* Montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
