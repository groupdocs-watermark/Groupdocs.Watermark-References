---
title: "Το GroupDocs.Watermark για Python μέσω .NET προσθέτει, αναζητά και αφαιρεί υδατογραφήματα κειμένου και εικόνας μέσω ενός ενιαίου, ανεξάρτητου από μορφή API — με τοποθέτηση ειδική για μορφή, επεξεργασία δέντρου περιεχομένου, κλείδωμα και rasterization."
linkTitle: "Features overview"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Το GroupDocs.Watermark για Python μέσω .NET προσθέτει, αναζητά και αφαιρεί υδατογραφήματα σε μια ευρεία γκάμα [υποστηριζόμενων μορφών εγγράφων](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/). Κάθε λειτουργία ακολουθεί την ίδια ροή εργασίας: ανοίξτε ένα έγγραφο με το [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/), καλέστε `add()`, `search()` ή `remove()`, στη συνέχεια `save()` το αποτέλεσμα πίσω στην αρχική του μορφή. Οι δυνατότητες παρακάτω μπορούν να συνδυαστούν ελεύθερα σε μία μόνο διεργασία."
type: docs
url: /el/python-net/guides/features-overview/
is_root: false
weight: 30
---


Προσθέστε μορφοποιημένα κείμενα ή υδατογραφήματα εικόνας με πλήρη έλεγχο της γραμματοσειράς, χρώματος, διαφάνειας, περιστροφής, στοίχισης και μεγέθους. Τα υδατογραφήματα εικόνας μπορούν να φορτωθούν από αρχείο ή ροή. Δείτε [Add text watermarks](/watermark/python-net/guides/add-text/) και [Add image watermarks](/watermark/python-net/guides/add-image/).

## Text and image watermarks

Τοποθετήστε ένα υδατογράφημα με απόλυτες συντεταγμένες ή στοίχιση και περιθώρια σχετικές με το γονικό στοιχείο, κλιμακώστε το σε σχέση με τη σελίδα, περιστρέψτε το και επαναλάβετε το σε ολόκληρη τη σελίδα σε επαναλαμβανόμενο μοτίβο. Δείτε [Customize watermarks](/watermark/python-net/guides/customize/), [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/), και [Adding text watermarks](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/).

## Customization and tiling

Τοποθετήστε υδατογραφήματα χρησιμοποιώντας τις επιλογές που ταιριάζουν σε κάθε μορφή — αντικείμενα PDF, σημειώσεις και σημειώσεις μόνο για εκτύπωση· διαφάνειες παρουσίασης, master, διατάξεις και σημειώσεις· φύλλα εργασίας λογιστικού φύλλου, φόντα και κεφαλίδες/υποσέλιδα· σελίδες Visio· και κλειδωμένα τμήματα και σελίδες Word. Δείτε [Add watermarks to PDF documents](https://docs.groupdocs.com/watermark/python-net/add-watermarks-to-pdf-documents/) και τα άλλα θέματα μορφής στον [Developer Guide](https://docs.groupdocs.com/watermark/python-net/adding-watermarks/).

## Format-specific placement

Βρείτε υδατογραφήματα που ήδη υπάρχουν σε ένα έγγραφο — συμπεριλαμβανομένων εκείνων που προστέθηκαν από εργαλεία τρίτων — με ακριβές κείμενο, κανονική έκφραση, ομοιότητα εικόνας ή μορφοποίηση κειμένου, και συνδυάστε κριτήρια με `and_`/`or_`/`not_`. Μόλις βρεθούν, αντικαταστήστε το κείμενο ή την εικόνα τους, ή αφαιρέστε τα. Δείτε [Searching watermarks](/watermark/python-net/guides/searching-watermarks/), [Modifying found watermark properties](https://docs.groupdocs.com/watermark/python-net/modifying-found-watermark-properties/), και [Removing found watermarks](https://docs.groupdocs.com/watermark/python-net/removing-found-watermarks/).

## Searching, modifying, and removing

Βρείτε υδατογραφήματα που ήδη υπάρχουν σε ένα έγγραφο — συμπεριλαμβανομένων εκείνων που προστέθηκαν από εργαλεία τρίτων — με ακριβές κείμενο, κανονική έκφραση, ομοιότητα εικόνας ή μορφοποίηση κειμένου, και συνδυάστε τα κριτήρια με `and_`/`or_`/`not_`. Μόλις βρεθούν, αντικαταστήστε το κείμενό τους ή την εικόνα, ή αφαιρέστε τα. Δείτε [Searching watermarks](/watermark/python-net/guides/searching-watermarks/), [Modifying found watermark properties](https://docs.groupdocs.com/watermark/python-net/modifying-found-watermark-properties/), και [Removing found watermarks](https://docs.groupdocs.com/watermark/python-net/removing-found-watermarks/).

## Working with existing content

`Watermarker.get_content()` εκθέτει ένα δέντρο περιεχομένου ειδικό για μορφή ώστε να μπορείτε να επιθεωρήσετε και να επεξεργαστείτε υπάρχουσες μορφές, PDF XObjects/αποτυπώματα/σχόλια, συνημμένα, φόντα και κεφαλίδες/υποσέλιδα — και μπορείτε να προσθέσετε υδατογράφημα στις εικόνες που είναι ενσωματωμένες σε ένα έγγραφο με `get_images()`. Δείτε [Adding watermark to images inside a document](https://docs.groupdocs.com/watermark/python-net/adding-watermark-to-images-inside-a-document/).

## Tamper resistance

Κάντε τα υδατογραφήματα δύσκολο να αφαιρεθούν κλειδώνοντάς τα, προστατεύοντας έγγραφα Word, προσθέτοντας σχόλια PDF μόνο για εκτύπωση ή ραστεριάζοντας σελίδες PDF ώστε το υδατογράφημα να μην μπορεί να επεξεργαστεί. Δείτε [Locking watermark in word processing document](https://docs.groupdocs.com/watermark/python-net/locking-watermark-in-word-processing-document/) και [Rasterize document or page](https://docs.groupdocs.com/watermark/python-net/rasterize-document-or-page/).

## Document inspection

Διαβάστε τον τύπο αρχείου, τον αριθμό σελίδων και το μέγεθος ενός εγγράφου χωρίς να το τροποποιήσετε, και απαριθμήστε κάθε μορφή αρχείου που υποστηρίζει η βιβλιοθήκη. Δείτε [Get document info](/watermark/python-net/guides/get-document-info/) και [Get supported file formats](/watermark/python-net/guides/get-supported-file-formats/).

## On-premise

Το GroupDocs.Watermark για Python μέσω .NET εκτελείται εξ ολοκλήρου στην υποδομή σας — τα έγγραφά σας δεν αφήνουν ποτέ το περιβάλλον σας. Το πακέτο είναι ένας αυτόνομος wheel που ενσωματώνει όλα όσα χρειάζεται, ώστε να μην χρειάζεται εγκατάσταση Microsoft Office, OpenOffice ή ξεχωριστής runtime. Δείτε [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) για τις υποστηριζόμενες πλατφόρμες και τις εγγενείς εξαρτήσεις.
