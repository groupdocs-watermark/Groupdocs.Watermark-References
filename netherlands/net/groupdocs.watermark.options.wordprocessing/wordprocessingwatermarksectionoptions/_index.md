---
title: "WordProcessingWatermarkSectionOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Geeft opties weer bij het toevoegen van een vormwatermerk aan een Word‑sectie."
type: docs
weight: 2420
url: /nl/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarksectionoptions/
---
## WordProcessingWatermarkSectionOptions class

Geeft opties weer bij het toevoegen van een vormwatermerk aan een Word‑sectie.

```csharp
public sealed class WordProcessingWatermarkSectionOptions : WordProcessingWatermarkBaseOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [WordProcessingWatermarkSectionOptions](wordprocessingwatermarksectionoptions)() | Initialiseert een nieuw exemplaar van de [`WordProcessingWatermarkSectionOptions`](../wordprocessingwatermarksectionoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | Haalt of stelt de beschrijvende (alternatieve) tekst in die aan een vorm wordt gekoppeld. |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | Haalt een waarde op of stelt deze in van [`WordProcessingImageEffects`](../wordprocessingimageeffects) of [`WordProcessingTextEffects`](../wordprocessingtexteffects) voor effecten die op het watermerk moeten worden toegepast. |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | Haalt een waarde op of stelt deze in die aangeeft of bewerken van de vorm in Word verboden is. |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | Haalt het vergrendeltype van het watermerk op of stelt dit in. |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | Haalt of stelt de naam van een vorm in. |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | Haalt een wachtwoord op of stelt een wachtwoord in dat wordt gebruikt om het watermerk te vergrendelen. |
| [SectionIndex](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarksectionoptions/sectionindex) { get; set; } | Haalt de index op of stelt de index in van een sectie waaraan het watermerk moet worden toegevoegd. |

### Opmerkingen

**Learn more:**

* [Add watermarks to word processing documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### Voorbeelden

Voeg een watermerk toe aan een specifieke sectie van een Word-document.

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

### Zie ook

* class [WordProcessingWatermarkBaseOptions](../wordprocessingwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
