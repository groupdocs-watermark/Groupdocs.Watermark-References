---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Recupera il conteggio dei crediti consumati."
type: docs
weight: 30
url: /it/net/groupdocs.watermark/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Recupera il conteggio dei crediti consumati.

```csharp
public static long GetConsumptionCredit()
```

### Valore di ritorno

Il conteggio dei crediti consumati.

### Esempi

L'esempio seguente dimostra come recuperare il conteggio dei crediti consumati.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Vedi anche

* class [Metered](../../metered)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
