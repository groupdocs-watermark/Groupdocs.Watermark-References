---
title: "WordProcessingLockType"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Spécifie le type de verrouillage du filigrane dans un document Word."
type: docs
weight: 2350
url: /fr/net/groupdocs.watermark.options.wordprocessing/wordprocessinglocktype/
---
## WordProcessingLockType enumeration

Spécifie le type de verrouillage du filigrane dans un document Word.

```csharp
public enum WordProcessingLockType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| AllowOnlyRevisions | `0` | L'utilisateur ne peut ajouter que des marques de révision au document. |
| AllowOnlyComments | `1` | L'utilisateur ne peut modifier que les commentaires dans le document. |
| AllowOnlyFormFields | `2` | L'utilisateur ne peut saisir que des données dans les champs de formulaire du document. |
| ReadOnly | `3` | L'ensemble du document est en lecture seule. |
| ReadOnlyWithEditableContent | `4` | Le document est en lecture seule, mais tout le contenu sauf le filigrane est marqué comme modifiable. |
| NoLock | `-1` | Désactiver tout verrouillage du filigrane et du document. |

### Voir aussi

* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
