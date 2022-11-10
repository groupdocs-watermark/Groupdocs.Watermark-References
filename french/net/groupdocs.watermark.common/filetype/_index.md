---
title: FileType
second_title: Référence de l'API GroupDocs.Watermark pour .NET
description: Représente le type de fichier.
type: docs
weight: 40
url: /fr/net/groupdocs.watermark.common/filetype/
---
## FileType class

Représente le type de fichier.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | Obtient le suffixe du nom de fichier (y compris le point "."), par exemple ".doc". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | Obtient le nom du type de fichier, par exemple, "Document Microsoft Word". |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | Obtient la famille de format. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | Mappe l'extension de fichier au type de fichier. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | Détermine si le courant[`FileType`](../filetype) est le même que celui spécifié[`FileType`](../filetype) objet. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | Détermine si le courant[`FileType`](../filetype) est le même que l'objet spécifié. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | Renvoie un code de hachage pour le courant[`FileType`](../filetype) objet. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | Récupère les types de fichiers pris en charge. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | Détermine si deux[`FileType`](../filetype) les objets sont les mêmes. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | Détermine si deux[`FileType`](../filetype) les objets ne sont pas les mêmes. |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | Les fichiers ayant l'extension .BMP représentent des fichiers d'image bitmap utilisés pour stocker des images numériques bitmap. Ces images sont indépendantes de l'adaptateur graphique et sont également appelées format de fichier bitmap indépendant du périphérique (DIB) . En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/bmp/) . |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | Les fichiers avec l'extension .doc représentent des documents générés par Microsoft Word ou d'autres documents de traitement de texte au format de fichier binaire. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/doc/) . |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | Les fichiers DOCM sont des documents générés par Microsoft Word 2007 ou version ultérieure avec la possibilité d'exécuter des macros. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/docm/) . |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX est un format bien connu pour les documents Microsoft Word. Introduit à partir de 2007 avec la release de Microsoft Office 2007, la structure de ce nouveau format de document est passée de plain binary à une combinaison de fichiers XML et binaires. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/docx/) . |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | Les fichiers avec l'extension .DOT sont des fichiers modèles créés par Microsoft Word pour avoir des paramètres pré-formatés pour la génération d'autres fichiers DOC ou DOCX. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/dot/) . |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | Un fichier avec l'extension DOTM représente un fichier modèle créé avec Microsoft Word 2007 ou supérieur. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/dotm/) . |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | Les fichiers avec l'extension DOTX sont des fichiers modèles créés par Microsoft Word pour avoir des paramètres pré-formatés pour la génération d'autres fichiers DOCX. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/dotx/) . |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | Le format de fichier EML représente les messages électroniques enregistrés à l'aide d'Outlook et d'autres applications pertinentes. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/email/eml/) . |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | Le format de fichier EMLX est implémenté et développé par Apple. L'application Apple Mail utilise le format de fichier EMLX pour exporter les e-mails. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/email/emlx/) . |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML stocké dans un fichier XML plat au lieu d'un package ZIP (.xml). En savoir plus sur ce format de fichier[ici](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML Macro-Enabled Document stocké dans un fichier XML plat au lieu d'un package ZIP (.xml). En savoir plus sur ce format de fichier[ici](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Modèle Office Open XML WordprocessingML (sans macro) stocké dans un fichier XML plat au lieu d'un package ZIP (.xml). En savoir plus sur ce format de fichier[ici](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Office Open XML WordprocessingML Macro-Enabled Template stocké dans un fichier XML plat au lieu d'un package ZIP (.xml). En savoir plus sur ce format de fichier[ici](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | Un format GIF ou Graphical Interchange est un type d'image hautement compressée. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/gif/) . |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | Un JPEG est un type de format d'image enregistré à l'aide de la méthode de compression avec perte. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF) est un système de codage d'image et une norme de compression d'image de pointe. Conçu, en utilisant la technologie des ondelettes JPEG 2000 peut coder du contenu sans perte dans n'importe quelle qualité à la fois. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | Un JPEG est un type de format d'image enregistré à l'aide de la méthode de compression avec perte. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM) est un système de codage d'image et une norme de compression d'image de pointe. Conçu, en utilisant la technologie des ondelettes JPEG 2000 peut coder du contenu sans perte dans n'importe quelle qualité à la fois. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX) est un système de codage d'image et une norme de compression d'image de pointe. Conçu, en utilisant la technologie des ondelettes JPEG 2000 peut coder du contenu sans perte dans n'importe quelle qualité à la fois. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG est un format de fichier utilisé par Microsoft Outlook et Exchange pour stocker les messages électroniques, les contacts, les rendez-vous ou d'autres tâches. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/email/msg/) . |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | Les fichiers ODT sont des types de documents créés avec des applications de traitement de texte basées sur le format de fichier texte OpenDocument . Ceux-ci sont créés avec des applications de traitement de texte telles que OpenOffice Writer gratuit et peuvent contenir du contenu tel que du texte, des images, des objets et des styles. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/odt/) . |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | Les fichiers avec l'extension .OFT représentent des fichiers de modèle de message créés à l'aide de Microsoft Outlook. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/email/oft/) . |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Office ouvrir le fichier xml (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Portable Document Format (PDF) est un type de document créé par Adobe dans les années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et autres documents de référence dans un format qui est indépendant du logiciel d'application, du matériel ainsi que du système d'exploitation. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/view/pdf/) . |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG, Portable Network Graphics, fait référence à un type de format de fichier d'image raster qui utilise une compression sans perte. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/png/) . |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | Les fichiers avec l'extension POTM sont des fichiers de modèle Microsoft PowerPoint prenant en charge les macros. Les fichiers POTM sont créés avec PowerPoint 2007 ou supérieur et contiennent des paramètres par défaut qui peuvent être utilisés pour créer d'autres fichiers de présentation. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/potm/) . |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | Les fichiers avec l'extension .POTX représentent des modèles de présentation Microsoft PowerPoint créés avec Microsoft PowerPoint 2007 et versions ultérieures. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/potx/) . |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS, diaporama PowerPoint, les fichiers sont créés à l'aide de Microsoft PowerPoint à des fins de diaporama. La lecture et la création de fichiers PPS sont prises en charge par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/pps/) . |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | Les fichiers avec l'extension PPSM représentent un format de fichier de diaporama compatible macro créé avec Microsoft PowerPoint 2007 ou supérieur. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/ppsm/) . |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX, diaporama Power Point, les fichiers sont créés à l'aide de Microsoft PowerPoint 2007 et supérieur à des fins de diaporama. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/ppsx/) . |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | Un fichier avec l'extension PPT représente un fichier PowerPoint composé d'une collection de diapositives for affichées sous forme de diaporama. Il spécifie le format de fichier binaire utilisé par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/ppt/) . |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | Les fichiers avec l'extension PPTM sont des fichiers de présentation prenant en charge les macros qui sont créés avec Microsoft PowerPoint 2007 ou des versions supérieures. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/pptm/) . |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | Les fichiers avec l'extension PPTX sont des fichiers de présentation créés avec l'application Microsoft PowerPoint populaire. Contrairement à la version précédente du format de fichier de présentation PPT qui était binaire, le format PPTX est basé sur le format de fichier de présentation XML ouvert de Microsoft PowerPoint. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/pptx/) . |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Introduit et documenté par Microsoft, le format RTF (Rich Text Format) représente une méthode d'encodage du texte et des graphiques formatés à utiliser dans les applications. Le format facilite l'échange multiplateforme document avec d'autres produits Microsoft, servant ainsi l'objectif d'interopérabilité. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/rtf/) . |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF ou TIF, Tagged Image File Format, représente des images raster destinées à être utilisées sur une variété d'appareils conformes à cette norme de format de fichier. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF ou TIF, Tagged Image File Format, représente des images raster destinées à être utilisées sur une variété d'appareils conformes à cette norme de format de fichier. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | Représente un type de fichier inconnu. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW est le format de fichier Visio Graphics Service qui spécifie les flux et les stockages requis pour le rendu d'un dessin Web. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/web/vdw/) . |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Tout dessin ou graphique créé dans Microsoft Visio, mais enregistré au format XML porte l'extension .VDX. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/vdx/) . |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | Les fichiers VSD sont des dessins créés avec l'application Microsoft Visio pour représenter une variété d'objets graphiques et l'interconnexion entre ceux-ci. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vsd/) . |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | Les fichiers avec l'extension VSDM sont des fichiers de dessin créés avec l'application Microsoft Visio qui prend en charge les macros. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vsdm/) . |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | Les fichiers avec l'extension .VSDX représentent le format de fichier Microsoft Visio introduit à partir de Microsoft Office 2013. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vsdx/) . |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS sont des fichiers stencil créés avec Microsoft Visio 2007 et versions antérieures. Les fichiers Stencil fournissent des objets drawing qui peuvent être inclus dans un dessin .VSD Visio. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vss/) . |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | Les fichiers avec l'extension .VSSM sont des fichiers Microsoft Visio Stencil qui prennent en charge les macros. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/vssm/) . |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | Les fichiers avec l'extension .VSSX sont des gabarits de dessin créés avec Microsoft Visio 2013 et supérieur. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vssx/) . |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | Les fichiers avec l'extension VST sont des fichiers d'image vectorielle créés avec Microsoft Visio et servent de modèle pour créer d'autres fichiers. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vst/) . |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | Les fichiers avec l'extension VSTM sont des fichiers modèles créés avec Microsoft Visio qui prennent en charge les macros. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/vstm/) . |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | Les fichiers avec des extensions VSTX sont des fichiers de modèle de dessin créés avec Microsoft Visio 2013 et supérieur. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vstx/) . |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | Les fichiers avec l'extension .VSX font référence à des gabarits constitués de dessins et de formes utilisés pour créer des diagrammes dans Microsoft Visio. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vsx/) . |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | Un fichier avec l'extension VTX est un modèle de dessin Microsoft Visio qui est enregistré sur le disque au format de fichier XML. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/vtx/) . |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP, introduit par Google, est un format de fichier d'image Web raster moderne basé sur une compression sans perte et avec perte. Il offre la même qualité d'image tout en réduisant considérablement la taille de l'image. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/webp/) . |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | Les fichiers avec l'extension XLS représentent le format de fichier binaire Excel. Ces fichiers peuvent être créés par Microsoft Excel ainsi que par d'autres tableurs similaires tels que OpenOffice Calc ou Apple Numbers. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/specification/spreadsheet/xls/) . |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | Le format de fichier XLSB spécifie le format de fichier binaire Excel, qui est une collection d'enregistrements et de structures qui spécifient le contenu du classeur Excel. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/specification/spreadsheet/xlsb/) . |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | Les fichiers avec l'extension XLSM sont un type de fichiers de feuille de calcul prenant en charge les macros. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/specification/spreadsheet/xlsm/) . |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX est un format bien connu pour les documents Microsoft Excel qui a été introduit par Microsoft avec la version de Microsoft Office 2007. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/specification/spreadsheet/xlsx/) . |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | Les fichiers avec l'extension .XLT sont des fichiers modèles créés avec Microsoft Excel qui est une application tableur qui fait partie de la suite Microsoft Office. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/specification/spreadsheet/xlt/) . |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | L'extension de fichier XLTM représente les fichiers générés par Microsoft Excel en tant que fichiers de modèle Macro-enabled . En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/specification/spreadsheet/xltm/) . |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | Les fichiers avec l'extension XLTX représentent des fichiers de modèle Microsoft Excel basés sur les spécifications de format de fichier Office OpenXML . En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/specification/spreadsheet/xltx/) . |

### Remarques

Cette classe fournit des méthodes pour obtenir la liste de tous les types de fichiers pris en charge par**GroupDocs.WatermarkGroupDocs.Watermark**.**Apprendre encore plus**

* [Formats de documents pris en charge](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Obtenir les formats de fichiers pris en charge](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Obtenir des informations sur les documents](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Voir également

* espace de noms [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* Assemblée [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
