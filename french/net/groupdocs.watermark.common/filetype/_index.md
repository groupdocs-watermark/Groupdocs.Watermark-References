---
title: "FileType"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente le type de fichier."
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

| Nom | Description |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | Obtient le suffixe du nom de fichier (y compris le point ".") p. ex., ".doc". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | Obtient le nom du type de fichier, p. ex., "Microsoft Word Document". |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | Obtient la famille de format. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | Mappe l'extension de fichier au type de fichier. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | Détermine si le [`FileType`](../filetype) actuel est le même que l'objet [`FileType`](../filetype) spécifié. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | Détermine si le [`FileType`](../filetype) actuel est identique à l'objet spécifié. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | Renvoie un code de hachage pour l'objet [`FileType`](../filetype) actuel. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | Récupère les types de fichiers pris en charge. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | Détermine si deux objets [`FileType`](../filetype) sont identiques. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | Détermine si deux objets [`FileType`](../filetype) ne sont pas identiques. |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | Les fichiers avec l'extension .BMP représentent des fichiers d'images bitmap utilisés pour stocker des images numériques bitmap. Ces images sont indépendantes de l'adaptateur graphique et sont également appelées format de fichier bitmap indépendant du dispositif (DIB). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/bmp/). |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | Les fichiers avec l'extension .doc représentent des documents générés par Microsoft Word ou d'autres traitements de texte au format binaire. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/doc/). |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | Les fichiers DOCM sont des documents générés par Microsoft Word 2007 ou version ultérieure, avec la capacité d'exécuter des macros. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/docm/). |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX est un format bien connu pour les documents Microsoft Word. Introduit en 2007 avec la sortie de Microsoft Office 2007, la structure de ce nouveau format de document est passée du binaire pur à une combinaison de fichiers XML et binaires. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/docx/). |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | Les fichiers avec l'extension .DOT sont des modèles créés par Microsoft Word contenant des paramètres préformatés pour la génération de futurs fichiers DOC ou DOCX. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/dot/). |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | Un fichier avec l'extension DOTM représente un modèle créé avec Microsoft Word 2007 ou version ultérieure. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/dotm/). |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | Les fichiers avec l'extension DOTX sont des modèles créés par Microsoft Word contenant des paramètres préformatés pour la génération de futurs fichiers DOCX. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/dotx/). |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | Le format de fichier EML représente des messages électroniques enregistrés à l'aide d'Outlook et d'autres applications pertinentes. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/email/eml/). |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | Le format de fichier EMLX est implémenté et développé par Apple. L'application Apple Mail utilise le format de fichier EMLX pour exporter les courriels. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/email/emlx/). |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML stocké dans un fichier XML plat au lieu d'un package ZIP (.xml). En savoir plus sur ce format de fichier [ici](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Document Office Open XML WordprocessingML avec macros activées stocké dans un fichier XML plat au lieu d'un package ZIP (.xml). En savoir plus sur ce format de fichier [ici](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Modèle Office Open XML WordprocessingML (sans macros) stocké dans un fichier XML plat au lieu d'un package ZIP (.xml). En savoir plus sur ce format de fichier [ici](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Modèle Office Open XML WordprocessingML avec macros activées stocké dans un fichier XML plat au lieu d'un package ZIP (.xml). En savoir plus sur ce format de fichier [ici](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | Un GIF ou Graphical Interchange Format est un type d'image fortement compressée. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/gif/). |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | Un JPEG est un type de format d'image enregistré à l'aide d'une compression avec perte. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF) est un système de codage d'image et une norme de compression d'image à la pointe de la technologie. Conçu avec la technologie d'ondelettes, JPEG 2000 peut coder du contenu sans perte à n'importe quelle qualité instantanément. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | Un JPEG est un type de format d'image enregistré à l'aide d'une compression avec perte. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM) est un système de codage d'images et une norme de compression d'images à la pointe de la technologie. Conçu, en utilisant la technologie ondelettes, JPEG 2000 peut coder du contenu sans perte à n'importe quelle qualité d'un seul coup. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX) est un système de codage d'images et une norme de compression d'images à la pointe de la technologie. Conçu, en utilisant la technologie ondelettes, JPEG 2000 peut coder du contenu sans perte à n'importe quelle qualité d'un seul coup. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/jp2/). |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG est un format de fichier utilisé par Microsoft Outlook et Exchange pour stocker des messages électroniques, des contacts, des rendez-vous ou d'autres tâches. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/email/msg/). |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | Les fichiers ODT sont un type de documents créés avec des applications de traitement de texte basées sur le format de fichier OpenDocument Text. Ils sont créés avec des applications de traitement de texte telles que le gratuit OpenOffice Writer et peuvent contenir du contenu tel que du texte, des images, des objets et des styles. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/odt/). |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | Les fichiers avec l'extension .OFT représentent des modèles de messages créés avec Microsoft Outlook. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/email/oft/). |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Fichier Office Open XML (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Le format Portable Document Format (PDF) est un type de document créé par Adobe dans les années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et d'autres supports de référence dans un format indépendant des logiciels d'application, du matériel ainsi que du système d'exploitation. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/view/pdf/). |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG, Portable Network Graphics, désigne un type de format de fichier d'image raster qui utilise une compression sans perte. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/png/). |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | Les fichiers avec l'extension POTM sont des modèles de Microsoft PowerPoint prenant en charge les macros. Les fichiers POTM sont créés avec PowerPoint 2007 ou une version ultérieure et contiennent des paramètres par défaut pouvant être utilisés pour créer d'autres fichiers de présentation. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/potm/). |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | Les fichiers avec l'extension .POTX représentent des présentations modèles Microsoft PowerPoint créées avec Microsoft PowerPoint 2007 et versions ultérieures. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/potx/). |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS, PowerPoint Slide Show, les fichiers sont créés avec Microsoft PowerPoint à des fins de diaporama. La lecture et la création de fichiers PPS sont prises en charge par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/pps/). |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | Les fichiers avec l'extension PPSM représentent un format de diaporama activé par macro créé avec Microsoft PowerPoint 2007 ou supérieur. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/ppsm/). |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX, Power Point Slide Show, les fichiers sont créés avec Microsoft PowerPoint 2007 et versions ultérieures à des fins de diaporama. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/ppsx/). |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | Un fichier avec l'extension PPT représente un fichier PowerPoint qui consiste en une collection de diapositives destinées à être affichées en diaporama. Il spécifie le format de fichier binaire utilisé par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/ppt/). |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | Les fichiers avec l'extension PPTM sont des présentations activées par macro créées avec Microsoft PowerPoint 2007 ou des versions supérieures. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/pptm/). |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | Les fichiers avec l'extension PPTX sont des fichiers de présentation créés avec l'application populaire Microsoft PowerPoint. Contrairement à la version précédente du format de fichier de présentation PPT qui était binaire, le format PPTX repose sur le format de fichier de présentation Microsoft PowerPoint Open XML. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/pptx/). |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Introduit et documenté par Microsoft, le Rich Text Format (RTF) représente une méthode d'encodage du texte formaté et des graphiques pour une utilisation au sein des applications. Le format facilite l'échange de documents multiplateforme avec d'autres produits Microsoft, servant ainsi l'interopérabilité. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/rtf/). |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF ou TIF, Tagged Image File Format, représente des images raster destinées à être utilisées sur une variété d'appareils conformes à cette norme de format de fichier. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/tiff/). |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF ou TIF, Tagged Image File Format, représente des images raster destinées à être utilisées sur une variété d'appareils conformes à cette norme de format de fichier. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/tiff/). |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | Représente un type de fichier inconnu. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW est le format de fichier Visio Graphics Service qui spécifie les flux et les stockages requis pour le rendu d'un dessin Web. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/web/vdw/). |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Tout dessin ou graphique créé dans Microsoft Visio, mais enregistré au format XML, possède l'extension .VDX. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vdx/). |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | Les fichiers VSD sont des dessins créés avec l'application Microsoft Visio pour représenter une variété d'objets graphiques et les interconnexions entre eux. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vsd/). |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | Les fichiers avec l'extension VSDM sont des fichiers de dessin créés avec l'application Microsoft Visio qui prend en charge les macros. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vsdm/). |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | Les fichiers avec l'extension .VSDX représentent le format de fichier Microsoft Visio introduit à partir de Microsoft Office 2013. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vsdx/). |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS sont des fichiers de gabarit créés avec Microsoft Visio 2007 et antérieurs. Les fichiers de gabarit fournissent des objets de dessin qui peuvent être inclus dans un dessin Visio .VSD. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vss/). |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | Les fichiers avec l'extension .VSSM sont des fichiers de gabarit Microsoft Visio qui offrent la prise en charge des macros. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vssm/). |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | Les fichiers avec l'extension .VSSX sont des gabarits de dessin créés avec Microsoft Visio 2013 et versions ultérieures. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vssx/). |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | Les fichiers avec l'extension VST sont des fichiers d'image vectorielle créés avec Microsoft Visio et servent de modèle pour créer d'autres fichiers. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vst/). |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | Les fichiers avec l'extension VSTM sont des fichiers modèle créés avec Microsoft Visio qui prennent en charge les macros. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vstm/). |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | Les fichiers avec l'extension VSTX sont des fichiers de modèle de dessin créés avec Microsoft Visio 2013 et versions ultérieures. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vstx/). |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | Les fichiers avec l'extension .VSX désignent des gabarits composés de dessins et de formes utilisés pour créer des diagrammes dans Microsoft Visio. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vsx/). |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | Un fichier avec l'extension VTX est un modèle de dessin Microsoft Visio qui est enregistré sur le disque au format XML. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vtx/). |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP, introduit par Google, est un format de fichier d'image raster web moderne basé sur la compression sans perte et avec perte. Il offre la même qualité d'image tout en réduisant considérablement la taille du fichier. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/webp/). |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | Les fichiers avec l'extension XLS représentent le format de fichier binaire Excel. Ces fichiers peuvent être créés par Microsoft Excel ainsi que par d'autres programmes de tableur similaires tels qu'OpenOffice Calc ou Apple Numbers. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/specification/spreadsheet/xls/). |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | Le format de fichier XLSB spécifie le Excel Binary File Format, qui est une collection d'enregistrements et de structures qui définissent le contenu d'un classeur Excel. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/specification/spreadsheet/xlsb/). |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | Les fichiers avec l'extension XLSM sont un type de fichiers de feuille de calcul qui prennent en charge les macros. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/specification/spreadsheet/xlsm/). |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX est un format bien connu pour les documents Microsoft Excel qui a été introduit par Microsoft avec la sortie de Microsoft Office 2007. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/specification/spreadsheet/xlsx/). |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | Les fichiers avec l'extension .XLT sont des fichiers de modèle créés avec Microsoft Excel, qui est une application de feuille de calcul faisant partie de la suite Microsoft Office. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/specification/spreadsheet/xlt/). |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | L'extension de fichier XLTM représente des fichiers générés par Microsoft Excel en tant que modèles activés par macro. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/specification/spreadsheet/xltm/). |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | Les fichiers avec l'extension XLTX représentent des modèles Microsoft Excel basés sur les spécifications du format de fichier Office OpenXML. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/specification/spreadsheet/xltx/). |

### Remarques

Cette classe fournit des méthodes pour obtenir la liste de tous les types de fichiers pris en charge par **GroupDocs.Watermark**.**En savoir plus**

* [Supported Document Formats](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Get supported file formats](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Voir aussi

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
