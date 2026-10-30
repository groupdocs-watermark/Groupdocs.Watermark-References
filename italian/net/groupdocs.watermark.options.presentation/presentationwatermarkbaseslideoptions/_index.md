---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Classe base per le opzioni di aggiunta della filigrana a un documento Presentation."
type: docs
weight: 2060
url: /it/net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/
---
## PresentationWatermarkBaseSlideOptions class

Classe base per le opzioni di aggiunta della filigrana a un documento Presentation.

```csharp
public abstract class PresentationWatermarkBaseSlideOptions : PresentationWatermarkOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternativetext) { get; set; } | Ottiene o imposta il testo descrittivo (alternativo) che sarà associato a una forma. |
| [Effects](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects) { get; set; } | Ottiene o imposta un valore di [`PresentationImageEffects`](../presentationimageeffects) o [`PresentationTextEffects`](../presentationtexteffects) per gli effetti che devono essere applicati alla filigrana. |
| [IsLocked](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/islocked) { get; set; } | Ottiene o imposta un valore che indica se la modifica della forma in PowerPoint è vietata. |
| [Name](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name) { get; set; } | Ottiene o imposta il nome di una forma. |
| [ProtectWithUnreadableCharacters](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protectwithunreadablecharacters) { get; set; } | Ottiene o imposta un valore che indica se i caratteri della filigrana di testo sono mescolati con caratteri illeggibili. |

### Osservazioni

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

### Esempi

Aggiungi una filigrana a diverse diapositive di servizio di una presentazione Power Point.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pptx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 8));

    // Aggiungi una filigrana a tutte le diapositive master
    PresentationWatermarkMasterSlideOptions masterSlideOptions = new PresentationWatermarkMasterSlideOptions();
    masterSlideOptions.MasterSlideIndex = -1; // default
    watermarker.Add(watermark, masterSlideOptions);

    // Aggiungi una filigrana a tutte le diapositive layout
    PresentationWatermarkLayoutSlideOptions layoutSlideOptions = new PresentationWatermarkLayoutSlideOptions();
    layoutSlideOptions.LayoutSlideIndex = -1; // default
    watermarker.Add(watermark, layoutSlideOptions);

    // Aggiungi una filigrana a tutte le diapositive note
    PresentationWatermarkNoteSlideOptions noteSlideOptions = new PresentationWatermarkNoteSlideOptions();
    noteSlideOptions.SlideIndex = -1; // default
    watermarker.Add(watermark, noteSlideOptions);

    // Aggiungi una filigrana al master dei fogli distribuiti
    PresentationWatermarkMasterHandoutSlideOptions masterHandoutSlideOptions = new PresentationWatermarkMasterHandoutSlideOptions();
    watermarker.Add(watermark, masterHandoutSlideOptions);

    // Aggiungi una filigrana al master delle note
    PresentationWatermarkMasterNotesSlideOptions masterNotesSlideOptions = new PresentationWatermarkMasterNotesSlideOptions();
    watermarker.Add(watermark, masterNotesSlideOptions);

    watermarker.Save();
}
```

### Vedi anche

* class [PresentationWatermarkOptions](../presentationwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
