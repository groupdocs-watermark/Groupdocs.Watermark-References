---
title: "PresentationWatermarkSlideOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta le opzioni quando si aggiunge la filigrana a una diapositiva di un documento Presentation."
type: docs
weight: 2130
url: /it/net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/
---
## PresentationWatermarkSlideOptions class

Rappresenta le opzioni quando si aggiunge la filigrana a una diapositiva di un documento Presentation.

```csharp
public sealed class PresentationWatermarkSlideOptions : PresentationWatermarkBaseSlideOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PresentationWatermarkSlideOptions](presentationwatermarkslideoptions)() | Inizializza una nuova istanza della classe [`PresentationWatermarkSlideOptions`](../presentationwatermarkslideoptions). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternativetext) { get; set; } | Ottiene o imposta il testo descrittivo (alternativo) che sarà associato a una forma. |
| [Effects](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects) { get; set; } | Ottiene o imposta un valore di [`PresentationImageEffects`](../presentationimageeffects) o [`PresentationTextEffects`](../presentationtexteffects) per gli effetti che devono essere applicati alla filigrana. |
| [IsLocked](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/islocked) { get; set; } | Ottiene o imposta un valore che indica se la modifica della forma in PowerPoint è vietata. |
| [Name](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name) { get; set; } | Ottiene o imposta il nome di una forma. |
| [ProtectWithUnreadableCharacters](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protectwithunreadablecharacters) { get; set; } | Ottiene o imposta un valore che indica se i caratteri della filigrana di testo sono mescolati con caratteri illeggibili. |
| [SlideIndex](../../groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/slideindex) { get; set; } | Ottiene o imposta l'indice della diapositiva a cui aggiungere la filigrana. |

### Osservazioni

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

### Esempi

Aggiungi una filigrana a una diapositiva specifica di una presentazione Power Point.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.ppt", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
    watermark.HorizontalAlignment = HorizontalAlignment.Center;
    watermark.VerticalAlignment = VerticalAlignment.Center;

    PresentationWatermarkSlideOptions options = new PresentationWatermarkSlideOptions();
    options.SlideIndex = 0;
    options.IsLocked = false; // default
    options.ProtectWithUnreadableCharacters = false; // default
    options.Name = null; // default
    options.AlternativeText = null; // default

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Vedi anche

* class [PresentationWatermarkBaseSlideOptions](../presentationwatermarkbaseslideoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
