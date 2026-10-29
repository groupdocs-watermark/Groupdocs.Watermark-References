---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Ermittelt die Menge der verarbeiteten MBs."
type: docs
weight: 40
url: /de/net/groupdocs.watermark/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Ermittelt die Menge der verarbeiteten MBs.

```csharp
public static decimal GetConsumptionQuantity()
```

### Rückgabewert

Die Menge der verarbeiteten MB.

### Beispiele

Das folgende Beispiel zeigt, wie die Menge der verarbeiteten MB abgerufen wird.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Siehe auch

* class [Metered](../../metered)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
