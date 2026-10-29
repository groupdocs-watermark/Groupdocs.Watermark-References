---
title: "PdfContent"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt ein pdf-Dokument dar, in dem ein Wasserzeichen platziert werden kann."
type: docs
weight: 660
url: /de/net/groupdocs.watermark.contents.pdf/pdfcontent/
---
## PdfContent class

Stellt ein pdf-Dokument dar, in dem ein Wasserzeichen platziert werden kann.

```csharp
public class PdfContent : Content
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.pdf/pdfcontent/attachments) { get; } | Ermittelt die Sammlung aller Anhänge dieses [`PdfContent`](../pdfcontent). |
| [PageMarginType](../../groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype) { get; set; } | Liest oder setzt die PDF-Seitenränder, die beim Hinzufügen von Wasserzeichen verwendet werden. |
| [Pages](../../groupdocs.watermark.contents.pdf/pdfcontent/pages) { get; } | Ermittelt die Sammlung aller Seiten dieses [`PdfContent`](../pdfcontent). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/decrypt)() | Entschlüsselt den Inhalt. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Gibt die aktuelle Instanz frei. |
| [Encrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/encrypt#encrypt)(string) | Verschlüsselt das Dokument mit demselben Passwort wie Benutzer- und Eigentümerpasswort. |
| [Encrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/encrypt#encrypt_1)(string, string, PdfPermissions, PdfCryptoAlgorithm) | Verschlüsselt den Inhalt. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Findet alle Bilder im Inhalt. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Findet Bilder gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [Rasterize](../../groupdocs.watermark.contents.pdf/pdfcontent/rasterize)(int, int, PdfImageConversionFormat) | Konvertiert alle Inhaltsseiten in Bilder. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Findet alle möglichen Wasserzeichen im Inhalt. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Findet mögliche Wasserzeichen gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |

### Hinweise

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)
* [Existing objects in PDF document](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+PDF+document)
* [Rasterize document or page](https://docs.groupdocs.com/display/watermarknet/Rasterize+document+or+page)
* [Watermarks in PDF document](https://docs.groupdocs.com/display/watermarknet/Watermarks+in+PDF+document)

### Siehe auch

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
