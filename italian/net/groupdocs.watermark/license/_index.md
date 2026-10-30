---
title: "License"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Fornisce metodi per licenziare il componente."
type: docs
weight: 1680
url: /it/net/groupdocs.watermark/license/
---
## License class

Fornisce metodi per licenziare il componente.

```csharp
public sealed class License
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [License](license)() | Inizializza una nuova istanza della classe [`License`](../license). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense)(Stream) | Concede la licenza al componente. |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense_1)(string) | Concede la licenza al componente. |

### Osservazioni

* More about licensing: [GroupDocs Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### Esempi

Questo esempio dimostra come configurare la licenza dal file locale.

```csharp
// Inizializza la classe License.
License license = new License();

// Imposta il percorso al file .lic.
license.SetLicense("C:\\GroupDocs.Watermark.lic");
```

### Vedi anche

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
