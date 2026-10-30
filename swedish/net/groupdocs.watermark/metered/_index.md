---
title: "Metered"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Tillhandahåller metoder för att licensiera komponenten med Metered license."
type: docs
weight: 1690
url: /sv/net/groupdocs.watermark/metered/
---
## Metered class

Tillhandahåller metoder för att licensiera komponenten med Metered license.

```csharp
public class Metered
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Metered](metered)() | Initierar en ny instans av klassen [`Metered`](../metered). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [SetMeteredKey](../../groupdocs.watermark/metered/setmeteredkey)(string, string) | Aktiverar produkt med Metered-nycklar. |
| static [GetConsumptionCredit](../../groupdocs.watermark/metered/getconsumptioncredit)() | Hämtar antalet förbrukade krediter. |
| static [GetConsumptionQuantity](../../groupdocs.watermark/metered/getconsumptionquantity)() | Hämtar mängden MB som bearbetats. |

### Anmärkningar

**Learn more**

* More about Metered licensing: [Metered Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing/metered)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### Exempel

Följande exempel visar hur man aktiverar produkt med Metered-nycklar.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Se även

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
