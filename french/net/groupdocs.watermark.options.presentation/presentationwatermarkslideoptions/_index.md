---
title: "PresentationWatermarkSlideOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente les options lors de l'ajout d'un filigrane à une diapositive d'un document Presentation."
type: docs
weight: 2130
url: /fr/net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/
---
## PresentationWatermarkSlideOptions class

Représente les options lors de l'ajout d'un filigrane à une diapositive d'un document Presentation.

```csharp
public sealed class PresentationWatermarkSlideOptions : PresentationWatermarkBaseSlideOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PresentationWatermarkSlideOptions](presentationwatermarkslideoptions)() | Initialise une nouvelle instance de la classe [`PresentationWatermarkSlideOptions`](../presentationwatermarkslideoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternativetext) { get; set; } | Obtient ou définit le texte descriptif (alternatif) qui sera associé à une forme. |
| [Effects](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects) { get; set; } | Obtient ou définit une valeur de [`PresentationImageEffects`](../presentationimageeffects) ou de [`PresentationTextEffects`](../presentationtexteffects) pour les effets qui doivent être appliqués au filigrane. |
| [IsLocked](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/islocked) { get; set; } | Obtient ou définit une valeur indiquant si la modification de la forme dans PowerPoint est interdite. |
| [Name](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name) { get; set; } | Obtient ou définit le nom d'une forme. |
| [ProtectWithUnreadableCharacters](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protectwithunreadablecharacters) { get; set; } | Obtient ou définit une valeur indiquant si les caractères du filigrane texte sont mélangés avec des caractères illisibles. |
| [SlideIndex](../../groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/slideindex) { get; set; } | Obtient ou définit l’index de la diapositive sur laquelle ajouter le filigrane. |

### Remarques

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

### Exemples

Ajoutez un filigrane à une diapositive particulière d’une présentation Power Point.

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

### Voir aussi

* class [PresentationWatermarkBaseSlideOptions](../presentationwatermarkbaseslideoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
