---
title: "Watermarker"
second_title: "GroupDocs.Watermark για .NET API Αναφορά"
description: "Αντιπροσωπεύει μια κλάση για τη διαχείριση υδατογραφήματος σε ένα έγγραφο."
type: docs
weight: 3140
url: /el/net/groupdocs.watermark/watermarker/
---
## Watermarker class

Αντιπροσωπεύει μια κλάση για τη διαχείριση υδατογραφήματος σε ένα έγγραφο.

```csharp
public class Watermarker : IDisposable
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`Watermarker`](../watermarker) με το καθορισμένο stream. |
| [Watermarker](watermarker#constructor_4)(string) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`Watermarker`](../watermarker) με το καθορισμένο μονοπάτι εγγράφου. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`Watermarker`](../watermarker) με το καθορισμένο stream και τις επιλογές φόρτωσης. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`Watermarker`](../watermarker) με το καθορισμένο stream και τις ρυθμίσεις. |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`Watermarker`](../watermarker) με το καθορισμένο μονοπάτι εγγράφου και τις επιλογές φόρτωσης. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`Watermarker`](../watermarker) με το καθορισμένο μονοπάτι εγγράφου και τις ρυθμίσεις. |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`Watermarker`](../watermarker) με το καθορισμένο stream, τις επιλογές φόρτωσης και τις ρυθμίσεις. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`Watermarker`](../watermarker) με το καθορισμένο μονοπάτι εγγράφου, τις επιλογές φόρτωσης και τις ρυθμίσεις. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | Λαμβάνει ή ορίζει τα αντικείμενα περιεχομένου που θα συμπεριληφθούν σε αναζήτηση υδατογραφήματος. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | Προσθέτει ένα υδατογράφημα στο φορτωμένο έγγραφο. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | Προσθέτει ένα υδατογράφημα στο φορτωμένο έγγραφο χρησιμοποιώντας επιλογές υδατογραφήματος. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | Αποδεσμεύει το τρέχον στιγμιότυπο. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | Δημιουργεί εικόνες προεπισκόπησης για το έγγραφο. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | Επιστρέφει το αντικείμενο [`Content`](../../groupdocs.watermark.contents/content) για το φορτωμένο έγγραφο. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | Λαμβάνει τις πληροφορίες σχετικά με τη μορφή του φορτωμένου εγγράφου. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | Βρίσκει όλες τις εικόνες στο έγγραφο. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | Βρίσκει εικόνες σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | Αφαιρεί το υδατογράφημα από το έγγραφο. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | Αφαιρεί όλα τα υδατογραφήματα στη συλλογή από το έγγραφο. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | Αποθηκεύει τα δεδομένα του εγγράφου στο υποκείμενο stream. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | Αποθηκεύει τα δεδομένα του εγγράφου στο υποκείμενο stream χρησιμοποιώντας επιλογές αποθήκευσης. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | Αποθηκεύει το έγγραφο στο καθορισμένο stream. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | Αποθηκεύει το έγγραφο στην καθορισμένη θέση αρχείου. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | Αποθηκεύει το έγγραφο στο καθορισμένο stream χρησιμοποιώντας επιλογές αποθήκευσης. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | Αποθηκεύει το έγγραφο στην καθορισμένη θέση αρχείου χρησιμοποιώντας επιλογές αποθήκευσης. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | Αναζητά όλα τα πιθανά υδατογραφήματα στο έγγραφο. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | Αναζητά πιθανά υδατογραφήματα σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης. |

### Παραδείγματα

Φορτώνει και αποθηκεύει περιεχόμενο σε οποιαδήποτε υποστηριζόμενη μορφή.

```csharp
// Φορτώνει περιεχόμενο από ένα αρχείο.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Χρησιμοποιήστε τις μεθόδους της κλάσης Watermarker για να προσθέσετε, αναζητήσετε ή αφαιρέσετε υδατογραφήματα.

    // Αποθηκεύστε τις αλλαγές.
    watermarker.Save("D:\\output.pdf");
}
```

### Δείτε επίσης

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
