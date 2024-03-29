---
title: WordProcessingWatermarkPagesOptions
second_title: GroupDocs.Watermark voor .NET API-referentie
description: Vertegenwoordigt opties bij het toevoegen van een watermerk aan Worddocumentpaginas.
type: docs
weight: 2370
url: /nl/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/
---
## WordProcessingWatermarkPagesOptions class

Vertegenwoordigt opties bij het toevoegen van een watermerk aan Word-documentpagina's.

```csharp
public sealed class WordProcessingWatermarkPagesOptions : WordProcessingWatermarkBaseOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [WordProcessingWatermarkPagesOptions](wordprocessingwatermarkpagesoptions)() | Initialiseert een nieuw exemplaar van het[`WordProcessingWatermarkPagesOptions`](../wordprocessingwatermarkpagesoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | Haalt de beschrijvende (alternatieve) tekst op of stelt deze in die aan een vorm wordt gekoppeld. |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | Haalt of stelt een waarde in van[`WordProcessingImageEffects`](../wordprocessingimageeffects) of [`WordProcessingTextEffects`](../wordprocessingtexteffects) voor effecten die op het watermerk moeten worden toegepast. |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | Haalt of stelt een waarde in die aangeeft of het bewerken van de vorm in Word verboden is. |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | Haalt of stelt het watermerkvergrendelingstype in. |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | Krijgt of stelt de naam van een vorm in. |
| [PageNumbers](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/pagenumbers) { get; set; } | Haalt of stelt de paginanummers in om het watermerk toe te voegen. |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | Krijgt of stelt een wachtwoord in dat wordt gebruikt om het watermerk te vergrendelen. |

### Opmerkingen

**Kom meer te weten:**

* [Voeg watermerken toe aan tekstverwerkingsdocumenten](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### Voorbeelden

Watermerk toevoegen aan een bepaalde pagina van een Word-document.

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
* naamruimte [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
