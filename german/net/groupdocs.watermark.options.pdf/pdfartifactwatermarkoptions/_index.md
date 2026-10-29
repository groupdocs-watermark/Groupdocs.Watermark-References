---
title: "PdfArtifactWatermarkOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn ein Artefakt‑Wasserzeichen zu einem PDF‑Dokument hinzugefügt wird."
type: docs
weight: 1940
url: /de/net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
---
## PdfArtifactWatermarkOptions class

Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn ein Artefakt‑Wasserzeichen zu einem PDF‑Dokument hinzugefügt wird.

```csharp
public sealed class PdfArtifactWatermarkOptions : PdfWatermarkOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfArtifactWatermarkOptions](pdfartifactwatermarkoptions)() | Initialisiert eine neue Instanz der [`PdfArtifactWatermarkOptions`](../pdfartifactwatermarkoptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/pageindex) { get; set; } | Liest oder setzt den Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll. |

### Hinweise

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Beispiele

Fügt ein Bild‑Artefakt‑Wasserzeichen zu einem PDF-Dokument hinzu.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        watermark.HorizontalAlignment = HorizontalAlignment.Right;
        watermark.VerticalAlignment = VerticalAlignment.Bottom;

        PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
        options.PageIndex = -1; // default - all pages

        watermarker.Add(watermark, options);
        watermarker.Save();
    }
}
```

### Siehe auch

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
