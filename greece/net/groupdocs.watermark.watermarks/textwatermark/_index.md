---
title: TextWatermark
second_title: GroupDocs.Watermark για Αναφορά API .NET
description: Αντιπροσωπεύει ένα υδατογράφημα κειμένου.
type: docs
weight: 3160
url: /el/net/groupdocs.watermark.watermarks/textwatermark/
---
## TextWatermark class

Αντιπροσωπεύει ένα υδατογράφημα κειμένου.

```csharp
public class TextWatermark : Watermark
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [TextWatermark](textwatermark)(string, Font) | Αρχικοποιεί μια νέα παρουσία του[`TextWatermark`](../textwatermark)τάξη με καθορισμένο κείμενο και γραμματοσειρά. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [BackgroundColor](../../groupdocs.watermark.watermarks/textwatermark/backgroundcolor) { get; set; } | Λαμβάνει ή ορίζει το χρώμα φόντου του κειμένου. |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το μέγεθος και οι συντεταγμένες του υδατογραφήματος υπολογίζονται λαμβάνοντας υπόψη τα γονικά περιθώρια. |
| [Font](../../groupdocs.watermark.watermarks/textwatermark/font) { get; set; } | Λαμβάνει ή ορίζει τη γραμματοσειρά του κειμένου. |
| [ForegroundColor](../../groupdocs.watermark.watermarks/textwatermark/foregroundcolor) { get; set; } | Παίρνει ή ορίζει το χρώμα προσκηνίου του κειμένου. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Λαμβάνει ή ορίζει το επιθυμητό ύψος αυτού[`Watermark`](../../groupdocs.watermark/watermark) . |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Λαμβάνει ή ορίζει την οριζόντια στοίχιση αυτού[`Watermark`](../../groupdocs.watermark/watermark) . |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το υδατογράφημα πρέπει να τοποθετηθεί στο φόντο. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Λαμβάνει ή ορίζει τις ρυθμίσεις περιθωρίου αυτού[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Λαμβάνει ή ορίζει την αδιαφάνεια αυτού[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Padding](../../groupdocs.watermark.watermarks/textwatermark/padding) { get; set; } | Λαμβάνει ή ορίζει τις ρυθμίσεις συμπλήρωσης αυτού[`TextWatermark`](../textwatermark) . Αυτή η ιδιότητα ισχύει μόνο για αρχεία εικόνας. |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Λαμβάνει ή ορίζει τη γωνία περιστροφής αυτού[`Watermark`](../../groupdocs.watermark/watermark) σε μοίρες. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που καθορίζει πώς το μέγεθος του υδατογραφήματος εξαρτάται από το γονικό μέγεθος. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που καθορίζει τον τρόπο με τον οποίο θα πρέπει να έχει το μέγεθος του υδατογραφήματος. |
| [Text](../../groupdocs.watermark.watermarks/textwatermark/text) { get; set; } | Λαμβάνει ή ορίζει το κείμενο που θα χρησιμοποιηθεί ως υδατογράφημα. |
| [TextAlignment](../../groupdocs.watermark.watermarks/textwatermark/textalignment) { get; set; } | Λαμβάνει ή ορίζει τη στοίχιση κειμένου του υδατογραφήματος. |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Λαμβάνει ή ορίζει την κατακόρυφη στοίχιση αυτού[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Λαμβάνει ή ορίζει το επιθυμητό πλάτος αυτού[`Watermark`](../../groupdocs.watermark/watermark) . |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη x αυτού[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη y αυτού[`Watermark`](../../groupdocs.watermark/watermark) . |

### Παρατηρήσεις

**Μάθε περισσότερα:**

* [Προσθήκη υδατογραφημάτων κειμένου](https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks)

### Παραδείγματα

Κλιμακώστε το υδατογράφημα κειμένου ανάλογα με το γονικό μέγεθος.

```csharp
foreach (string file in Directory.GetFiles("C:\\test"))
{
    using (Watermarker watermarker = new Watermarker(file))
    {
        TextWatermark watermark = new TextWatermark("test watermark", new Font("Arial", 36));
        watermark.HorizontalAlignment = HorizontalAlignment.Center;
        watermark.VerticalAlignment = VerticalAlignment.Center;
        watermark.SizingType = SizingType.ScaleToParentDimensions;
        watermark.RotateAngle = 45;
        watermark.ScaleFactor = 0.4;

        watermarker.Add(watermark);
        watermarker.Save();
    }
}
```

### Δείτε επίσης

* class [Watermark](../../groupdocs.watermark/watermark)
* χώρος ονομάτων [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* συνέλευση [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
