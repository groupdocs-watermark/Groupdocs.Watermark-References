---
title: "WordProcessingWatermarkPagesOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente les options lors de l'ajout d'un filigrane aux pages d'un document Word."
type: docs
weight: 2410
url: /fr/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/
---
## WordProcessingWatermarkPagesOptions class

Représente les options lors de l'ajout d'un filigrane aux pages d'un document Word.

```csharp
public sealed class WordProcessingWatermarkPagesOptions : WordProcessingWatermarkBaseOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [WordProcessingWatermarkPagesOptions](wordprocessingwatermarkpagesoptions)() | Initialise une nouvelle instance de la classe [`WordProcessingWatermarkPagesOptions`](../wordprocessingwatermarkpagesoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | Obtient ou définit le texte descriptif (alternatif) qui sera associé à une forme. |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | Obtient ou définit une valeur de [`WordProcessingImageEffects`](../wordprocessingimageeffects) ou de [`WordProcessingTextEffects`](../wordprocessingtexteffects) pour les effets qui doivent être appliqués au filigrane. |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | Obtient ou définit une valeur indiquant si la modification de la forme dans Word est interdite. |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | Obtient ou définit le type de verrouillage du filigrane. |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | Obtient ou définit le nom d'une forme. |
| [PageNumbers](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/pagenumbers) { get; set; } | Obtient ou définit les numéros de page pour ajouter le filigrane. |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | Obtient ou définit un mot de passe utilisé pour verrouiller le filigrane. |

### Remarques

**Learn more:**

* [Add watermarks to word processing documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### Exemples

Ajoute un filigrane à une page particulière d’un document Word.

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

### Voir aussi

* class [WordProcessingWatermarkBaseOptions](../wordprocessingwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
