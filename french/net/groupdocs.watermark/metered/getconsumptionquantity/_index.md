---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Récupère la quantité de Mo traités."
type: docs
weight: 40
url: /fr/net/groupdocs.watermark/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Récupère la quantité de Mo traités.

```csharp
public static decimal GetConsumptionQuantity()
```

### Valeur de retour

Le nombre de Mo traités.

### Exemples

L'exemple suivant montre comment récupérer le nombre de Mo traités.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Voir aussi

* class [Metered](../../metered)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
