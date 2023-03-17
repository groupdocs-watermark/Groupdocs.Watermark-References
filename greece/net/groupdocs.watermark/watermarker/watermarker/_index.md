---
title: Watermarker
second_title: GroupDocs.Watermark για Αναφορά API .NET
description: Αρχικοποιεί μια νέα παρουσία τουWatermarkergroupdocs.watermark/watermarker κλάση με την καθορισμένη διαδρομή εγγράφου.
type: docs
weight: 10
url: /el/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Αρχικοποιεί μια νέα παρουσία του[`Watermarker`](../../watermarker) κλάση με την καθορισμένη διαδρομή εγγράφου.

```csharp
public Watermarker(string filePath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου από την οποία θα φορτωθεί το έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Ο παρεχόμενος κωδικός πρόσβασης είναι εσφαλμένος. |

### Παρατηρήσεις

Μάθετε περισσότερα σχετικά με τη φόρτωση εγγράφων: [Φόρτωση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Παραδείγματα

Φόρτωση και αποθήκευση περιεχομένου οποιασδήποτε υποστηριζόμενης μορφής.

```csharp
// Φόρτωση περιεχομένου από αρχείο.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Χρησιμοποιήστε μεθόδους της κλάσης Watermarker για προσθήκη, αναζήτηση ή αφαίρεση υδατογραφημάτων.

    // Αποθηκεύστε το έγγραφο.
    watermarker.Save("D:\\output.pdf");
}
```

### Δείτε επίσης

* class [Watermarker](../../watermarker)
* χώρος ονομάτων [GroupDocs.Watermark](../../watermarker)
* συνέλευση [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Αρχικοποιεί μια νέα παρουσία του[`Watermarker`](../../watermarker)κλάση με την specified διαδρομή εγγράφου και επιλογές φόρτωσης.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου για τη φόρτωση του εγγράφου. |
| options | LoadOptions | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση ενός εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Ο παρεχόμενος κωδικός πρόσβασης είναι εσφαλμένος. |

### Παρατηρήσεις

Μάθετε περισσότερα σχετικά με τη φόρτωση εγγράφων: [Φόρτωση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Παραδείγματα

Φόρτωση κρυπτογραφημένου εγγράφου PDF με χρήση κωδικού πρόσβασης.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    //...
}
```

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* χώρος ονομάτων [GroupDocs.Watermark](../../watermarker)
* συνέλευση [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Αρχικοποιεί μια νέα παρουσία του[`Watermarker`](../../watermarker) κλάση με τη διαδρομή και τις ρυθμίσεις εγγράφου specified .

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου για τη φόρτωση του εγγράφου. |
| settings | WatermarkerSettings | Πρόσθετες ρυθμίσεις για χρήση κατά την εργασία με φορτωμένο έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Ο παρεχόμενος κωδικός πρόσβασης είναι εσφαλμένος. |

### Παρατηρήσεις

Μάθετε περισσότερα σχετικά με τη φόρτωση εγγράφων: [Φόρτωση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Παραδείγματα

Ορισμός αντικειμένων με δυνατότητα αναζήτησης καθολικά (για όλα τα έγγραφα που θα φορτωθούν μετά).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (Watermarker watermarker = new Watermarker(file, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // Ο κώδικας για την εργασία με υδατογραφήματα που βρέθηκαν βρίσκεται εδώ.
    }
}
```

### Δείτε επίσης

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* χώρος ονομάτων [GroupDocs.Watermark](../../watermarker)
* συνέλευση [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Αρχικοποιεί μια νέα παρουσία του[`Watermarker`](../../watermarker) κλάση με τη διαδρομή εγγράφου specified , επιλογές φόρτωσης και ρυθμίσεις.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου για τη φόρτωση του εγγράφου. |
| options | LoadOptions | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση ενός εγγράφου. |
| settings | WatermarkerSettings | Πρόσθετες ρυθμίσεις για χρήση κατά την εργασία με φορτωμένο έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Ο παρεχόμενος κωδικός πρόσβασης είναι εσφαλμένος. |

### Παρατηρήσεις

Μάθετε περισσότερα σχετικά με τη φόρτωση εγγράφων: [Φόρτωση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Παραδείγματα

Βρείτε συγκεκριμένα τμήματα κειμένου στο σώμα/θέμα του μηνύματος email.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.msg", loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Σημείωση, η αναζήτηση εκτελείται μόνο εάν περάσετε την παρουσία TextSearchCriteria στη μέθοδο αναζήτησης
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Αφαίρεση τεμαχίων κειμένου που βρέθηκαν
    watermarks.Clear();
    // Αποθήκευσε τις αλλαγές
    watermarker.Save();
}
```

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* χώρος ονομάτων [GroupDocs.Watermark](../../watermarker)
* συνέλευση [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Αρχικοποιεί μια νέα παρουσία του[`Watermarker`](../../watermarker) τάξη με την καθορισμένη ροή.

```csharp
public Watermarker(Stream document)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Η ροή από την οποία θα φορτωθεί το έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Ο παρεχόμενος κωδικός πρόσβασης είναι εσφαλμένος. |

### Παρατηρήσεις

Μάθετε περισσότερα σχετικά με τη φόρτωση εγγράφων [Φόρτωση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Παραδείγματα

Φορτώστε και αποθηκεύστε ένα έγγραφο οποιασδήποτε υποστηριζόμενης μορφής.

```csharp
// Φόρτωση περιεχομένου από ροή.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Χρησιμοποιήστε μεθόδους της κλάσης Watermarker για προσθήκη, αναζήτηση ή αφαίρεση υδατογραφημάτων.

    // Αποθήκευσε τις αλλαγές.
    watermarker.Save(outputStream);
}
```

### Δείτε επίσης

* class [Watermarker](../../watermarker)
* χώρος ονομάτων [GroupDocs.Watermark](../../watermarker)
* συνέλευση [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία του[`Watermarker`](../../watermarker) κλάση με τις καθορισμένες επιλογές ροής και φόρτωσης.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Η ροή από την οποία θα φορτωθεί το έγγραφο. |
| options | LoadOptions | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση ενός εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Ο παρεχόμενος κωδικός πρόσβασης είναι εσφαλμένος. |

### Παρατηρήσεις

Μάθετε περισσότερα σχετικά με τη φόρτωση εγγράφων [Φόρτωση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Παραδείγματα

Φόρτωση κρυπτογραφημένου εγγράφου PDF χρησιμοποιώντας κωδικό πρόσβασης

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    //...
}
```

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* χώρος ονομάτων [GroupDocs.Watermark](../../watermarker)
* συνέλευση [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Αρχικοποιεί μια νέα παρουσία του[`Watermarker`](../../watermarker) τάξη με την καθορισμένη ροή και τις ρυθμίσεις.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Η ροή από την οποία θα φορτωθεί το έγγραφο. |
| settings | WatermarkerSettings | Πρόσθετες ρυθμίσεις για χρήση κατά την εργασία με φορτωμένο έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Ο παρεχόμενος κωδικός πρόσβασης είναι εσφαλμένος. |

### Παρατηρήσεις

Μάθετε περισσότερα σχετικά με τη φόρτωση εγγράφων [Φόρτωση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Παραδείγματα

Ορισμός αντικειμένων με δυνατότητα αναζήτησης καθολικά (για όλα τα έγγραφα που θα φορτωθούν μετά).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (FileStream fileStream = File.Open(file, FileMode.Open))
    using (Watermarker watermarker = new Watermarker(fileStream, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // Ο κώδικας για την εργασία με υδατογραφήματα που βρέθηκαν βρίσκεται εδώ.
    }
}
```

### Δείτε επίσης

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* χώρος ονομάτων [GroupDocs.Watermark](../../watermarker)
* συνέλευση [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Αρχικοποιεί μια νέα παρουσία του[`Watermarker`](../../watermarker) τάξη με την καθορισμένη ροή, επιλογές και ρυθμίσεις φόρτωσης.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Η ροή από την οποία θα φορτωθεί το έγγραφο. |
| options | LoadOptions | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση ενός εγγράφου. |
| settings | WatermarkerSettings | Πρόσθετες ρυθμίσεις για χρήση κατά την εργασία με φορτωμένο έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Ο παρεχόμενος κωδικός πρόσβασης είναι εσφαλμένος. |

### Παρατηρήσεις

Μάθετε περισσότερα σχετικά με τη φόρτωση εγγράφων [Φόρτωση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Παραδείγματα

Βρείτε συγκεκριμένα τμήματα κειμένου στο σώμα/θέμα του μηνύματος email.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (FileStream fileStream = File.Open(@"D:\test.msg", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Σημείωση, η αναζήτηση εκτελείται μόνο εάν περάσετε την παρουσία TextSearchCriteria στη μέθοδο αναζήτησης
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Αφαίρεση τεμαχίων κειμένου που βρέθηκαν
    watermarks.Clear();
    // Αποθήκευσε τις αλλαγές
    watermarker.Save();
}
```

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* χώρος ονομάτων [GroupDocs.Watermark](../../watermarker)
* συνέλευση [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
