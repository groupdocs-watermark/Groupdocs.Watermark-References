---
title: PdfContent
second_title: Référence de l'API GroupDocs.Watermark pour .NET
description: Représente un document pdf où un filigrane peut être placé.
type: docs
weight: 610
url: /fr/net/groupdocs.watermark.contents.pdf/pdfcontent/
---
## PdfContent class

Représente un document pdf où un filigrane peut être placé.

```csharp
public class PdfContent : Content
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.pdf/pdfcontent/attachments) { get; } | Obtient la collection de toutes les pièces jointes de ce[`PdfContent`](../pdfcontent) . |
| [PageMarginType](../../groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype) { get; set; } | Obtient ou définit les marges de page pdf à utiliser lors de l'ajout de filigrane. |
| [Pages](../../groupdocs.watermark.contents.pdf/pdfcontent/pages) { get; } | Obtient la collection de toutes les pages de ce[`PdfContent`](../pdfcontent) . |

## Méthodes

| Nom | La description |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/decrypt)() | Déchiffre le contenu. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Supprime l'instance actuelle. |
| [Encrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/encrypt#encrypt)(string) | Crypte le document en utilisant le même mot de passe que le mot de passe utilisateur et le mot de passe propriétaire. |
| [Encrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/encrypt#encrypt_1)(string, string, PdfPermissions, PdfCryptoAlgorithm) | Crypte le contenu. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Recherche toutes les images dans le contenu. La recherche est effectuée dans les objets spécifiés dans[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trouve des images selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Rasterize](../../groupdocs.watermark.contents.pdf/pdfcontent/rasterize)(int, int, PdfImageConversionFormat) | Convertit toutes les pages de contenu en images. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Recherche tous les filigranes possibles dans le contenu. La recherche est effectuée dans les objets spécifiés dans[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trouve les filigranes possibles selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |

### Remarques

**Apprendre encore plus:**

* [Ajouter des filigranes aux documents PDF](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)
* [Objets existants dans le document PDF](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+PDF+document)
* [Pixelliser un document ou une page](https://docs.groupdocs.com/display/watermarknet/Rasterize+document+or+page)
* [Filigranes dans le document PDF](https://docs.groupdocs.com/display/watermarknet/Watermarks+in+PDF+document)

### Voir également

* class [Content](../../groupdocs.watermark.contents/content)
* espace de noms [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* Assemblée [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->