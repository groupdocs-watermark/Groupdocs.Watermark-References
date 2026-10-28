---
title: "Watermarker"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά μια κλάση για τη διαχείριση υδατογραφήματος σε ένα έγγραφο."
type: docs
weight: 14
url: /el/java/com.groupdocs.watermark/watermarker/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Watermarker implements Closeable
```

Αναπαριστά μια κλάση για τη διαχείριση υδατογραφήματος σε ένα έγγραφο.

Το παρακάτω παράδειγμα δείχνει πώς να φορτώσετε και να αποθηκεύσετε το περιεχόμενο σε οποιαδήποτε υποστηριζόμενη μορφή.
>
> ````
> ```
>
>    // Load a content from a file.
>    Watermarker watermarker = new Watermarker("D:\\input.pdf");
>
>    // Use methods of Watermarker class to add, search or remove watermarks.
>
>    // Save changes.
>    watermarker.save("D:\\output.pdf");
>
>    // Free resources.
>    watermarker.close();
>  
> ```
> ````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [Watermarker(String filePath)](#Watermarker-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[Watermarker](../../com.groupdocs.watermark/watermarker)` με το καθορισμένο μονοπάτι εγγράφου. |
|
|  | [Watermarker(String filePath, LoadOptions options)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[Watermarker](../../com.groupdocs.watermark/watermarker)` με το καθορισμένο μονοπάτι εγγράφου και τις επιλογές φόρτωσης. |
|
|  | [Watermarker(String filePath, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[Watermarker](../../com.groupdocs.watermark/watermarker)` με το καθορισμένο μονοπάτι εγγράφου και τις ρυθμίσεις. |
|
|  | [Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[Watermarker](../../com.groupdocs.watermark/watermarker)` με το καθορισμένο μονοπάτι εγγράφου, τις επιλογές φόρτωσης και τις ρυθμίσεις. |
|
|  | [Watermarker(InputStream document)](#Watermarker-java.io.InputStream-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[Watermarker](../../com.groupdocs.watermark/watermarker)` με τη συγκεκριμένη ροή. |
|
|  | [Watermarker(InputStream document, LoadOptions options)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[Watermarker](../../com.groupdocs.watermark/watermarker)` με τη συγκεκριμένη ροή και τις επιλογές φόρτωσης. |
|
|  | [Watermarker(InputStream document, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[Watermarker](../../com.groupdocs.watermark/watermarker)` με τη συγκεκριμένη ροή και τις ρυθμίσεις. |
|
|  | [Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Αρχικοποιεί μια νέα παρουσία της κλάσης με τη συγκεκριμένη ροή, τις επιλογές φόρτωσης και τις ρυθμίσεις. |
|
| [Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | Αποκτά τα αντικείμενα περιεχομένου που θα συμπεριληφθούν σε αναζήτηση υδατογραφήματος. |
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Ορίζει τα αντικείμενα περιεχομένου που θα συμπεριληφθούν σε αναζήτηση υδατογραφήματος. |
|
| [dispose()](#dispose--) |  |
|  | [close()](#close--) | Αποδεσμεύει την τρέχουσα παρουσία. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Αποκτά τις πληροφορίες σχετικά με τη μορφή του φορτωμένου εγγράφου. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Προσθέτει ένα υδατογράφημα στο φορτωμένο έγγραφο. |
|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | Προσθέτει ένα υδατογράφημα στο φορτωμένο έγγραφο χρησιμοποιώντας τις επιλογές υδατογραφήματος. |
|
|  | [remove(PossibleWatermark possibleWatermark)](#remove-com.groupdocs.watermark.search.PossibleWatermark-) | Αφαιρεί το υδατογράφημα από το έγγραφο. |
|
|  | [remove(PossibleWatermarkCollection possibleWatermarks)](#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-) | Αφαιρεί όλα τα υδατογραφήματα στη συλλογή από το έγγραφο. |
|
|  | [save(String filePath)](#save-java.lang.String-) | Αποθηκεύει το έγγραφο στην καθορισμένη θέση αρχείου. |
|
|  | [save(OutputStream document)](#save-java.io.OutputStream-) | Αποθηκεύει το έγγραφο στην καθορισμένη ροή. |
|
|  | [save(String filePath, SaveOptions options)](#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | Αποθηκεύει το έγγραφο στην καθορισμένη θέση αρχείου χρησιμοποιώντας επιλογές αποθήκευσης. |
|
|  | [save(OutputStream document, SaveOptions options)](#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | Αποθηκεύει το έγγραφο στην καθορισμένη ροή χρησιμοποιώντας επιλογές αποθήκευσης. |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | Δημιουργεί εικόνες προεπισκόπησης για το έγγραφο. |
|
|  | [search()](#search--) | Αναζητά όλα τα πιθανά υδατογραφήματα στο έγγραφο. |
|
|  | [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | Αναζητά πιθανά υδατογραφήματα σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης. |
|
|  | [getImages(ImageSearchCriteria searchCriteria)](#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | Βρίσκει εικόνες σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης. |
|
|  | [getImages()](#getImages--) | Βρίσκει όλες τις εικόνες στο έγγραφο. |
|
|  | [<T>getContent(Class<T> contentType)](#-T-getContent-java.lang.Class-T--) | Επιστρέφει το αντικείμενο `[Content](../../com.groupdocs.watermark.contents/content)` για το φορτωμένο έγγραφο. |
|
### Watermarker(String filePath) {#Watermarker-java.lang.String-}
```
public Watermarker(String filePath)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[Watermarker](../../com.groupdocs.watermark/watermarker)` με το καθορισμένο μονοπάτι εγγράφου.

Μάθετε περισσότερα για τη φόρτωση εγγράφων:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Το παρακάτω παράδειγμα δείχνει πώς να φορτώσετε και να αποθηκεύσετε το περιεχόμενο σε οποιαδήποτε υποστηριζόμενη μορφή.
>
> ````
> ```
>
>    // Load a content from a file.
>    Watermarker watermarker = new Watermarker("D:\\input.pdf");
>
>    // Use methods of Watermarker class to add, search or remove watermarks.
>
>    // Save changes.
>    watermarker.save("D:\\output.pdf");
>
>    // Free resources.
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή αρχείου από την οποία θα φορτωθεί το έγγραφο. |
|

### Watermarker(String filePath, LoadOptions options) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(String filePath, LoadOptions options)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[Watermarker](../../com.groupdocs.watermark/watermarker)` με το καθορισμένο μονοπάτι εγγράφου και τις επιλογές φόρτωσης.

Μάθετε περισσότερα για τη φόρτωση εγγράφων:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Το παρακάτω παράδειγμα δείχνει πώς να φορτώσετε κρυπτογραφημένο PDF έγγραφο χρησιμοποιώντας κωδικό πρόσβασης.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    loadOptions.setPassword("123");
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.pdf", loadOptions);
>    // ...
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή αρχείου για τη φόρτωση του εγγράφου. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση ενός εγγράφου. |
|

### Watermarker(String filePath, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, WatermarkerSettings settings)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[Watermarker](../../com.groupdocs.watermark/watermarker)` με το καθορισμένο μονοπάτι εγγράφου και τις ρυθμίσεις.

Μάθετε περισσότερα για τη φόρτωση εγγράφων:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε αναζητήσιμα αντικείμενα παγκοσμίως (για όλα τα έγγραφα που
θα φορτωθούν μετά από αυτό).
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setWordProcessingSearchableObjects(WordProcessingSearchableObjects.Hyperlinks
>                                                                     | WordProcessingSearchableObjects.Text);
>    settings.getSearchableObjects().setSpreadsheetSearchableObjects(SpreadsheetSearchableObjects.HeadersFooters);
>    settings.getSearchableObjects().setPresentationSearchableObjects(PresentationSearchableObjects.SlidesBackgrounds
>                                                                   | PresentationSearchableObjects.Shapes);
>    settings.getSearchableObjects().setDiagramSearchableObjects(DiagramSearchableObjects.None);
>    settings.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.All);
>
>    for (final File fileEntry : new File("D:\\files").listFiles())
>    {
>       if (fileEntry.isFile()) {
>           Watermarker watermarker = new Watermarker(fileEntry.getPath(), settings);
>           PossibleWatermarkCollection watermarks = watermarker.search();
>           // The code for working with found watermarks goes here.
>           watermarker.close();
>       }
>    }
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή αρχείου για τη φόρτωση του εγγράφου. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Πρόσθετες ρυθμίσεις για χρήση κατά την εργασία με το φορτωμένο έγγραφο. |
|

### Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[Watermarker](../../com.groupdocs.watermark/watermarker)` με το καθορισμένο μονοπάτι εγγράφου, τις επιλογές φόρτωσης και τις ρυθμίσεις.

Μάθετε περισσότερα για τη φόρτωση εγγράφων:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Το παρακάτω παράδειγμα δείχνει πώς να βρείτε συγκεκριμένα τμήματα κειμένου στο σώμα/θέμα του μηνύματος ηλεκτρονικού ταχυδρομείου.
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setEmailSearchableObjects(EmailSearchableObjects.Subject
>                                                            | EmailSearchableObjects.HtmlBody
>                                                            | EmailSearchableObjects.PlainTextBody);
>    EmailLoadOptions loadOptions = new EmailLoadOptions(); 
>    Watermarker watermarker = new Watermarker("D:\\test.msg", loadOptions, settings);
>    SearchCriteria criteria = new TextSearchCriteria("test", false);
>    // Note, search is performed only if you pass TextSearchCriteria instance to search() method
>    PossibleWatermarkCollection watermarks = watermarker.search(criteria);
>    // Remove found text fragments
>    watermarks.clear();
>    // Save changes
>    watermarker.save("D:\\modified_test.msg");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή αρχείου για τη φόρτωση του εγγράφου. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση ενός εγγράφου. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Πρόσθετες ρυθμίσεις για χρήση κατά την εργασία με το φορτωμένο έγγραφο. |
|

### Watermarker(InputStream document) {#Watermarker-java.io.InputStream-}
```
public Watermarker(InputStream document)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[Watermarker](../../com.groupdocs.watermark/watermarker)` με τη συγκεκριμένη ροή.

Μάθετε περισσότερα για τη φόρτωση εγγράφων:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Το παρακάτω παράδειγμα δείχνει πώς να φορτώσετε και να αποθηκεύσετε ένα έγγραφο σε οποιαδήποτε υποστηριζόμενη μορφή.
>
> ````
> ```
>
>    // Load a content from a stream.
>    FileInputStream inputStream = new FileInputStream("D:\\input.pdf");
>    FileOutputStream outputStream = new FileOutputStream("D:\\output.pdf");
>    Watermarker watermarker = new Watermarker(inputStream);
>    // Use methods of Watermarker class to add, search or remove watermarks.
>
>    // Save changes.
>    watermarker.save(outputStream);
>    watermarker.close();
>    outputStream.close();
>    inputStream.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.InputStream | Η ροή για τη φόρτωση του εγγράφου. |
|

### Watermarker(InputStream document, LoadOptions options) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(InputStream document, LoadOptions options)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[Watermarker](../../com.groupdocs.watermark/watermarker)` με τη συγκεκριμένη ροή και τις επιλογές φόρτωσης.

Μάθετε περισσότερα για τη φόρτωση εγγράφων:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Το παρακάτω παράδειγμα δείχνει πώς να φορτώσετε κρυπτογραφημένο έγγραφο PDF χρησιμοποιώντας κωδικό πρόσβασης
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    loadOptions.setPassword("123");
>    FileInputStream inputStream = new FileInputStream("D:\\input.pdf");
>    Watermarker watermarker = new Watermarker(inputStream, loadOptions);
>    // ...
>
>    watermarker.close();
>    inputStream.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.InputStream | Η ροή για τη φόρτωση του εγγράφου. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση ενός εγγράφου. |
|

### Watermarker(InputStream document, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, WatermarkerSettings settings)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[Watermarker](../../com.groupdocs.watermark/watermarker)` με τη συγκεκριμένη ροή και τις ρυθμίσεις.

Μάθετε περισσότερα για τη φόρτωση εγγράφων:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε αναζητήσιμα αντικείμενα παγκοσμίως (για όλα τα έγγραφα που
θα φορτωθούν μετά από αυτό).
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setWordProcessingSearchableObjects(WordProcessingSearchableObjects.Hyperlinks
>                                                                     | WordProcessingSearchableObjects.Text);
>    settings.getSearchableObjects().setSpreadsheetSearchableObjects(SpreadsheetSearchableObjects.HeadersFooters);
>    settings.getSearchableObjects().setPresentationSearchableObjects(PresentationSearchableObjects.SlidesBackgrounds
>                                                                   | PresentationSearchableObjects.Shapes);
>    settings.getSearchableObjects().setDiagramSearchableObjects(DiagramSearchableObjects.None);
>    settings.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.All);
>
>    for (final File fileEntry : new File("D:\\files").listFiles())
>    {
>       if (fileEntry.isFile()) {
>           FileInputStream inputStream = new FileInputStream(fileEntry.getPath());
>           Watermarker watermarker = new Watermarker(inputStream, settings);
>           PossibleWatermarkCollection watermarks = watermarker.Search();
>           // The code for working with found watermarks goes here.
>           watermarker.close();
>           inputStream.close();
>       }
>    }
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.InputStream | Η ροή για τη φόρτωση του εγγράφου. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Πρόσθετες ρυθμίσεις για χρήση κατά την εργασία με το φορτωμένο έγγραφο. |
|

### Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης με τη συγκεκριμένη ροή, τις επιλογές φόρτωσης και τις ρυθμίσεις.

Μάθετε περισσότερα για τη φόρτωση εγγράφων:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε αναζητήσιμα αντικείμενα παγκοσμίως (για όλα τα έγγραφα που
θα φορτωθούν μετά από αυτό).
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setEmailSearchableObjects(EmailSearchableObjects.Subject
>                                                            | EmailSearchableObjects.HtmlBody
>                                                            | EmailSearchableObjects.PlainTextBody);
>    FileInputStream inputStream = new FileInputStream("D:\\test.msg");
>    FileOutputStream outputStream = new FileOutputStream("D:\\modified_test.msg");
>    EmailLoadOptions loadOptions = new EmailLoadOptions(); 
>    Watermarker watermarker = new Watermarker(inputStream, loadOptions, settings);
>    SearchCriteria criteria = new TextSearchCriteria("test", false);
>    // Note, search is performed only if you pass TextSearchCriteria instance to search() method
>    PossibleWatermarkCollection watermarks = watermarker.search(criteria);
>    // Remove found text fragments
>    watermarks.clear();
>    // Save changes
>    watermarker.save(outputStream);
>    watermarker.close();
>    outputStream.close();
>    inputStream.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.InputStream | Η ροή για τη φόρτωση του εγγράφου. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση ενός εγγράφου. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Πρόσθετες ρυθμίσεις για χρήση κατά την εργασία με το φορτωμένο έγγραφο. |
|

### Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | com.aspose.ms.System.IO.Stream |  |
| options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) |  |
| settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Αποκτά τα αντικείμενα περιεχομένου που θα συμπεριληφθούν σε αναζήτηση υδατογραφήματος.

Αυτή η μέθοδος επίσης καθορίζει αντικείμενα περιεχομένου που χρησιμοποιούνται στην αναζήτηση εικόνων.
Για περισσότερες πληροφορίες δείτε `#search(SearchCriteria).search(SearchCriteria)`
και τις μεθόδους `#getImages().getImages()`.

Μάθετε περισσότερα για την αναζήτηση υδατογραφιών:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Το παρακάτω παράδειγμα δείχνει πώς να αφαιρέσετε όλα τα XObjects και τα Artifacts από ένα έγγραφο PDF.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.pdf");
>    watermarker.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.XObjects
>                                                             | PdfSearchableObjects.Artifacts);
>    PossibleWatermarkCollection watermarks = watermarker.search();
>    // Remove all found objects.
>    watermarks.clear();
>    // Save changes.
>    watermarker.save("D:\\modified_test.pdf");
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The objects that are to be included in a watermark search.

### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


Ορίζει τα αντικείμενα περιεχομένου που θα συμπεριληφθούν σε αναζήτηση υδατογραφήματος.

Αυτή η μέθοδος επίσης καθορίζει αντικείμενα περιεχομένου που χρησιμοποιούνται στην αναζήτηση εικόνων.
Για περισσότερες πληροφορίες δείτε `#search(SearchCriteria).search(SearchCriteria)`
και τις μεθόδους `#getImages().getImages()`.
Μάθετε περισσότερα για την αναζήτηση υδατογραφιών:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Το παρακάτω παράδειγμα δείχνει πώς να αφαιρέσετε όλα τα XObjects και τα Artifacts από ένα έγγραφο PDF.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.pdf");
>    watermarker.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.XObjects
>                                                             | PdfSearchableObjects.Artifacts);
>    PossibleWatermarkCollection watermarks = watermarker.search();
>    // Remove all found objects.
>    watermarks.clear();
>    // Save changes.
>    watermarker.save("D:\\modified_test.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | Τα αντικείμενα που πρέπει να συμπεριληφθούν στην αναζήτηση υδατογραφιών. |
|

### dispose() {#dispose--}
```
public final void dispose()
```




### close() {#close--}
```
public final void close()
```


Αποδεσμεύει την τρέχουσα παρουσία.


### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Αποκτά τις πληροφορίες σχετικά με τη μορφή του φορτωμένου εγγράφου.

Μάθετε περισσότερα για την λήψη πληροφοριών του εγγράφου
[Get document info](../https://docs.groupdocs.com/display/watermarkjava/Get+document+info).

Το παρακάτω παράδειγμα δείχνει πώς να λάβετε πληροφορίες για ένα έγγραφο οποιουδήποτε υποστηριζόμενου τύπου.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.ppt");
>    IDocumentInfo info = watermarker.getDocumentInfo();
>    System.out.println("File type: " + info.getFileType());
>    System.out.println("Number of pages: " + info.getPageCount());
>    System.out.println("Document size: " + info.getSize() + " bytes");
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.

### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


Προσθέτει ένα υδατογράφημα στο φορτωμένο έγγραφο.

Μάθετε περισσότερα για την προσθήκη υδατογραφιών:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε υδατογράφημα εικόνας και κειμένου σε ένα έγγραφο οποιουδήποτε υποστηριζόμενου τύπου.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.pdf");
>
>    TextWatermark textWatermark = new TextWatermark("DRAFT", new Font("Arial", 19));
>    textWatermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    textWatermark.setVerticalAlignment(VerticalAlignment.Top);
>    textWatermark.setConsiderParentMargins(true);
>    textWatermark.setForegroundColor(Color.getRed());
>    textWatermark.setBackground(true);
>    textWatermark.setOpacity(0.5);
>    watermarker.add(textWatermark);
>  
>    ImageWatermark imageWatermark = new ImageWatermark("D:\\draft.png"));
>    imageWatermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    imageWatermark.setVerticalAlignment(VerticalAlignment.Bottom);
>    imageWatermark.setConsiderParentMargins(true);
>    imageWatermark.setBackground(true);
>    imageWatermark.setOpacity(0.5);
>    watermarker.add(imageWatermark);
>    imageWatermark.close();
>
>    watermarker.save("D:\\output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Το υδατογράφημα που θα προστεθεί στο έγγραφο. |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public final void add(Watermark watermark, WatermarkOptions options)
```


Προσθέτει ένα υδατογράφημα στο φορτωμένο έγγραφο χρησιμοποιώντας τις επιλογές υδατογραφήματος.

Μάθετε περισσότερα για την προσθήκη υδατογραφιών:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε υδατογράφημα εικόνας σε συγκεκριμένη σελίδα ενός εγγράφου PDF.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\input.pdf", loadOptions);
>
>    ImageWatermark imageWatermark = new ImageWatermark("D:\\draft.png"));
>    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
>    options.setPageIndex(0);
>    watermarker.add(imageWatermark, options);
>    imageWatermark.close();
>
>    watermarker.save("D:\\output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Το υδατογράφημα που θα προστεθεί στο έγγραφο. |
|
|  | options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) | Πρόσθετες επιλογές για χρήση κατά την προσθήκη του υδατογραφήματος. |
|

### remove(PossibleWatermark possibleWatermark) {#remove-com.groupdocs.watermark.search.PossibleWatermark-}
```
public final void remove(PossibleWatermark possibleWatermark)
```


Αφαιρεί το υδατογράφημα από το έγγραφο.

Μάθετε περισσότερα για την αφαίρεση υδατογραφιών:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

Το παρακάτω παράδειγμα δείχνει πώς να βρείτε και να αφαιρέσετε το πρώτο δυνατό υδατογράφημα που περιέχει συγκεκριμένο
κείμενο ή εικόνα από ένα έγγραφο οποιουδήποτε υποστηριζόμενου τύπου.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.doc");
>    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria("D:\\logo.png");
>    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(Pattern.compile("^Company\\sName$"));
>    PossibleWatermarkCollection watermarks = watermarker.search(textSearchCriteria.or(imageSearchCriteria));
>    if (watermarks.getCount() > 0)
>    {
>        watermarker.remove(watermarks.get_Item(0));
>    }
>
>    watermarker.save("D:\\output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | possibleWatermark | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) | Το υδατογράφημα που θα αφαιρεθεί. |
|

### remove(PossibleWatermarkCollection possibleWatermarks) {#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void remove(PossibleWatermarkCollection possibleWatermarks)
```


Αφαιρεί όλα τα υδατογραφήματα στη συλλογή από το έγγραφο.

Μάθετε περισσότερα για την αφαίρεση υδατογραφιών:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

Το παρακάτω παράδειγμα δείχνει πώς να βρείτε και να αφαιρέσετε όλα τα πιθανά υδατογραφίες που περιέχουν συγκεκριμένο
κείμενο ή εικόνα από ένα έγγραφο οποιουδήποτε υποστηριζόμενου τύπου.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.doc");
>    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria("D:\\logo.png");
>    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(Pattern.compile("^Company\\sName$"));
>    PossibleWatermarkCollection watermarks = watermarker.search(textSearchCriteria.or(imageSearchCriteria));
>    watermarker.remove(watermarks);
>    watermarker.save("D:\\output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | possibleWatermarks | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) | Η συλλογή των υδατογραφιών που θα αφαιρεθούν. |
|

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Αποθηκεύει το έγγραφο στην καθορισμένη θέση αρχείου.

Μάθετε περισσότερα για την αποθήκευση των εγγράφων
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το υδατογράφημα και να αποθηκεύσετε το έγγραφο σε άλλο αρχείο.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    watermarker.save("output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή αρχείου για αποθήκευση των δεδομένων του εγγράφου. |
|

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


Αποθηκεύει το έγγραφο στην καθορισμένη ροή.

Μάθετε περισσότερα για την αποθήκευση των εγγράφων
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε υδατογράφημα και να αποθηκεύσετε το έγγραφο στη μνήμη ροής.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    ByteArrayOutputStream outputStream = new ByteArrayOutputStream();
>    watermarker.save(outputStream);
>    // ...
>    outputStream.close();
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.OutputStream | Η ροή για αποθήκευση των δεδομένων του εγγράφου. |
|

### save(String filePath, SaveOptions options) {#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(String filePath, SaveOptions options)
```


Αποθηκεύει το έγγραφο στην καθορισμένη θέση αρχείου χρησιμοποιώντας επιλογές αποθήκευσης.

Μάθετε περισσότερα για την αποθήκευση των εγγράφων
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το υδατογράφημα και να αποθηκεύσετε το έγγραφο σε άλλο αρχείο
με προεπιλογή `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    watermarker.save("output.pdf", new SaveOptions());
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή αρχείου για αποθήκευση των δεδομένων του εγγράφου. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Πρόσθετες επιλογές για χρήση κατά την αποθήκευση ενός εγγράφου. |
|

### save(OutputStream document, SaveOptions options) {#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(OutputStream document, SaveOptions options)
```


Αποθηκεύει το έγγραφο στην καθορισμένη ροή χρησιμοποιώντας επιλογές αποθήκευσης.

Μάθετε περισσότερα για την αποθήκευση των εγγράφων
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε υδατογράφημα και να αποθηκεύσετε το έγγραφο στη μνήμη ροής
με προεπιλογή `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    ByteArrayOutputStream outputStream = new ByteArrayOutputStream();
>    watermarker.save(outputStream, new SaveOptions());
>    // ...
>    outputStream.close();
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.OutputStream | Η ροή για αποθήκευση των δεδομένων του εγγράφου. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Πρόσθετες επιλογές για χρήση κατά την αποθήκευση ενός εγγράφου. |
|

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Δημιουργεί εικόνες προεπισκόπησης για το έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) | Πρόσθετες επιλογές για χρήση κατά τη δημιουργία προεπισκοπών εικόνων. |
|

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


Αναζητά όλα τα πιθανά υδατογραφήματα στο έγγραφο.

Η αναζήτηση πραγματοποιείται σε αντικείμενα που καθορίζονται με `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Μάθετε περισσότερα για την αναζήτηση υδατογραφημάτων
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Το παρακάτω παράδειγμα δείχνει πώς να μετρήσετε τα πιθανά υδατογραφήματα σε ένα έγγραφο οποιουδήποτε υποστηριζόμενου τύπου.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    PossibleWatermarkCollection watermarks = watermarker.search();
>    System.out.println(watermarks.getCount());
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### search(SearchCriteria searchCriteria) {#search-com.groupdocs.watermark.search.SearchCriteria-}
```
public final PossibleWatermarkCollection search(SearchCriteria searchCriteria)
```


Αναζητά πιθανά υδατογραφήματα σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης.

Η αναζήτηση πραγματοποιείται σε αντικείμενα που καθορίζονται με `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Μάθετε περισσότερα για την αναζήτηση υδατογραφημάτων
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Το παρακάτω παράδειγμα δείχνει πώς να βρείτε και να αφαιρέσετε όλα τα πιθανά υδατογραφήματα που περιέχουν συγκεκριμένο κείμενο
ή εικόνα από ένα έγγραφο οποιουδήποτε υποστηριζόμενου τύπου.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria("logo.png");
>    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(Pattern.compile("^Company\\sName$"));
>    PossibleWatermarkCollection watermarks = watermarker.search(textSearchCriteria.or(imageSearchCriteria));
>    watermarks.clear();
>    watermarker.save("output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Τα κριτήρια αναζήτησης για χρήση. |
|

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### getImages(ImageSearchCriteria searchCriteria) {#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-}
```
public final WatermarkableImageCollection getImages(ImageSearchCriteria searchCriteria)
```


Βρίσκει εικόνες σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης.

Η αναζήτηση πραγματοποιείται σε αντικείμενα που καθορίζονται με `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Μάθετε περισσότερα για την αναζήτηση υδατογραφημάτων
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Το παρακάτω παράδειγμα δείχνει πώς να αφαιρέσετε όλες τις εικόνες που είναι παρόμοιες με την αναφορά
από ένα έγγραφο οποιουδήποτε υποστηριζόμενου τύπου.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    ImageThumbnailSearchCriteria criteria = new ImageThumbnailSearchCriteria("reference.png");
>    WatermarkableImageCollection images = watermarker.getImages(criteria);
>    images.clear();
>    watermarker.save("output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | Τα κριτήρια αναζήτησης για χρήση. |
|

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection)
### getImages() {#getImages--}
```
public final WatermarkableImageCollection getImages()
```


Βρίσκει όλες τις εικόνες στο έγγραφο.

Η αναζήτηση πραγματοποιείται σε αντικείμενα που καθορίζονται με `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Μάθετε περισσότερα για την αναζήτηση υδατογραφημάτων
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε υδατογράφημα σε όλες τις εικόνες σε ένα έγγραφο οποιουδήποτε υποστηριζόμενου τύπου.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    // Initialize text or image watermark.
>    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));
>
>    // Find all images in the document.
>    WatermarkableImageCollection images = watermarker.getImages();
>
>    // Add watermark.
>    for (WatermarkableImage watermarkableImage : images)
>    {
>        watermarkableImage.addWatermark(watermark);
>    }
>
>    // Save changes.
>    watermarker.save("output.doc");
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection) - The collection of found images.

### <T>getContent(Class<T> contentType) {#-T-getContent-java.lang.Class-T--}
```
public final T <T>getContent(Class<T> contentType)
```


Επιστρέφει το αντικείμενο `[Content](../../com.groupdocs.watermark.contents/content)` για το φορτωμένο έγγραφο.

Το παρακάτω παράδειγμα δείχνει πώς να ραστεροποιήσετε τη σελίδα εγγράφου pdf με προστιθέμενο υδατογράφημα.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("input.pdf", loadOptions);
>    ImageWatermark watermark = new ImageWatermark("watermark.png")
>    watermarker.add(watermark);
>    PdfContent content = watermarker.getContent(PdfContent.class);
>    content.rasterize(300, 300, PdfImageConversionFormat.Png);
>    watermarker.save("output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentType | java.lang.Class<T> | Ο ζητούμενος τύπος ενός αντικειμένου `[Content](../../com.groupdocs.watermark.contents/content)`. |
|

**Returns:**
T - Το αντικείμενο `[Content](../../com.groupdocs.watermark.contents/content)` για το φορτωμένο έγγραφο.

