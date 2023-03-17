---
title: Watermarker
second_title: GroupDocs.Watermark για Αναφορά API .NET
description: Αντιπροσωπεύει μια κλάση για διαχείριση υδατογραφήματος σε ένα έγγραφο.
type: docs
weight: 3060
url: /el/net/groupdocs.watermark/watermarker/
---
## Watermarker class

Αντιπροσωπεύει μια κλάση για διαχείριση υδατογραφήματος σε ένα έγγραφο.

```csharp
public class Watermarker : IDisposable
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | Αρχικοποιεί μια νέα παρουσία του[`Watermarker`](../watermarker) τάξη με την καθορισμένη ροή. |
| [Watermarker](watermarker#constructor_4)(string) | Αρχικοποιεί μια νέα παρουσία του[`Watermarker`](../watermarker) κλάση με την καθορισμένη διαδρομή εγγράφου. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | Αρχικοποιεί μια νέα παρουσία του[`Watermarker`](../watermarker) κλάση με τις καθορισμένες επιλογές ροής και φόρτωσης. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | Αρχικοποιεί μια νέα παρουσία του[`Watermarker`](../watermarker) τάξη με την καθορισμένη ροή και τις ρυθμίσεις. |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | Αρχικοποιεί μια νέα παρουσία του[`Watermarker`](../watermarker)κλάση με την specified διαδρομή εγγράφου και επιλογές φόρτωσης. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | Αρχικοποιεί μια νέα παρουσία του[`Watermarker`](../watermarker) κλάση με τη διαδρομή και τις ρυθμίσεις εγγράφου specified . |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | Αρχικοποιεί μια νέα παρουσία του[`Watermarker`](../watermarker) τάξη με την καθορισμένη ροή, επιλογές και ρυθμίσεις φόρτωσης. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | Αρχικοποιεί μια νέα παρουσία του[`Watermarker`](../watermarker) κλάση με τη διαδρομή εγγράφου specified , επιλογές φόρτωσης και ρυθμίσεις. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | Λαμβάνει ή ορίζει τα αντικείμενα περιεχομένου που πρόκειται να συμπεριληφθούν σε μια αναζήτηση υδατογραφήματος. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | Προσθέτει ένα υδατογράφημα στο φορτωμένο έγγραφο. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | Προσθέτει ένα υδατογράφημα στο φορτωμένο έγγραφο χρησιμοποιώντας επιλογές υδατογραφήματος. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | Διαθέτει την τρέχουσα παρουσία. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | Δημιουργεί εικόνες προεπισκόπησης για το έγγραφο. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | Επιστρέφει το[`Content`](../../groupdocs.watermark.contents/content) αντικείμενο για το φορτωμένο έγγραφο. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | Λαμβάνει τις πληροφορίες σχετικά με τη μορφή του εγγράφου που έχει φορτωθεί. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | Βρίσκει όλες τις εικόνες στο έγγραφο. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | Βρίσκει εικόνες σύμφωνα με καθορισμένα κριτήρια αναζήτησης. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | Αφαιρεί το υδατογράφημα από το έγγραφο. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | Αφαιρεί όλα τα υδατογραφήματα της συλλογής από το έγγραφο. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | Αποθηκεύει τα δεδομένα του εγγράφου στην υποκείμενη ροή. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | Αποθηκεύει τα δεδομένα του εγγράφου στην υποκείμενη ροή χρησιμοποιώντας τις επιλογές αποθήκευσης. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | Αποθηκεύει το έγγραφο στην καθορισμένη ροή. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | Αποθηκεύει το έγγραφο στην καθορισμένη θέση αρχείου. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | Αποθηκεύει το έγγραφο στην καθορισμένη ροή χρησιμοποιώντας τις επιλογές αποθήκευσης. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | Αποθηκεύει το έγγραφο στην καθορισμένη θέση αρχείου χρησιμοποιώντας τις επιλογές αποθήκευσης. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | Αναζητά όλα τα πιθανά υδατογραφήματα στο έγγραφο. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | Αναζητά πιθανά υδατογραφήματα σύμφωνα με καθορισμένα κριτήρια αναζήτησης. |

### Παραδείγματα

Φόρτωση και αποθήκευση περιεχομένου οποιασδήποτε υποστηριζόμενης μορφής.

```csharp
// Φόρτωση περιεχομένου από αρχείο.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Χρησιμοποιήστε μεθόδους της κλάσης Watermarker για προσθήκη, αναζήτηση ή αφαίρεση υδατογραφημάτων.

    // Αποθήκευσε τις αλλαγές.
    watermarker.Save("D:\\output.pdf");
}
```

### Δείτε επίσης

* χώρος ονομάτων [GroupDocs.Watermark](../../groupdocs.watermark)
* συνέλευση [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
