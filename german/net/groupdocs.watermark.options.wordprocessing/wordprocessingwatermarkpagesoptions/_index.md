---
title: "WordProcessingWatermarkPagesOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Optionen dar, wenn ein Wasserzeichen zu Word‑Dokumentseiten hinzugefügt wird."
type: docs
weight: 2410
url: /de/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/
---
## WordProcessingWatermarkPagesOptions class

Stellt Optionen dar, wenn ein Wasserzeichen zu Word‑Dokumentseiten hinzugefügt wird.

```csharp
public sealed class WordProcessingWatermarkPagesOptions : WordProcessingWatermarkBaseOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [WordProcessingWatermarkPagesOptions](wordprocessingwatermarkpagesoptions)() | Initialisiert eine neue Instanz der [`WordProcessingWatermarkPagesOptions`](../wordprocessingwatermarkpagesoptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | Liest oder setzt den beschreibenden (alternativen) Text, der mit einer Form verknüpft wird. |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | Liest oder setzt einen Wert von [`WordProcessingImageEffects`](../wordprocessingimageeffects) oder [`WordProcessingTextEffects`](../wordprocessingtexteffects) für Effekte, die auf das Wasserzeichen angewendet werden sollen. |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | Liest oder setzt einen Wert, der angibt, ob das Bearbeiten der Form in Word verboten ist. |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | Liest oder setzt den Sperrtyp des Wasserzeichens. |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | Liest oder setzt den Namen einer Form. |
| [PageNumbers](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/pagenumbers) { get; set; } | Liest oder setzt die Seitenzahlen, zu denen das Wasserzeichen hinzugefügt werden soll. |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | Liest oder setzt ein Passwort, das zum Sperren des Wasserzeichens verwendet wird. |

### Hinweise

**Learn more:**

* [Add watermarks to word processing documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### Beispiele

Füge ein Wasserzeichen zu einer bestimmten Seite eines Word-Dokuments hinzu.

```csharp
WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.doc", loadOptions))
{
    TextWatermark watermark = new TextWatermark("text", new Font("Arial", 42));

    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
    options.PageNumbers = new[] { 1 };

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Siehe auch

* class [WordProcessingWatermarkBaseOptions](../wordprocessingwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
