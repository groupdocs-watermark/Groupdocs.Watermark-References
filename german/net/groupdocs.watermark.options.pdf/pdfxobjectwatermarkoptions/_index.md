---
title: "PdfXObjectWatermarkOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn ein XObject‑Wasserzeichen zu einem PDF‑Dokument hinzugefügt wird."
type: docs
weight: 1990
url: /de/net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/
---
## PdfXObjectWatermarkOptions class

Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn ein XObject‑Wasserzeichen zu einem PDF‑Dokument hinzugefügt wird.

```csharp
public sealed class PdfXObjectWatermarkOptions : PdfWatermarkOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfXObjectWatermarkOptions](pdfxobjectwatermarkoptions)() | Initialisiert eine neue Instanz der [`PdfXObjectWatermarkOptions`](../pdfxobjectwatermarkoptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/pageindex) { get; set; } | Liest oder setzt den Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll. |

### Hinweise

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Beispiele

Fügt ein Wasserzeichen zu einer bestimmten Seite eines PDF-Dokuments hinzu.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\doc.pdf", loadOptions))
using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
{
    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Siehe auch

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
