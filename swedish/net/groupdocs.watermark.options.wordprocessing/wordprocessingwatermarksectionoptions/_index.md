---
title: "WordProcessingWatermarkSectionOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar alternativ när en formvattenstämpel läggs till i ett Word-dokumentavsnitt."
type: docs
weight: 2420
url: /sv/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarksectionoptions/
---
## WordProcessingWatermarkSectionOptions class

Representerar alternativ när en formvattenstämpel läggs till i ett Word-dokumentavsnitt.

```csharp
public sealed class WordProcessingWatermarkSectionOptions : WordProcessingWatermarkBaseOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [WordProcessingWatermarkSectionOptions](wordprocessingwatermarksectionoptions)() | Initierar en ny instans av klassen [`WordProcessingWatermarkSectionOptions`](../wordprocessingwatermarksectionoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | Hämtar eller anger den beskrivande (alternativa) texten som kommer att associeras med en form. |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | Hämtar eller anger ett värde av [`WordProcessingImageEffects`](../wordprocessingimageeffects) eller [`WordProcessingTextEffects`](../wordprocessingtexteffects) för effekter som ska tillämpas på vattenstämpeln. |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | Hämtar eller anger ett värde som indikerar om redigering av formen i Word är förbjuden. |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | Hämtar eller anger vattenstämpelns låstyp. |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | Hämtar eller anger namnet på en form. |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | Hämtar eller anger ett lösenord som används för att låsa vattenstämpeln. |
| [SectionIndex](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarksectionoptions/sectionindex) { get; set; } | Hämtar eller anger indexet för ett avsnitt som vattenstämpeln ska läggas till. |

### Anmärkningar

**Learn more:**

* [Add watermarks to word processing documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### Exempel

Lägg till vattenstämpel i ett specifikt avsnitt i ett Word-dokument.

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

### Se även

* class [WordProcessingWatermarkBaseOptions](../wordprocessingwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
