---
title: "PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn ein Anmerkungs‑Wasserzeichen zu einem PDF‑Dokument hinzugefügt wird."
type: docs
weight: 1930
url: /de/net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
---
## PdfAnnotationWatermarkOptions class

Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn ein Anmerkungs‑Wasserzeichen zu einem PDF‑Dokument hinzugefügt wird.

```csharp
public sealed class PdfAnnotationWatermarkOptions : PdfWatermarkOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfAnnotationWatermarkOptions](pdfannotationwatermarkoptions)() | Initialisiert eine neue Instanz der [`PdfAnnotationWatermarkOptions`](../pdfannotationwatermarkoptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/pageindex) { get; set; } | Liest oder setzt den Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll. |
| [PrintOnly](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/printonly) { get; set; } | Liest oder setzt den Wert, der angibt, ob die Anmerkung gedruckt, aber nicht in einer PDF‑Ansichts‑Anwendung angezeigt wird. |

### Hinweise

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Beispiele

Fügt ein Bild‑Anmerkungs‑Wasserzeichen zu einem PDF-Dokument hinzu.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
        options.PageIndex = -1; // default - all pages

        watermarker.Add(watermark, options);
    }

    watermarker.Save();
}
```

### Siehe auch

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
