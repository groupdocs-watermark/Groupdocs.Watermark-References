---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Ermittelt die Anzahl der verbrauchten Credits."
type: docs
weight: 30
url: /de/net/groupdocs.watermark/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Ermittelt die Anzahl der verbrauchten Credits.

```csharp
public static long GetConsumptionCredit()
```

### Rückgabewert

Die Anzahl der verbrauchten Credits.

### Beispiele

Das folgende Beispiel zeigt, wie die Anzahl der verbrauchten Credits abgerufen wird.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Siehe auch

* class [Metered](../../metered)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
