---
title: "License"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Fournit des méthodes pour licencier le composant."
type: docs
weight: 1680
url: /fr/net/groupdocs.watermark/license/
---
## License class

Fournit des méthodes pour licencier le composant.

```csharp
public sealed class License
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [License](license)() | Initialise une nouvelle instance de la classe [`License`](../license). |

## Méthodes

| Nom | Description |
| --- | --- |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense)(Stream) | Accorde une licence au composant. |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense_1)(string) | Accorde une licence au composant. |

### Remarques

* More about licensing: [GroupDocs Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### Exemples

Cet exemple montre comment configurer la licence à partir du fichier local.

```csharp
// Initialiser la classe License.
License license = new License();

// Définissez le chemin vers le fichier .lic.
license.SetLicense("C:\\GroupDocs.Watermark.lic");
```

### Voir aussi

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
