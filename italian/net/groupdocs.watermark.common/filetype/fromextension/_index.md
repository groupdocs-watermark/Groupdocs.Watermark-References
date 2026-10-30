---
title: "FromExtension"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Mappa l'estensione del file al tipo di file."
type: docs
weight: 590
url: /it/net/groupdocs.watermark.common/filetype/fromextension/
---
## FileType.FromExtension method

Mappa l'estensione del file al tipo di file.

```csharp
public static FileType FromExtension(string extension)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| extension | String | L'estensione del file (incluso il punto "."). |

### Valore di ritorno

Quando il tipo di file è supportato lo restituisce, altrimenti restituisce il tipo di file predefinito [`Unknown`](../unknown).

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generata quando *extension* è null o una stringa vuota. |

### Vedi anche

* class [FileType](../../filetype)
* namespace [GroupDocs.Watermark.Common](../../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
