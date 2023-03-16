---
title: WordProcessingWatermarkSectionOptions
second_title: GroupDocs.Watermark for .NET API-referens
description: Representerar alternativ när du lägger till formvattenstämpel i ett Worddokumentsektion.
type: docs
weight: 2380
url: /sv/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarksectionoptions/
---
## WordProcessingWatermarkSectionOptions class

Representerar alternativ när du lägger till formvattenstämpel i ett Word-dokumentsektion.

```csharp
public sealed class WordProcessingWatermarkSectionOptions : WordProcessingWatermarkBaseOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [WordProcessingWatermarkSectionOptions](wordprocessingwatermarksectionoptions)() | Initierar en ny instans av[`WordProcessingWatermarkSectionOptions`](../wordprocessingwatermarksectionoptions) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | Hämtar eller ställer in den beskrivande (alternativa) texten som kommer att associeras med en form. |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | Hämtar eller ställer in ett värde på[`WordProcessingImageEffects`](../wordprocessingimageeffects) or [`WordProcessingTextEffects`](../wordprocessingtexteffects) för effekter som bör appliceras på vattenstämpeln. |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | Hämtar eller ställer in ett värde som anger om en redigering av formen i Word är förbjuden. |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | Hämtar eller ställer in vattenstämpellåstypen. |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | Hämtar eller sätter namnet en form. |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | Hämtar eller ställer in ett lösenord som används för att låsa vattenstämpeln. |
| [SectionIndex](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarksectionoptions/sectionindex) { get; set; } | Hämtar eller ställer in indexet för ett avsnitt som vattenstämpeln ska läggas till. |

### Anmärkningar

**Läs mer:**

* [Lägg till vattenstämplar i ordbehandlingsdokument](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### Exempel

Lägg till vattenstämpel till en viss del av ett Word-dokument.

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
* namnutrymme [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* hopsättning [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->