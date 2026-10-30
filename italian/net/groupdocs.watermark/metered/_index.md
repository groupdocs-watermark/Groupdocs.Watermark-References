---
title: "Metered"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Fornisce metodi per licenziare il componente con licenza a consumo."
type: docs
weight: 1690
url: /it/net/groupdocs.watermark/metered/
---
## Metered class

Fornisce metodi per licenziare il componente con licenza a consumo.

```csharp
public class Metered
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Metered](metered)() | Inizializza una nuova istanza della classe [`Metered`](../metered). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [SetMeteredKey](../../groupdocs.watermark/metered/setmeteredkey)(string, string) | Attiva il prodotto con chiavi Metered. |
| static [GetConsumptionCredit](../../groupdocs.watermark/metered/getconsumptioncredit)() | Recupera il conteggio dei crediti consumati. |
| static [GetConsumptionQuantity](../../groupdocs.watermark/metered/getconsumptionquantity)() | Recupera la quantità di MB elaborati. |

### Osservazioni

**Learn more**

* More about Metered licensing: [Metered Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing/metered)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### Esempi

L'esempio seguente dimostra come attivare il prodotto con chiavi a consumo.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Vedi anche

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
