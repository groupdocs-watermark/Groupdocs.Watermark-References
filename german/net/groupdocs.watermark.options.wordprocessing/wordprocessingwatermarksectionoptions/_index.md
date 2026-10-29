---
title: "WordProcessingWatermarkSectionOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Optionen dar, wenn ein Form‑Wasserzeichen zu einem Word‑Dokumentabschnitt hinzugefügt wird."
type: docs
weight: 2420
url: /de/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarksectionoptions/
---
## WordProcessingWatermarkSectionOptions class

Stellt Optionen dar, wenn ein Form‑Wasserzeichen zu einem Word‑Dokumentabschnitt hinzugefügt wird.

```csharp
public sealed class WordProcessingWatermarkSectionOptions : WordProcessingWatermarkBaseOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [WordProcessingWatermarkSectionOptions](wordprocessingwatermarksectionoptions)() | Initialisiert eine neue Instanz der [`WordProcessingWatermarkSectionOptions`](../wordprocessingwatermarksectionoptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | Liest oder setzt den beschreibenden (alternativen) Text, der mit einer Form verknüpft wird. |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | Liest oder setzt einen Wert von [`WordProcessingImageEffects`](../wordprocessingimageeffects) oder [`WordProcessingTextEffects`](../wordprocessingtexteffects) für Effekte, die auf das Wasserzeichen angewendet werden sollen. |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | Liest oder setzt einen Wert, der angibt, ob das Bearbeiten der Form in Word verboten ist. |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | Liest oder setzt den Sperrtyp des Wasserzeichens. |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | Liest oder setzt den Namen einer Form. |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | Liest oder setzt ein Passwort, das zum Sperren des Wasserzeichens verwendet wird. |
| [SectionIndex](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarksectionoptions/sectionindex) { get; set; } | Liest oder setzt den Index eines Abschnitts, zu dem das Wasserzeichen hinzugefügt werden soll. |

### Hinweise

**Learn more:**

* [Add watermarks to word processing documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### Beispiele

Füge ein Wasserzeichen zu einem bestimmten Abschnitt eines Word-Dokuments hinzu.

```csharp
WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.doc", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
    watermark.HorizontalAlignment = HorizontalAlignment.Center;
    watermark.VerticalAlignment = VerticalAlignment.Center;
    watermark.ForegroundColor = Color.Red;

    WordProcessingWatermarkSectionOptions options = new WordProcessingWatermarkSectionOptions();
    options.SectionIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Siehe auch

* class [WordProcessingWatermarkBaseOptions](../wordprocessingwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
