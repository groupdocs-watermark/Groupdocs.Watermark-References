---
title: "DiagramPageWatermarkOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane de forme à une page particulière d'un document Visio."
type: docs
weight: 1720
url: /fr/net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/
---
## DiagramPageWatermarkOptions class

Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane de forme à une page particulière d'un document Visio.

```csharp
public sealed class DiagramPageWatermarkOptions : DiagramWatermarkOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DiagramPageWatermarkOptions](diagrampagewatermarkoptions)() | Initialise une nouvelle instance de la classe [`DiagramPageWatermarkOptions`](../diagrampagewatermarkoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Obtient ou définit une valeur indiquant si la modification de la forme dans Visio est interdite. |
| [PageIndex](../../groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/pageindex) { get; set; } | Obtient ou définit l'index de page auquel ajouter le filigrane. |

### Remarques

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### Exemples

Ajoute un filigrane protégé à la première page d'un document Visio.

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
    options.IsLocked = true;
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Voir aussi

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
