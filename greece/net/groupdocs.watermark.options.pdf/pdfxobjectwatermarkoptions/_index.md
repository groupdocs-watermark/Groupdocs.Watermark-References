---
title: PdfXObjectWatermarkOptions
second_title: GroupDocs.Watermark για Αναφορά API .NET
description: Αντιπροσωπεύει επιλογές προσθήκης υδατογραφήματος κατά την προσθήκη υδατογραφήματος XObject σε έγγραφο pdf.
type: docs
weight: 1920
url: /el/net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/
---
## PdfXObjectWatermarkOptions class

Αντιπροσωπεύει επιλογές προσθήκης υδατογραφήματος κατά την προσθήκη υδατογραφήματος XObject σε έγγραφο pdf.

```csharp
public sealed class PdfXObjectWatermarkOptions : PdfWatermarkOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [PdfXObjectWatermarkOptions](pdfxobjectwatermarkoptions)() | Αρχικοποιεί μια νέα παρουσία του[`PdfXObjectWatermarkOptions`](../pdfxobjectwatermarkoptions) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/pageindex) { get; set; } | Λαμβάνει ή ορίζει το ευρετήριο σελίδας για προσθήκη υδατογραφήματος. |

### Παρατηρήσεις

**Μάθε περισσότερα:**

* [Προσθήκη υδατογραφημάτων σε έγγραφα PDF](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Παραδείγματα

Προσθέστε ένα υδατογράφημα σε μια συγκεκριμένη σελίδα ενός εγγράφου pdf.

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

### Δείτε επίσης

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* χώρος ονομάτων [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* συνέλευση [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->