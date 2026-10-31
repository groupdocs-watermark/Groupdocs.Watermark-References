---
title: "SpreadsheetPreviewOptions classe"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Fournit des options pour définir les exigences et les délégués de flux pour la génération d'aperçu d'un document de feuille de calcul."
type: docs
url: /fr/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/
is_root: false
weight: 50
---


## SpreadsheetPreviewOptions class

Fournit des options pour définir les exigences et les délégués de flux pour la génération d'aperçu d'un document de feuille de calcul.

Le type SpreadsheetPreviewOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/__init__/#create_page_stream) | Initialise une nouvelle instance de la classe SpreadsheetPreviewOptions, entraînant la fermeture du flux de sortie. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/__init__/#create_page_stream-release_page_stream) | Initialise une nouvelle instance de la classe SpreadsheetPreviewOptions, faisant retourner le flux de sortie au client pour une utilisation ultérieure. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [only_data_area](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/only_data_area/) | Le drapeau pour le rendu uniquement de la zone de données sans en-têtes, pieds de page, marges. |
| [resolution](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/resolution/) | La résolution des images générées, en points par pouce. |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | Le délégué de création du flux de page utilisé pour obtenir un flux inscriptible pour chaque page rendue. (hérité de [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | La hauteur de l’aperçu de page. (hérité de [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | Le tableau des numéros de page pour générer les aperçus. (hérité de [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | Le format de l’image d’aperçu. (hérité de [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | Le délégué de fin d’aperçu de page. (hérité de [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | La largeur de l’aperçu de page. (hérité de [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |

### Champs
| Champ | Description |
| :- | :- |
| [DEFAULT_RESOLUTION](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/default_resolution/) | Résolution par défaut en points par pouce. |

### Voir aussi
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
