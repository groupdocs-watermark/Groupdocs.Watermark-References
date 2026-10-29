---
title: "Remove"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Supprime le filigrane du document."
type: docs
weight: 90
url: /fr/net/groupdocs.watermark/watermarker/remove/
---
## Remove(PossibleWatermark) {#remove}

Supprime le filigrane du document.

```csharp
public void Remove(PossibleWatermark possibleWatermark)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| possibleWatermark | PossibleWatermark | Le filigrane à supprimer. |

### Remarques

En savoir plus sur la suppression des filigranes : [Suppression des filigranes trouvés](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks).

### Exemples

Trouver et supprimer le premier filigrane possible contenant un texte ou une image particulier d'un document de tout type pris en charge.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    if (watermarks.Count > 0)
    {
        watermarker.Remove(watermarks[0]);
    }

    watermarker.Save(@"D:\output.doc");
}
```

### Voir aussi

* class [PossibleWatermark](../../../groupdocs.watermark.search/possiblewatermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Remove(PossibleWatermarkCollection) {#remove_1}

Supprime tous les filigranes de la collection du document.

```csharp
public void Remove(PossibleWatermarkCollection possibleWatermarks)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| possibleWatermarks | PossibleWatermarkCollection | La collection de filigranes à supprimer. |

### Remarques

En savoir plus sur la suppression des filigranes [Suppression des filigranes trouvés](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks).

### Exemples

Trouver et supprimer tous les filigranes possibles contenant un texte ou une image particuliers d'un document de tout type pris en charge.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    watermarker.Remove(watermarks);
    watermarker.Save(@"D:\output.doc");
}
```

### Voir aussi

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
