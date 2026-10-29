---
title: "Metered"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Fournit des méthodes pour licencier le composant avec une licence à consommation."
type: docs
weight: 1690
url: /fr/net/groupdocs.watermark/metered/
---
## Metered class

Fournit des méthodes pour licencier le composant avec une licence à consommation.

```csharp
public class Metered
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Metered](metered)() | Initialise une nouvelle instance de la classe [`Metered`](../metered). |

## Méthodes

| Nom | Description |
| --- | --- |
| [SetMeteredKey](../../groupdocs.watermark/metered/setmeteredkey)(string, string) | Active le produit avec des clés Metered. |
| static [GetConsumptionCredit](../../groupdocs.watermark/metered/getconsumptioncredit)() | Récupère le nombre de crédits consommés. |
| static [GetConsumptionQuantity](../../groupdocs.watermark/metered/getconsumptionquantity)() | Récupère la quantité de Mo traités. |

### Remarques

**Learn more**

* More about Metered licensing: [Metered Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing/metered)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### Exemples

L'exemple suivant montre comment activer le produit avec des clés mesurées.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Voir aussi

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
