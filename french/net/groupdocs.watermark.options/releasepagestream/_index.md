---
title: "ReleasePageStream"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente une méthode qui libère le flux créé par le délégué CreatePageStream./createpagestream."
type: docs
weight: 2160
url: /fr/net/groupdocs.watermark.options/releasepagestream/
---
## ReleasePageStream delegate

Représente une méthode qui libère le flux créé par le délégué [`CreatePageStream`](../createpagestream).

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Le numéro de page d'un aperçu de page généré. |
| pageStream | Stream | Le flux contenant l'aperçu de page généré. |

### Voir aussi

* namespace [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
