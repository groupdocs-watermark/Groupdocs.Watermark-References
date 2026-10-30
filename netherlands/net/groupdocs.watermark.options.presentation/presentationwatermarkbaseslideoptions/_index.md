---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Basisklasse voor opties om een watermerk toe te voegen aan een Presentatie-document."
type: docs
weight: 2060
url: /nl/net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/
---
## PresentationWatermarkBaseSlideOptions class

Basisklasse voor opties om een watermerk toe te voegen aan een Presentatie-document.

```csharp
public abstract class PresentationWatermarkBaseSlideOptions : PresentationWatermarkOptions
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternativetext) { get; set; } | Haalt of stelt de beschrijvende (alternatieve) tekst in die aan een vorm wordt gekoppeld. |
| [Effects](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects) { get; set; } | Haalt op of stelt een waarde in van [`PresentationImageEffects`](../presentationimageeffects) of [`PresentationTextEffects`](../presentationtexteffects) voor effecten die op het watermerk moeten worden toegepast. |
| [IsLocked](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/islocked) { get; set; } | Haalt op of stelt een waarde in die aangeeft of bewerken van de vorm in PowerPoint verboden is. |
| [Name](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name) { get; set; } | Haalt of stelt de naam van een vorm in. |
| [ProtectWithUnreadableCharacters](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protectwithunreadablecharacters) { get; set; } | Haalt op of stelt een waarde in die aangeeft of de tekens van het tekstwatermerk gemengd zijn met onleesbare tekens. |

### Opmerkingen

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

### Voorbeelden

Voeg een watermerk toe aan verschillende service-dia's van een PowerPoint-presentatie.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pptx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 8));

    // Voeg een watermerk toe aan alle masterdia's
    PresentationWatermarkMasterSlideOptions masterSlideOptions = new PresentationWatermarkMasterSlideOptions();
    masterSlideOptions.MasterSlideIndex = -1; // default
    watermarker.Add(watermark, masterSlideOptions);

    // Voeg een watermerk toe aan alle lay-outdia's
    PresentationWatermarkLayoutSlideOptions layoutSlideOptions = new PresentationWatermarkLayoutSlideOptions();
    layoutSlideOptions.LayoutSlideIndex = -1; // default
    watermarker.Add(watermark, layoutSlideOptions);

    // Voeg een watermerk toe aan alle notitiedia's
    PresentationWatermarkNoteSlideOptions noteSlideOptions = new PresentationWatermarkNoteSlideOptions();
    noteSlideOptions.SlideIndex = -1; // default
    watermarker.Add(watermark, noteSlideOptions);

    // Voeg een watermerk toe aan de handout-master
    PresentationWatermarkMasterHandoutSlideOptions masterHandoutSlideOptions = new PresentationWatermarkMasterHandoutSlideOptions();
    watermarker.Add(watermark, masterHandoutSlideOptions);

    // Voeg een watermerk toe aan de notitie-master
    PresentationWatermarkMasterNotesSlideOptions masterNotesSlideOptions = new PresentationWatermarkMasterNotesSlideOptions();
    watermarker.Add(watermark, masterNotesSlideOptions);

    watermarker.Save();
}
```

### Zie ook

* class [PresentationWatermarkOptions](../presentationwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
