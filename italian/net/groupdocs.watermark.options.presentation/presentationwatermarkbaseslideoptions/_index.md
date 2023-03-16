---
title: PresentationWatermarkBaseSlideOptions
second_title: Riferimento API GroupDocs.Watermark per .NET
description: Classe base per la filigrana che aggiunge opzioni a un documento di presentazione.
type: docs
weight: 1990
url: /it/net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/
---
## PresentationWatermarkBaseSlideOptions class

Classe base per la filigrana che aggiunge opzioni a un documento di presentazione.

```csharp
public abstract class PresentationWatermarkBaseSlideOptions : PresentationWatermarkOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternativetext) { get; set; } | Ottiene o imposta il testo descrittivo (alternativo) che verrà associato a una forma. |
| [Effects](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects) { get; set; } | Ottiene o imposta un valore di[`PresentationImageEffects`](../presentationimageeffects) o [`PresentationTextEffects`](../presentationtexteffects) per gli effetti da applicare alla filigrana. |
| [IsLocked](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/islocked) { get; set; } | Ottiene o imposta un valore che indica se è vietata la modifica della forma in PowerPoint. |
| [Name](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name) { get; set; } | Ottiene o imposta il nome una forma. |
| [ProtectWithUnreadableCharacters](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protectwithunreadablecharacters) { get; set; } | Ottiene o imposta un valore che indica se i caratteri della filigrana di testo sono mescolati con caratteri illeggibili. |

### Osservazioni

**Saperne di più:**

* [Aggiungi filigrane ai documenti di presentazione](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

### Esempi

Aggiungi filigrana a diverse diapositive di servizio di una presentazione in Power Point.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pptx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 8));

    // Aggiungi filigrana a tutte le diapositive master
    PresentationWatermarkMasterSlideOptions masterSlideOptions = new PresentationWatermarkMasterSlideOptions();
    masterSlideOptions.MasterSlideIndex = -1; // predefinito
    watermarker.Add(watermark, masterSlideOptions);

    // Aggiungi filigrana a tutte le diapositive del layout
    PresentationWatermarkLayoutSlideOptions layoutSlideOptions = new PresentationWatermarkLayoutSlideOptions();
    layoutSlideOptions.LayoutSlideIndex = -1; // predefinito
    watermarker.Add(watermark, layoutSlideOptions);

    // Aggiungi filigrana a tutte le diapositive delle note
    PresentationWatermarkNoteSlideOptions noteSlideOptions = new PresentationWatermarkNoteSlideOptions();
    noteSlideOptions.SlideIndex = -1; // predefinito
    watermarker.Add(watermark, noteSlideOptions);

    // Aggiungi filigrana all'handout master
    PresentationWatermarkMasterHandoutSlideOptions masterHandoutSlideOptions = new PresentationWatermarkMasterHandoutSlideOptions();
    watermarker.Add(watermark, masterHandoutSlideOptions);

    // Aggiungi filigrana al master delle note
    PresentationWatermarkMasterNotesSlideOptions masterNotesSlideOptions = new PresentationWatermarkMasterNotesSlideOptions();
    watermarker.Add(watermark, masterNotesSlideOptions);

    watermarker.Save();
}
```

### Guarda anche

* class [PresentationWatermarkOptions](../presentationwatermarkoptions)
* spazio dei nomi [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assemblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->