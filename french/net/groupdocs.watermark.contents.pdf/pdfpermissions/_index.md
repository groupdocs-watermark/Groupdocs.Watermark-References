---
title: "PdfPermissions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente les autorisations des utilisateurs pour un document PDF."
type: docs
weight: 760
url: /fr/net/groupdocs.watermark.contents.pdf/pdfpermissions/
---
## PdfPermissions enumeration

Représente les autorisations de l'utilisateur pour un document pdf.

```csharp
[Flags]
public enum PdfPermissions
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| PrintDocument | `4` | Imprimer le contenu. |
| ModifyContent | `8` | Modifier le contenu. |
| ExtractContent | `10` | Copier ou extraire autrement le texte et les graphiques du document. |
| ModifyTextAnnotations | `20` | Ajouter ou modifier des annotations de texte. |
| FillForm | `100` | Remplir les champs de formulaire interactifs existants. |
| ExtractContentWithDisabilities | `200` | Extraire le texte et les graphiques. |
| AssembleDocument | `400` | Assembler le contenu. |
| PrintingQuality | `800` | Imprimer le contenu vers une représentation à partir de laquelle une copie numérique fidèle du document PDF pourrait être générée. |

### Voir aussi

* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
