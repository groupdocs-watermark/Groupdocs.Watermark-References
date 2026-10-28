---
title: "PdfPermissions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά τα δικαιώματα των χρηστών για ένα έγγραφο pdf."
type: docs
weight: 68
url: /el/java/com.groupdocs.watermark.contents/pdfpermissions/
---
**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Αναπαριστά τα δικαιώματα του χρήστη για ένα pdf έγγραφο.

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [PrintDocument](#PrintDocument) | Εκτύπωση του περιεχομένου. |
|
|  | [ModifyContent](#ModifyContent) | Τροποποίηση του περιεχομένου. |
|
|  | [ExtractContent](#ExtractContent) | Αντιγραφή ή άλλης μορφής εξαγωγή κειμένου και γραφικών από το έγγραφο. |
|
|  | [ModifyTextAnnotations](#ModifyTextAnnotations) | Προσθήκη ή τροποποίηση σχολίων κειμένου. |
|
|  | [FillForm](#FillForm) | Συμπλήρωση των υπαρχόντων διαδραστικών πεδίων φόρμας. |
|
|  | [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | Εξαγωγή κειμένου και γραφικών. |
|
|  | [AssembleDocument](#AssembleDocument) | Συναρμολόγηση του περιεχομένου. |
|
|  | [PrintingQuality](#PrintingQuality) | Εκτύπωση του περιεχομένου σε μια αναπαράσταση από την οποία μπορεί να δημιουργηθεί μια πιστή ψηφιακή αντίγραφο του εγγράφου PDF. |
|
### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


Εκτύπωση του περιεχομένου.

Διαχειριστές ασφαλείας της έκδοσης 2: Εκτύπωση του περιεχομένου.

Διαχειριστές ασφαλείας της έκδοσης 3 ή υψηλότερης: Εκτύπωση του περιεχομένου
(πιθανώς όχι στο υψηλότερο επίπεδο ποιότητας, ανάλογα με το αν
`#PrintingQuality.PrintingQuality` είναι επίσης ορισμένο).


### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


Τροποποίηση του περιεχομένου.

Τροποποίηση του περιεχομένου του εγγράφου μέσω άλλων λειτουργιών
από αυτές που ελέγχονται από `#ModifyTextAnnotations.ModifyTextAnnotations`, `#FillForm.FillForm`.


### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```


Αντιγραφή ή άλλης μορφής εξαγωγή κειμένου και γραφικών από το έγγραφο.

Διαχειριστές ασφαλείας της έκδοσης 2: Αντιγραφή ή άλλης μορφής εξαγωγή κειμένου και γραφικών από το περιεχόμενο,
συμπεριλαμβανομένης της εξαγωγής κειμένου και γραφικών (υποστηρίζοντας την προσβασιμότητα για χρήστες με
αναπηρίες ή για άλλους σκοπούς).

Διαχειριστές ασφαλείας της έκδοσης 3 ή υψηλότερης: Αντιγραφή ή άλλης μορφής εξαγωγή κειμένου και γραφικών από
το περιεχόμενο μέσω λειτουργιών διαφορετικών από αυτές που ελέγχονται από
`#ExtractContentWithDisabilities.ExtractContentWithDisabilities`.


### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```


Προσθήκη ή τροποποίηση σχολίων κειμένου.

Προσθήκη ή τροποποίηση σχολίων κειμένου, συμπλήρωση διαδραστικών πεδίων φόρμας,
και, εάν το `#ModifyContent.ModifyContent` είναι επίσης ορισμένο,
δημιουργήστε ή τροποποιήστε διαδραστικά πεδία φόρμας (συμπεριλαμβανομένων των πεδίων υπογραφής).


### FillForm {#FillForm}
```
public static final int FillForm
```


Συμπλήρωση των υπαρχόντων διαδραστικών πεδίων φόρμας.

Διαχειριστές ασφαλείας έκδοσης 3 ή μεγαλύτερης: Συμπληρώστε υπάρχοντα διαδραστικά πεδία φόρμας
(συμπεριλαμβανομένων των πεδίων υπογραφής), ακόμη και αν το `#ModifyTextAnnotations.ModifyTextAnnotations` είναι καθαρό.


### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```


Εξαγωγή κειμένου και γραφικών.

Διαχειριστές ασφαλείας έκδοσης 3 ή μεγαλύτερης: Εξαγωγή κειμένου και γραφικών
(υπέρ της προσβασιμότητας για χρήστες με αναπηρίες ή για άλλους σκοπούς).


### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


Συναρμολόγηση του περιεχομένου.

Διαχειριστές ασφαλείας έκδοσης 3 ή μεγαλύτερης: Συναρμολόγηση του περιεχομένου (εισαγωγή, περιστροφή ή διαγραφή σελίδων
και δημιουργία σελιδοδεικτών ή μικρογραφιών), ακόμη και αν το `#ModifyContent.ModifyContent` είναι καθαρό.


### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```


Εκτύπωση του περιεχομένου σε μια αναπαράσταση από την οποία μπορεί να δημιουργηθεί μια πιστή ψηφιακή αντίγραφο του εγγράφου PDF.

Διαχειριστές ασφαλείας έκδοσης 3 ή μεγαλύτερης: Εκτύπωση του περιεχομένου σε μια αναπαράσταση από την οποία μπορεί να δημιουργηθεί μια πιστή
ψηφιακό αντίγραφο του εγγράφου PDF. Όταν αυτό το bit είναι καθαρό (και το `#PrintDocument.PrintDocument`
είναι ορισμένο), η εκτύπωση περιορίζεται σε μια χαμηλού επιπέδου αναπαράσταση της εμφάνισης, πιθανώς με μειωμένη ποιότητα.


