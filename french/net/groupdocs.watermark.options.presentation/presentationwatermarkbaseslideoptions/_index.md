---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Classe de base pour les options d'ajout de filigrane à un document Presentation."
type: docs
weight: 2060
url: /fr/net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/
---
## PresentationWatermarkBaseSlideOptions class

Classe de base pour les options d'ajout de filigrane à un document Presentation.

```csharp
public abstract class PresentationWatermarkBaseSlideOptions : PresentationWatermarkOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternativetext) { get; set; } | Obtient ou définit le texte descriptif (alternatif) qui sera associé à une forme. |
| [Effects](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects) { get; set; } | Obtient ou définit une valeur de [`PresentationImageEffects`](../presentationimageeffects) ou de [`PresentationTextEffects`](../presentationtexteffects) pour les effets qui doivent être appliqués au filigrane. |
| [IsLocked](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/islocked) { get; set; } | Obtient ou définit une valeur indiquant si la modification de la forme dans PowerPoint est interdite. |
| [Name](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name) { get; set; } | Obtient ou définit le nom d'une forme. |
| [ProtectWithUnreadableCharacters](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protectwithunreadablecharacters) { get; set; } | Obtient ou définit une valeur indiquant si les caractères du filigrane texte sont mélangés avec des caractères illisibles. |

### Remarques

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

### Exemples

Ajoutez un filigrane aux différentes diapositives de service d’une présentation Power Point.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pptx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 8));

    // Ajoutez un filigrane à toutes les diapositives maîtres
    PresentationWatermarkMasterSlideOptions masterSlideOptions = new PresentationWatermarkMasterSlideOptions();
    masterSlideOptions.MasterSlideIndex = -1; // default
    watermarker.Add(watermark, masterSlideOptions);

    // Ajoutez un filigrane à toutes les diapositives de mise en page
    PresentationWatermarkLayoutSlideOptions layoutSlideOptions = new PresentationWatermarkLayoutSlideOptions();
    layoutSlideOptions.LayoutSlideIndex = -1; // default
    watermarker.Add(watermark, layoutSlideOptions);

    // Ajoutez un filigrane à toutes les diapositives de notes
    PresentationWatermarkNoteSlideOptions noteSlideOptions = new PresentationWatermarkNoteSlideOptions();
    noteSlideOptions.SlideIndex = -1; // default
    watermarker.Add(watermark, noteSlideOptions);

    // Ajoutez un filigrane au handout master
    PresentationWatermarkMasterHandoutSlideOptions masterHandoutSlideOptions = new PresentationWatermarkMasterHandoutSlideOptions();
    watermarker.Add(watermark, masterHandoutSlideOptions);

    // Ajoutez un filigrane au notes master
    PresentationWatermarkMasterNotesSlideOptions masterNotesSlideOptions = new PresentationWatermarkMasterNotesSlideOptions();
    watermarker.Add(watermark, masterNotesSlideOptions);

    watermarker.Save();
}
```

### Voir aussi

* class [PresentationWatermarkOptions](../presentationwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
