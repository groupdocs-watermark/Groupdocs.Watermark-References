---
title: "License"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Methoden bereit, um die Komponente zu lizenzieren."
type: docs
weight: 1680
url: /de/net/groupdocs.watermark/license/
---
## License class

Stellt Methoden bereit, um die Komponente zu lizenzieren.

```csharp
public sealed class License
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [License](license)() | Initialisiert eine neue Instanz der [`License`](../license) Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense)(Stream) | Lizenziert die Komponente. |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense_1)(string) | Lizenziert die Komponente. |

### Hinweise

* More about licensing: [GroupDocs Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### Beispiele

Dieses Beispiel zeigt, wie man die Lizenz aus einer lokalen Datei einrichtet.

```csharp
// License-Klasse initialisieren.
License license = new License();

// Pfad zur .lic-Datei festlegen.
license.SetLicense("C:\\GroupDocs.Watermark.lic");
```

### Siehe auch

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
