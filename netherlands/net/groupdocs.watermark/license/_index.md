---
title: "License"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Biedt methoden om het component te licentiëren."
type: docs
weight: 1680
url: /nl/net/groupdocs.watermark/license/
---
## License class

Biedt methoden om het component te licentiëren.

```csharp
public sealed class License
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [License](license)() | Initialiseert een nieuw exemplaar van de [`License`](../license) klasse. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense)(Stream) | Licentieert de component. |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense_1)(string) | Licentieert de component. |

### Opmerkingen

* More about licensing: [GroupDocs Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### Voorbeelden

Dit voorbeeld laat zien hoe je een licentie instelt vanuit het lokale bestand.

```csharp
// Initialiseer de License-klasse.
License license = new License();

// Stel het pad in naar het .lic-bestand.
license.SetLicense("C:\\GroupDocs.Watermark.lic");
```

### Zie ook

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
