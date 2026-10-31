---
title: "SpreadsheetPreviewOptions Klasse"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt Optionen bereit, um Anforderungen und Stream‑Delegaten für die Vorschauerstellung eines Spreadsheet‑Dokuments festzulegen."
type: docs
url: /de/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/
is_root: false
weight: 50
---


## SpreadsheetPreviewOptions class

Stellt Optionen bereit, um Anforderungen und Stream‑Delegaten für die Vorschauerstellung eines Spreadsheet‑Dokuments festzulegen.

Der Typ SpreadsheetPreviewOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/__init__/#create_page_stream) | Initialisiert eine neue Instanz der SpreadsheetPreviewOptions Klasse, wodurch der Ausgabestream geschlossen wird. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/__init__/#create_page_stream-release_page_stream) | Initialisiert eine neue Instanz der SpreadsheetPreviewOptions Klasse, wodurch der Ausgabestream dem Client zur weiteren Verwendung zurückgegeben wird. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [only_data_area](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/only_data_area/) | Das Flag zum Rendern des Datenbereichs ausschließlich ohne Kopfzeilen, Fußzeilen und Ränder. |
| [resolution](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/resolution/) | Die Auflösung für die erzeugten Bilder, in Punkten pro Zoll. |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | Der Delegat zur Erstellung des Seitenstreams, der verwendet wird, um für jede gerenderte Seite einen beschreibbaren Stream zu erhalten. (geerbt von [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | Die Höhe der Seitenvorschau. (geerbt von [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | Das Array von Seitenzahlen, für die Vorschauen erzeugt werden sollen. (geerbt von [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | Das Bildformat der Vorschau. (geerbt von [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | Der Delegat für den Abschluss der Seitenvorschau. (geerbt von [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | Die Breite der Seitenvorschau. (geerbt von [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |

### Felder
| Feld | Beschreibung |
| :- | :- |
| [DEFAULT_RESOLUTION](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/default_resolution/) | Standardauflösung in Punkten pro Zoll. |

### Siehe auch
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
