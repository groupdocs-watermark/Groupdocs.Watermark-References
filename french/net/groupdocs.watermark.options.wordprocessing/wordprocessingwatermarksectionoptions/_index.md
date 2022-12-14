---
title: WordProcessingWatermarkSectionOptions
second_title: Référence de l'API GroupDocs.Watermark pour .NET
description: Représente les options lors de lajout dun filigrane de forme à une section de document Word.
type: docs
weight: 2380
url: /fr/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarksectionoptions/
---
## WordProcessingWatermarkSectionOptions class

Représente les options lors de l'ajout d'un filigrane de forme à une section de document Word.

```csharp
public sealed class WordProcessingWatermarkSectionOptions : WordProcessingWatermarkBaseOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [WordProcessingWatermarkSectionOptions](wordprocessingwatermarksectionoptions)() | Initialise une nouvelle instance du[`WordProcessingWatermarkSectionOptions`](../wordprocessingwatermarksectionoptions) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | Obtient ou définit le texte descriptif (alternatif) qui sera associé à une forme. |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | Obtient ou définit une valeur de[`WordProcessingImageEffects`](../wordprocessingimageeffects) ou [`WordProcessingTextEffects`](../wordprocessingtexteffects) pour les effets qui doivent être appliqués au filigrane. |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | Obtient ou définit une valeur indiquant si une modification de la forme dans Word est interdite. |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | Obtient ou définit le type de verrouillage du filigrane. |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | Obtient ou définit le nom d'une forme. |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | Obtient ou définit un mot de passe utilisé pour verrouiller le filigrane. |
| [SectionIndex](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarksectionoptions/sectionindex) { get; set; } | Obtient ou définit l'index d'une section à laquelle ajouter le filigrane. |

### Remarques

**Apprendre encore plus:**

* [Ajouter des filigranes aux documents de traitement de texte](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### Exemples

Ajouter un filigrane à une section particulière d'un document Word.

```csharp
WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.doc", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
    watermark.HorizontalAlignment = HorizontalAlignment.Center;
    watermark.VerticalAlignment = VerticalAlignment.Center;
    watermark.ForegroundColor = Color.Red;

    WordProcessingWatermarkSectionOptions options = new WordProcessingWatermarkSectionOptions();
    options.SectionIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Voir également

* class [WordProcessingWatermarkBaseOptions](../wordprocessingwatermarkbaseoptions)
* espace de noms [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* Assemblée [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
