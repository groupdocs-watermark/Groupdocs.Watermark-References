---
title: "WordProcessingWatermarkPagesOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Geeft opties weer bij het toevoegen van een watermerk aan Word-documentpagina's."
type: docs
weight: 2410
url: /nl/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/
---
## WordProcessingWatermarkPagesOptions class

Geeft opties weer bij het toevoegen van een watermerk aan Word-documentpagina's.

```csharp
public sealed class WordProcessingWatermarkPagesOptions : WordProcessingWatermarkBaseOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [WordProcessingWatermarkPagesOptions](wordprocessingwatermarkpagesoptions)() | Initialiseert een nieuw exemplaar van de [`WordProcessingWatermarkPagesOptions`](../wordprocessingwatermarkpagesoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | Haalt of stelt de beschrijvende (alternatieve) tekst in die aan een vorm wordt gekoppeld. |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | Haalt een waarde op of stelt deze in van [`WordProcessingImageEffects`](../wordprocessingimageeffects) of [`WordProcessingTextEffects`](../wordprocessingtexteffects) voor effecten die op het watermerk moeten worden toegepast. |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | Haalt een waarde op of stelt deze in die aangeeft of bewerken van de vorm in Word verboden is. |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | Haalt het vergrendeltype van het watermerk op of stelt dit in. |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | Haalt of stelt de naam van een vorm in. |
| [PageNumbers](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/pagenumbers) { get; set; } | Haalt de paginanummers op of stelt deze in waarop het watermerk moet worden toegevoegd. |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | Haalt een wachtwoord op of stelt een wachtwoord in dat wordt gebruikt om het watermerk te vergrendelen. |

### Opmerkingen

**Learn more:**

* [Add watermarks to word processing documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### Voorbeelden

Voeg een watermerk toe aan een specifieke pagina van een Word-document.

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

### Zie ook

* class [WordProcessingWatermarkBaseOptions](../wordprocessingwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
