---
title: "FileType"
second_title: "GroupDocs.Watermark για .NET API Αναφορά"
description: "Αναπαριστά τον τύπο αρχείου."
type: docs
weight: 40
url: /el/net/groupdocs.watermark.common/filetype/
---
## FileType class

Αναπαριστά τον τύπο αρχείου.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | Λαμβάνει το επίθημα του ονόματος αρχείου (συμπεριλαμβανομένου του σημείου ".") π.χ., ".doc". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | Λαμβάνει το όνομα τύπου αρχείου π.χ., "Microsoft Word Document". |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | Λαμβάνει την οικογένεια μορφής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | Αντιστοιχίζει την επέκταση αρχείου με τον τύπο αρχείου. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | Καθορίζει εάν το τρέχον [`FileType`](../filetype) είναι το ίδιο με το καθορισμένο αντικείμενο [`FileType`](../filetype). |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | Καθορίζει εάν ο τρέχων [`FileType`](../filetype) είναι ίδιος με το καθορισμένο αντικείμενο. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | Επιστρέφει έναν κώδικα κατακερματισμού για το τρέχον αντικείμενο [`FileType`](../filetype). |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | Ανακτά τους υποστηριζόμενους τύπους αρχείων. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | Καθορίζει εάν δύο αντικείμενα [`FileType`](../filetype) είναι ίδια. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | Καθορίζει εάν δύο αντικείμενα [`FileType`](../filetype) δεν είναι ίδια. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | Τα αρχεία με επέκταση .BMP αντιπροσωπεύουν αρχεία Bitmap Image που χρησιμοποιούνται για την αποθήκευση ψηφιακών bitmap εικόνων. Αυτές οι εικόνες είναι ανεξάρτητες από την κάρτα γραφικών και επίσης ονομάζονται μορφή αρχείου device independent bitmap (DIB). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here](https://wiki.fileformat.com/image/bmp/). |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | Τα αρχεία με επέκταση .doc αντιπροσωπεύουν έγγραφα που δημιουργούνται από το Microsoft Word ή άλλα προγράμματα επεξεργασίας κειμένου σε δυαδική μορφή αρχείου. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here](https://wiki.fileformat.com/word-processing/doc/). |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | Τα αρχεία DOCM είναι έγγραφα που δημιουργούνται από το Microsoft Word 2007 ή νεότερο, με δυνατότητα εκτέλεσης μακροεντολών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here](https://wiki.fileformat.com/word-processing/docm/). |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | Το DOCX είναι μια γνωστή μορφή για έγγραφα Microsoft Word. Εισήχθη το 2007 με την κυκλοφορία του Microsoft Office 2007, η δομή αυτής της νέας μορφής εγγράφου άλλαξε από απλό δυαδικό σε συνδυασμό XML και δυαδικών αρχείων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here](https://wiki.fileformat.com/word-processing/docx/). |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | Τα αρχεία με επέκταση .DOT είναι πρότυπα αρχεία που δημιουργήθηκαν από το Microsoft Word για να έχουν προρυθμισμένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOC ή DOCX. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here](https://wiki.fileformat.com/word-processing/dot/). |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | Ένα αρχείο με επέκταση DOTM αντιπροσωπεύει πρότυπο αρχείο που δημιουργήθηκε με το Microsoft Word 2007 ή νεότερο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here](https://wiki.fileformat.com/word-processing/dotm/). |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | Τα αρχεία με επέκταση DOTX είναι πρότυπα αρχεία που δημιουργήθηκαν από το Microsoft Word για να έχουν προρυθμισμένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOCX. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here](https://wiki.fileformat.com/word-processing/dotx/). |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | Η μορφή αρχείου EML αντιπροσωπεύει μηνύματα ηλεκτρονικού ταχυδρομείου που αποθηκεύονται με χρήση του Outlook και άλλων σχετικών εφαρμογών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here](https://wiki.fileformat.com/email/eml/). |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | Η μορφή αρχείου EMLX υλοποιείται και αναπτύσσεται από την Apple. Η εφαρμογή Apple Mail χρησιμοποιεί τη μορφή αρχείου EMLX για την εξαγωγή των email. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here](https://wiki.fileformat.com/email/emlx/). |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Το Office Open XML WordprocessingML αποθηκεύεται σε ένα επίπεδο αρχείο XML αντί για πακέτο ZIP (.xml). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Το Office Open XML WordprocessingML Macro-Enabled Document αποθηκεύεται σε ένα επίπεδο αρχείο XML αντί για πακέτο ZIP (.xml). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Το Office Open XML WordprocessingML Template (χωρίς μακροεντολές) αποθηκεύεται σε ένα επίπεδο αρχείο XML αντί για πακέτο ZIP (.xml). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Το Office Open XML WordprocessingML Macro-Enabled Template αποθηκεύεται σε ένα επίπεδο αρχείο XML αντί για πακέτο ZIP (.xml). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | Το GIF ή Graphical Interchange Format είναι ένας τύπος εξαιρετικά συμπιεσμένης εικόνας. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here](https://wiki.fileformat.com/image/gif/). |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | Το JPEG είναι ένας τύπος μορφής εικόνας που αποθηκεύεται με τη μέθοδο της απώλειας συμπίεσης. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | Το JPEG 2000 (JPF) είναι ένα σύστημα κωδικοποίησης εικόνας και ένα σύγχρονο πρότυπο συμπίεσης εικόνας. Σχεδιασμένο με τη χρήση τεχνολογίας κυματικού, το JPEG 2000 μπορεί να κωδικοποιήσει περιεχόμενο χωρίς απώλειες σε οποιαδήποτε ποιότητα ταυτόχρονα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | Το JPEG είναι ένας τύπος μορφής εικόνας που αποθηκεύεται με τη μέθοδο της απώλειας συμπίεσης. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | Το JPEG 2000 (JPM) είναι ένα σύστημα κωδικοποίησης εικόνας και ένα σύγχρονο πρότυπο συμπίεσης εικόνας. Σχεδιασμένο, χρησιμοποιώντας τεχνολογία κυματικού, το JPEG 2000 μπορεί να κωδικοποιήσει περιεχόμενο χωρίς απώλειες σε οποιαδήποτε ποιότητα αμέσως. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | Το JPEG 2000 (JPX) είναι ένα σύστημα κωδικοποίησης εικόνας και ένα σύγχρονο πρότυπο συμπίεσης εικόνας. Σχεδιασμένο, χρησιμοποιώντας τεχνολογία κυματικού, το JPEG 2000 μπορεί να κωδικοποιήσει περιεχόμενο χωρίς απώλειες σε οποιαδήποτε ποιότητα αμέσως. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/jp2/). |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | Το MSG είναι μια μορφή αρχείου που χρησιμοποιείται από το Microsoft Outlook και το Exchange για την αποθήκευση μηνυμάτων ηλεκτρονικού ταχυδρομείου, επαφών, ραντεβού ή άλλων εργασιών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/email/msg/). |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | Τα αρχεία ODT είναι τύπος εγγράφων που δημιουργούνται με εφαρμογές επεξεργασίας κειμένου που βασίζονται στη μορφή αρχείου OpenDocument Text. Δημιουργούνται με εφαρμογές επεξεργασίας κειμένου όπως το δωρεάν OpenOffice Writer και μπορούν να περιέχουν περιεχόμενο όπως κείμενο, εικόνες, αντικείμενα και στυλ. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/odt/). |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | Τα αρχεία με επέκταση .OFT αντιπροσωπεύουν πρότυπα μηνυμάτων που δημιουργούνται χρησιμοποιώντας το Microsoft Outlook. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/email/oft/). |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Αρχείο Office Open XML (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Το Portable Document Format (PDF) είναι ένας τύπος εγγράφου που δημιουργήθηκε από την Adobe τη δεκαετία του 1990. Ο σκοπός αυτής της μορφής αρχείου ήταν η εισαγωγή ενός προτύπου για την αναπαράσταση εγγράφων και άλλου υλικού αναφοράς σε μορφή ανεξάρτητη από λογισμικό εφαρμογών, υλικό καθώς και λειτουργικό σύστημα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/view/pdf/). |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | Το PNG, Portable Network Graphics, αναφέρεται σε έναν τύπο αρχείου raster εικόνας που χρησιμοποιεί χωρίς απώλειες συμπίεση. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/png/). |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | Τα αρχεία με επέκταση POTM είναι πρότυπα αρχείων Microsoft PowerPoint με υποστήριξη μακροεντολών. Τα αρχεία POTM δημιουργούνται με το PowerPoint 2007 ή νεότερο και περιέχουν προεπιλεγμένες ρυθμίσεις που μπορούν να χρησιμοποιηθούν για τη δημιουργία περαιτέρω αρχείων παρουσίασης. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/potm/). |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | Τα αρχεία με επέκταση .POTX αντιπροσωπεύουν πρότυπες παρουσιάσεις Microsoft PowerPoint που δημιουργούνται με το Microsoft PowerPoint 2007 και νεότερο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/potx/). |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | Τα αρχεία PPS, PowerPoint Slide Show, δημιουργούνται χρησιμοποιώντας το Microsoft PowerPoint για σκοπό παρουσίασης διαφανειών. Η ανάγνωση και δημιουργία αρχείων PPS υποστηρίζεται από το Microsoft PowerPoint 97-2003. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/pps/). |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | Τα αρχεία με επέκταση PPSM αντιπροσωπεύουν μορφή αρχείου Slide Show με ενεργοποιημένες μακροεντολές, δημιουργημένη με το Microsoft PowerPoint 2007 ή νεότερο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/ppsm/). |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | Τα αρχεία PPSX, Power Point Slide Show, δημιουργούνται χρησιμοποιώντας το Microsoft PowerPoint 2007 και νεότερο για σκοπό παρουσίασης διαφανειών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/ppsx/). |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | Ένα αρχείο με επέκταση PPT αντιπροσωπεύει αρχείο PowerPoint που αποτελείται από μια συλλογή διαφανειών για προβολή ως SlideShow. Καθορίζει τη Δυαδική Μορφή Αρχείου που χρησιμοποιείται από το Microsoft PowerPoint 97-2003. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/ppt/). |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | Τα αρχεία με επέκταση PPTM είναι παρουσιάσεις με ενεργοποιημένες μακροεντολές που δημιουργούνται με το Microsoft PowerPoint 2007 ή νεότερες εκδόσεις. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/pptm/). |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | Τα αρχεία με επέκταση PPTX είναι αρχεία παρουσίασης που δημιουργούνται με τη δημοφιλής εφαρμογή Microsoft PowerPoint. Σε αντίθεση με την προηγούμενη έκδοση της μορφής αρχείου παρουσίασης PPT που ήταν δυαδική, η μορφή PPTX βασίζεται στη μορφή αρχείου παρουσίασης Microsoft PowerPoint Open XML. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/pptx/). |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Εισήχθη και τεκμηριώθηκε από τη Microsoft, το Rich Text Format (RTF) αντιπροσωπεύει μια μέθοδο κωδικοποίησης μορφοποιημένου κειμένου και γραφικών για χρήση σε εφαρμογές. Η μορφή διευκολύνει την ανταλλαγή εγγράφων μεταξύ πλατφορμών με άλλα προϊόντα της Microsoft, εξυπηρετώντας έτσι τον σκοπό της διαλειτουργικότητας. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/rtf/). |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | Το TIFF ή TIF, Tagged Image File Format, αντιπροσωπεύει ραστερ εικόνες που προορίζονται για χρήση σε ποικίλες συσκευές που συμμορφώνονται με αυτό το πρότυπο μορφής αρχείου. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/tiff/). |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | Το TIFF ή TIF, Tagged Image File Format, αντιπροσωπεύει ραστερ εικόνες που προορίζονται για χρήση σε ποικίλες συσκευές που συμμορφώνονται με αυτό το πρότυπο μορφής αρχείου. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/tiff/). |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | Αντιπροσωπεύει άγνωστο τύπο αρχείου. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | Το VDW είναι η μορφή αρχείου Visio Graphics Service που καθορίζει τις ροές και τις αποθηκεύσεις που απαιτούνται για την απόδοση ενός σχεδίου Web. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/web/vdw/). |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Οποιοδήποτε σχέδιο ή διάγραμμα δημιουργείται στο Microsoft Visio, αλλά αποθηκεύεται σε μορφή XML, έχει την επέκταση .VDX. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vdx/). |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | Τα αρχεία VSD είναι σχέδια που δημιουργούνται με την εφαρμογή Microsoft Visio για να αντιπροσωπεύουν ποικιλία γραφικών αντικειμένων και τη διασύνδεσή τους. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vsd/). |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | Τα αρχεία με επέκταση VSDM είναι αρχεία σχεδίων που δημιουργούνται με την εφαρμογή Microsoft Visio και υποστηρίζουν μακροεντολές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vsdm/). |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | Τα αρχεία με επέκταση .VSDX αντιπροσωπεύουν τη μορφή αρχείου Microsoft Visio που εισήχθη από το Microsoft Office 2013 και μετά. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vsdx/). |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | Τα VSS είναι αρχεία στενσίλ που δημιουργήθηκαν με το Microsoft Visio 2007 και παλαιότερα. Τα αρχεία στενσίλ παρέχουν αντικείμενα σχεδίου που μπορούν να συμπεριληφθούν σε ένα σχέδιο .VSD του Visio. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vss/). |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | Τα αρχεία με επέκταση .VSSM είναι αρχεία στενσίλ του Microsoft Visio που παρέχουν υποστήριξη για μακροεντολές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vssm/). |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | Τα αρχεία με επέκταση .VSSX είναι στενσίλ σχεδίων που δημιουργήθηκαν με το Microsoft Visio 2013 και μεταγενέστερα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vssx/). |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | Τα αρχεία με επέκταση VST είναι αρχεία διανυσματικών εικόνων που δημιουργήθηκαν με το Microsoft Visio και λειτουργούν ως πρότυπο για τη δημιουργία περαιτέρω αρχείων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vst/). |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | Τα αρχεία με επέκταση VSTM είναι αρχεία προτύπων που δημιουργήθηκαν με το Microsoft Visio και υποστηρίζουν μακροεντολές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vstm/). |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | Τα αρχεία με επέκταση VSTX είναι αρχεία προτύπων σχεδίων που δημιουργήθηκαν με το Microsoft Visio 2013 και μεταγενέστερα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vstx/). |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | Τα αρχεία με επέκταση .VSX αναφέρονται σε στενσίλ που αποτελούνται από σχέδια και σχήματα που χρησιμοποιούνται για τη δημιουργία διαγραμμάτων στο Microsoft Visio. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vsx/). |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | Ένα αρχείο με επέκταση VTX είναι ένα πρότυπο σχεδίου Microsoft Visio που αποθηκεύεται στο δίσκο σε μορφή αρχείου XML. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vtx/). |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | Το WebP, που εισήχθη από τη Google, είναι μια σύγχρονη ραστερ μορφή αρχείου εικόνας για το web που βασίζεται σε συμπίεση χωρίς απώλειες και με απώλειες. Παρέχει την ίδια ποιότητα εικόνας ενώ μειώνει σημαντικά το μέγεθος της εικόνας. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/webp/). |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | Τα αρχεία με επέκταση XLS αντιπροσωπεύουν τη μορφή αρχείου Excel Binary. Τέτοια αρχεία μπορούν να δημιουργηθούν από το Microsoft Excel καθώς και από άλλα παρόμοια προγράμματα λογιστικών φύλλων όπως το OpenOffice Calc ή το Apple Numbers. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/specification/spreadsheet/xls/). |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | Η μορφή αρχείου XLSB καθορίζει το Excel Binary File Format, το οποίο είναι μια συλλογή εγγραφών και δομών που καθορίζουν το περιεχόμενο του βιβλίου εργασίας του Excel. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/specification/spreadsheet/xlsb/). |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | Τα αρχεία με επέκταση XLSM είναι ένας τύπος αρχείων λογιστικού φύλλου που υποστηρίζουν μακροεντολές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/specification/spreadsheet/xlsm/). |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | Το XLSX είναι μια ευρέως γνωστή μορφή για έγγραφα Microsoft Excel που εισήχθη από τη Microsoft με την κυκλοφορία του Microsoft Office 2007. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/specification/spreadsheet/xlsx/). |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | Τα αρχεία με επέκταση .XLT είναι αρχεία προτύπου που δημιουργήθηκαν με το Microsoft Excel, το οποίο είναι μια εφαρμογή λογιστικού φύλλου που αποτελεί μέρος της σουίτας Microsoft Office. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/specification/spreadsheet/xlt/). |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | Η επέκταση αρχείου XLTM αντιπροσωπεύει αρχεία που δημιουργούνται από το Microsoft Excel ως αρχεία προτύπου με ενεργοποιημένα μακροεντολές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/specification/spreadsheet/xltm/). |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | Τα αρχεία με επέκταση XLTX αντιπροσωπεύουν αρχεία προτύπου Microsoft Excel που βασίζονται στις προδιαγραφές του μορφότυπου Office OpenXML. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/specification/spreadsheet/xltx/). |

### Σχόλια

Αυτή η κλάση παρέχει μεθόδους για την απόκτηση λίστας όλων των τύπων αρχείων που υποστηρίζονται από **GroupDocs.Watermark**.**Μάθετε περισσότερα**

* [Supported Document Formats](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Get supported file formats](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Δείτε επίσης

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
