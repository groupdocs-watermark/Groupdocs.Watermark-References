---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Récupère le nombre de crédits consommés."
type: docs
weight: 30
url: /fr/net/groupdocs.watermark/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Récupère le nombre de crédits consommés.

```csharp
public static long GetConsumptionCredit()
```

### Valeur de retour

Le nombre de crédits consommés.

### Exemples

L'exemple suivant montre comment récupérer le nombre de crédits consommés.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Voir aussi

* class [Metered](../../metered)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
