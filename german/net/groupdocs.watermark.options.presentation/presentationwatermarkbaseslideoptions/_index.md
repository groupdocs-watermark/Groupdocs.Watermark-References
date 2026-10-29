---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Basisklasse für Optionen zum Hinzufügen von Wasserzeichen zu einem Präsentationsdokument."
type: docs
weight: 2060
url: /de/net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/
---
## PresentationWatermarkBaseSlideOptions class

Basisklasse für Optionen zum Hinzufügen von Wasserzeichen zu einem Präsentationsdokument.

```csharp
public abstract class PresentationWatermarkBaseSlideOptions : PresentationWatermarkOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternativetext) { get; set; } | Liest oder setzt den beschreibenden (alternativen) Text, der mit einer Form verknüpft wird. |
| [Effects](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects) { get; set; } | Liest oder setzt einen Wert von [`PresentationImageEffects`](../presentationimageeffects) oder [`PresentationTextEffects`](../presentationtexteffects) für Effekte, die auf das Wasserzeichen angewendet werden sollen. |
| [IsLocked](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/islocked) { get; set; } | Liest oder setzt einen Wert, der angibt, ob das Bearbeiten der Form in PowerPoint verboten ist. |
| [Name](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name) { get; set; } | Liest oder setzt den Namen einer Form. |
| [ProtectWithUnreadableCharacters](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protectwithunreadablecharacters) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die Zeichen des Textwasserzeichens mit unlesbaren Zeichen gemischt werden. |

### Hinweise

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

### Beispiele

Füge ein Wasserzeichen zu verschiedenen Service‑Folien einer Power Point‑Präsentation hinzu.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pptx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 8));

    // Füge ein Wasserzeichen zu allen Master‑Folien hinzu.
    PresentationWatermarkMasterSlideOptions masterSlideOptions = new PresentationWatermarkMasterSlideOptions();
    masterSlideOptions.MasterSlideIndex = -1; // default
    watermarker.Add(watermark, masterSlideOptions);

    // Füge ein Wasserzeichen zu allen Layout‑Folien hinzu.
    PresentationWatermarkLayoutSlideOptions layoutSlideOptions = new PresentationWatermarkLayoutSlideOptions();
    layoutSlideOptions.LayoutSlideIndex = -1; // default
    watermarker.Add(watermark, layoutSlideOptions);

    // Füge ein Wasserzeichen zu allen Notiz‑Folien hinzu.
    PresentationWatermarkNoteSlideOptions noteSlideOptions = new PresentationWatermarkNoteSlideOptions();
    noteSlideOptions.SlideIndex = -1; // default
    watermarker.Add(watermark, noteSlideOptions);

    // Füge ein Wasserzeichen zum Handout‑Master hinzu.
    PresentationWatermarkMasterHandoutSlideOptions masterHandoutSlideOptions = new PresentationWatermarkMasterHandoutSlideOptions();
    watermarker.Add(watermark, masterHandoutSlideOptions);

    // Füge ein Wasserzeichen zum Notiz‑Master hinzu.
    PresentationWatermarkMasterNotesSlideOptions masterNotesSlideOptions = new PresentationWatermarkMasterNotesSlideOptions();
    watermarker.Add(watermark, masterNotesSlideOptions);

    watermarker.Save();
}
```

### Siehe auch

* class [PresentationWatermarkOptions](../presentationwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
