---
title: PresentationWatermarkBaseSlideOptions
second_title: GroupDocs.Watermark für .NET-API-Referenz
description: Basisklasse für das Hinzufügen von Optionen für Wasserzeichen zu einem Präsentationsdokument.
type: docs
weight: 1990
url: /de/net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/
---
## PresentationWatermarkBaseSlideOptions class

Basisklasse für das Hinzufügen von Optionen für Wasserzeichen zu einem Präsentationsdokument.

```csharp
public abstract class PresentationWatermarkBaseSlideOptions : PresentationWatermarkOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternativetext) { get; set; } | Ruft den beschreibenden (alternativen) Text ab oder legt ihn fest, der einer Form zugeordnet wird. |
| [Effects](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects) { get; set; } | Erhält oder setzt einen Wert von[`PresentationImageEffects`](../presentationimageeffects) oder [`PresentationTextEffects`](../presentationtexteffects) für Effekte, die auf das Wasserzeichen angewendet werden sollen. |
| [IsLocked](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/islocked) { get; set; } | Ruft oder setzt einen Wert, der angibt, ob eine Bearbeitung der Form in PowerPoint verboten ist. |
| [Name](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name) { get; set; } | Ruft den Namen einer Form ab oder legt ihn fest. |
| [ProtectWithUnreadableCharacters](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protectwithunreadablecharacters) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Zeichen des Textwasserzeichens mit nicht lesbaren Zeichen gemischt sind. |

### Bemerkungen

**Mehr erfahren:**

* [Fügen Sie Präsentationsdokumenten Wasserzeichen hinzu](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

### Beispiele

Hinzufügen von Wasserzeichen zu verschiedenen Servicefolien einer PowerPoint-Präsentation.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pptx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 8));

    // Wasserzeichen zu allen Masterfolien hinzufügen
    PresentationWatermarkMasterSlideOptions masterSlideOptions = new PresentationWatermarkMasterSlideOptions();
    masterSlideOptions.MasterSlideIndex = -1; // Ursprünglich
    watermarker.Add(watermark, masterSlideOptions);

    // Wasserzeichen zu allen Layoutfolien hinzufügen
    PresentationWatermarkLayoutSlideOptions layoutSlideOptions = new PresentationWatermarkLayoutSlideOptions();
    layoutSlideOptions.LayoutSlideIndex = -1; // Ursprünglich
    watermarker.Add(watermark, layoutSlideOptions);

    // Wasserzeichen zu allen Notizfolien hinzufügen
    PresentationWatermarkNoteSlideOptions noteSlideOptions = new PresentationWatermarkNoteSlideOptions();
    noteSlideOptions.SlideIndex = -1; // Ursprünglich
    watermarker.Add(watermark, noteSlideOptions);

    // Wasserzeichen zum Handout-Master hinzufügen
    PresentationWatermarkMasterHandoutSlideOptions masterHandoutSlideOptions = new PresentationWatermarkMasterHandoutSlideOptions();
    watermarker.Add(watermark, masterHandoutSlideOptions);

    // Wasserzeichen zum Notizenmaster hinzufügen
    PresentationWatermarkMasterNotesSlideOptions masterNotesSlideOptions = new PresentationWatermarkMasterNotesSlideOptions();
    watermarker.Add(watermark, masterNotesSlideOptions);

    watermarker.Save();
}
```

### Siehe auch

* class [PresentationWatermarkOptions](../presentationwatermarkoptions)
* namensraum [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* Montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->