---
title: "Watermarker"
second_title: "GroupDocs.Watermark για .NET API Αναφορά"
description: "Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Watermarkergroupdocs.watermark/watermarker με τη συγκεκριμένη διαδρομή αρχείου."
type: docs
weight: 10
url: /el/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`Watermarker`](../../watermarker) με τη συγκεκριμένη διαδρομή αρχείου.

```csharp
public Watermarker(string filePath)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου από την οποία θα φορτωθεί το έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Ο παρεχόμενος κωδικός πρόσβασης είναι λανθασμένος. |

### Σχόλια

Μάθετε περισσότερα για τη φόρτωση εγγράφων: [Φόρτωση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Παραδείγματα

Φορτώνει και αποθηκεύει περιεχόμενο σε οποιαδήποτε υποστηριζόμενη μορφή.

```csharp
// Φορτώνει περιεχόμενο από ένα αρχείο.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Χρησιμοποιήστε τις μεθόδους της κλάσης Watermarker για να προσθέσετε, αναζητήσετε ή αφαιρέσετε υδατογραφήματα.

    // Αποθηκεύστε το έγγραφο.
    watermarker.Save("D:\\output.pdf");
}
```

### Δείτε επίσης

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`Watermarker`](../../watermarker) με τη συγκεκριμένη διαδρομή αρχείου και επιλογές φόρτωσης.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου από την οποία θα φορτωθεί το έγγραφο. |
| επιλογές | LoadOptions | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση ενός εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Ο παρεχόμενος κωδικός πρόσβασης είναι λανθασμένος. |

### Σχόλια

Μάθετε περισσότερα για τη φόρτωση εγγράφων: [Φόρτωση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Παραδείγματα

Φορτώστε κρυπτογραφημένο έγγραφο PDF χρησιμοποιώντας κωδικό πρόσβασης.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`Watermarker`](../../watermarker) με τη συγκεκριμένη διαδρομή αρχείου και ρυθμίσεις.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου από την οποία θα φορτωθεί το έγγραφο. |
| ρυθμίσεις | WatermarkerSettings | Πρόσθετες ρυθμίσεις για χρήση κατά την εργασία με το φορτωμένο έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Ο παρεχόμενος κωδικός πρόσβασης είναι λανθασμένος. |

### Σχόλια

Μάθετε περισσότερα για τη φόρτωση εγγράφων: [Φόρτωση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Παραδείγματα

Ορίστε τα αναζητήσιμα αντικείμενα παγκοσμίως (για όλα τα έγγραφα που θα φορτωθούν μετά από αυτό).

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

        // Ο κώδικας για εργασία με τα βρεθέντα υδατογραφήματα τοποθετείται εδώ.
    }
}
```

### Δείτε επίσης

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`Watermarker`](../../watermarker) με τη συγκεκριμένη διαδρομή αρχείου, επιλογές φόρτωσης και ρυθμίσεις.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου από την οποία θα φορτωθεί το έγγραφο. |
| επιλογές | LoadOptions | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση ενός εγγράφου. |
| ρυθμίσεις | WatermarkerSettings | Πρόσθετες ρυθμίσεις για χρήση κατά την εργασία με το φορτωμένο έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Ο παρεχόμενος κωδικός πρόσβασης είναι λανθασμένος. |

### Σχόλια

Μάθετε περισσότερα για τη φόρτωση εγγράφων: [Φόρτωση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

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
    // Σημείωση, η αναζήτηση εκτελείται μόνο εάν περάσετε ένα αντικείμενο TextSearchCriteria στη μέθοδο Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Αφαιρέστε τα ευρεθέντα αποσπάσματα κειμένου
    watermarks.Clear();
    // Αποθηκεύστε τις αλλαγές
    watermarker.Save();
}
```

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`Watermarker`](../../watermarker) με τη συγκεκριμένη ροή.

```csharp
public Watermarker(Stream document)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| έγγραφο | Stream | Η ροή από την οποία θα φορτωθεί το έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Ο παρεχόμενος κωδικός πρόσβασης είναι λανθασμένος. |

### Σχόλια

Μάθετε περισσότερα για τη φόρτωση εγγράφων [Φόρτωση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Παραδείγματα

Φορτώστε και αποθηκεύστε ένα έγγραφο σε οποιαδήποτε υποστηριζόμενη μορφή.

```csharp
// Φορτώστε περιεχόμενο από μια ροή.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Χρησιμοποιήστε τις μεθόδους της κλάσης Watermarker για να προσθέσετε, αναζητήσετε ή αφαιρέσετε υδατογραφήματα.

    // Αποθηκεύστε τις αλλαγές.
    watermarker.Save(outputStream);
}
```

### Δείτε επίσης

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`Watermarker`](../../watermarker) με τη συγκεκριμένη ροή και τις επιλογές φόρτωσης.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| έγγραφο | Stream | Η ροή από την οποία θα φορτωθεί το έγγραφο. |
| επιλογές | LoadOptions | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση ενός εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Ο παρεχόμενος κωδικός πρόσβασης είναι λανθασμένος. |

### Σχόλια

Μάθετε περισσότερα για τη φόρτωση εγγράφων [Φόρτωση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Παραδείγματα

Φορτώστε κρυπτογραφημένο PDF έγγραφο χρησιμοποιώντας κωδικό πρόσβασης

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`Watermarker`](../../watermarker) με τη συγκεκριμένη ροή και τις ρυθμίσεις.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| έγγραφο | Stream | Η ροή από την οποία θα φορτωθεί το έγγραφο. |
| ρυθμίσεις | WatermarkerSettings | Πρόσθετες ρυθμίσεις για χρήση κατά την εργασία με το φορτωμένο έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Ο παρεχόμενος κωδικός πρόσβασης είναι λανθασμένος. |

### Σχόλια

Μάθετε περισσότερα για τη φόρτωση εγγράφων [Φόρτωση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Παραδείγματα

Ορίστε τα αναζητήσιμα αντικείμενα παγκοσμίως (για όλα τα έγγραφα που θα φορτωθούν μετά από αυτό).

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

        // Ο κώδικας για εργασία με τα βρεθέντα υδατογραφήματα τοποθετείται εδώ.
    }
}
```

### Δείτε επίσης

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`Watermarker`](../../watermarker) με τη συγκεκριμένη ροή, τις επιλογές φόρτωσης και τις ρυθμίσεις.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| έγγραφο | Stream | Η ροή από την οποία θα φορτωθεί το έγγραφο. |
| επιλογές | LoadOptions | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση ενός εγγράφου. |
| ρυθμίσεις | WatermarkerSettings | Πρόσθετες ρυθμίσεις για χρήση κατά την εργασία με το φορτωμένο έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Ο παρεχόμενος κωδικός πρόσβασης είναι λανθασμένος. |

### Σχόλια

Μάθετε περισσότερα για τη φόρτωση εγγράφων [Φόρτωση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

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
    // Σημείωση, η αναζήτηση εκτελείται μόνο εάν περάσετε ένα αντικείμενο TextSearchCriteria στη μέθοδο Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Αφαιρέστε τα ευρεθέντα αποσπάσματα κειμένου
    watermarks.Clear();
    // Αποθηκεύστε τις αλλαγές
    watermarker.Save();
}
```

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
