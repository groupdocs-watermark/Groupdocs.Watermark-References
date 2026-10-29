---
title: "Metered"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Methoden bereit, um die Komponente mit einer nutzungsbasierten Lizenz zu lizenzieren."
type: docs
weight: 1690
url: /de/net/groupdocs.watermark/metered/
---
## Metered class

Stellt Methoden bereit, um die Komponente mit einer nutzungsbasierten Lizenz zu lizenzieren.

```csharp
public class Metered
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Metered](metered)() | Initialisiert eine neue Instanz der [`Metered`](../metered) Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetMeteredKey](../../groupdocs.watermark/metered/setmeteredkey)(string, string) | Aktiviert das Produkt mit Metered-Schlüsseln. |
| static [GetConsumptionCredit](../../groupdocs.watermark/metered/getconsumptioncredit)() | Ermittelt die Anzahl der verbrauchten Credits. |
| static [GetConsumptionQuantity](../../groupdocs.watermark/metered/getconsumptionquantity)() | Ermittelt die Menge der verarbeiteten MBs. |

### Hinweise

**Learn more**

* More about Metered licensing: [Metered Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing/metered)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### Beispiele

Das folgende Beispiel zeigt, wie das Produkt mit Metered-Schlüsseln aktiviert wird.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Siehe auch

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
