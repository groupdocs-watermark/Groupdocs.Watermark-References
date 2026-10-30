---
title: "Metered"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Biedt methoden om het component te licentiëren met een Metered-licentie."
type: docs
weight: 1690
url: /nl/net/groupdocs.watermark/metered/
---
## Metered class

Biedt methoden om het component te licentiëren met een Metered-licentie.

```csharp
public class Metered
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Metered](metered)() | Initialiseert een nieuw exemplaar van de [`Metered`](../metered) klasse. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [SetMeteredKey](../../groupdocs.watermark/metered/setmeteredkey)(string, string) | Activeert het product met Metered-sleutels. |
| static [GetConsumptionCredit](../../groupdocs.watermark/metered/getconsumptioncredit)() | Haalt het aantal verbruikte credits op. |
| static [GetConsumptionQuantity](../../groupdocs.watermark/metered/getconsumptionquantity)() | Haalt de hoeveelheid verwerkte MB's op. |

### Opmerkingen

**Learn more**

* More about Metered licensing: [Metered Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing/metered)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### Voorbeelden

Het volgende voorbeeld toont hoe u het product activeert met Metered-sleutels.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Zie ook

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
