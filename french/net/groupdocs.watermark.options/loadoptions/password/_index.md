---
title: "Mot de passe"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Obtient ou définit le mot de passe pour ouvrir un document chiffré."
type: docs
weight: 50
url: /fr/net/groupdocs.watermark.options/loadoptions/password/
---
## LoadOptions.Password property

Obtient ou définit le mot de passe pour ouvrir un document chiffré.

```csharp
public string Password { get; set; }
```

### Property Value

Le mot de passe pour ouvrir un document chiffré.

### Remarques

Le mot de passe peut être nul ou une chaîne vide. La valeur par défaut est nulle. Si le contenu n'est pas chiffré, définissez-le sur nul ou une chaîne vide.

### Exemples

Charge un contenu protégé par un mot de passe.

```csharp
LoadOptions loadOptions = new LoadOptions
{
    Password = "pwd123"
};
using (Watermarker watermarker = new Watermarker(@"D:\doc.vsdx", loadOptions))
{
    // ...
}
```

### Voir aussi

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
