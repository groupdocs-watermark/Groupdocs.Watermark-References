---
title: "DiagramShapeWatermarkOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane de forme à un document Visio."
type: docs
weight: 1750
url: /fr/net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/
---
## DiagramShapeWatermarkOptions class

Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane de forme à un document Visio.

```csharp
public sealed class DiagramShapeWatermarkOptions : DiagramWatermarkOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DiagramShapeWatermarkOptions](diagramshapewatermarkoptions)() | Initialise une nouvelle instance de la classe [`DiagramShapeWatermarkOptions`](../diagramshapewatermarkoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Obtient ou définit une valeur indiquant si la modification de la forme dans Visio est interdite. |
| [PlacementType](../../groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/placementtype) { get; set; } | Obtient ou définit une valeur spécifiant sur quelles pages un filigrane doit être ajouté. |

### Remarques

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### Exemples

Ajoute un filigrane protégé à toutes les pages du document Visio.

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
    options.IsLocked = true;
    options.PlacementType = DiagramWatermarkPlacementType.AllPages; // default

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Voir aussi

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
