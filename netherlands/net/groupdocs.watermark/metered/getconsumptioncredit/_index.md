---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Haalt het aantal verbruikte credits op."
type: docs
weight: 30
url: /nl/net/groupdocs.watermark/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Haalt het aantal verbruikte credits op.

```csharp
public static long GetConsumptionCredit()
```

### Retourwaarde

Het aantal verbruikte credits.

### Voorbeelden

Het volgende voorbeeld toont hoe het aantal verbruikte credits op te halen.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Zie ook

* class [Metered](../../metered)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
