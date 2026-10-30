---
title: "License"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Tillhandahåller metoder för att licensiera komponenten."
type: docs
weight: 1680
url: /sv/net/groupdocs.watermark/license/
---
## License class

Tillhandahåller metoder för att licensiera komponenten.

```csharp
public sealed class License
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [License](license)() | Initierar en ny instans av [`License`](../license)-klassen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense)(Stream) | Licensierar komponenten. |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense_1)(string) | Licensierar komponenten. |

### Anmärkningar

* More about licensing: [GroupDocs Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### Exempel

Detta exempel visar hur man konfigurerar licensen från den lokala filen.

```csharp
// Initiera License-klassen.
License license = new License();

// Ange sökväg till .lic-fil.
license.SetLicense("C:\\GroupDocs.Watermark.lic");
```

### Se även

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
