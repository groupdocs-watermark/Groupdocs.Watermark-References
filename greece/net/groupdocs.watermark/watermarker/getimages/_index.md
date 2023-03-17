---
title: GetImages
second_title: GroupDocs.Watermark για Αναφορά API .NET
description: Βρίσκει εικόνες σύμφωνα με καθορισμένα κριτήρια αναζήτησης.
type: docs
weight: 80
url: /el/net/groupdocs.watermark/watermarker/getimages/
---
## GetImages(ImageSearchCriteria) {#getimages_1}

Βρίσκει εικόνες σύμφωνα με καθορισμένα κριτήρια αναζήτησης.

```csharp
public WatermarkableImageCollection GetImages(ImageSearchCriteria searchCriteria)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| searchCriteria | ImageSearchCriteria | Τα κριτήρια αναζήτησης προς χρήση. |

### Επιστρεφόμενη Αξία

Η συλλογή των εικόνων που βρέθηκαν.

### Παρατηρήσεις

Η αναζήτηση πραγματοποιείται σε αντικείμενα που καθορίζονται στο[`SearchableObjects`](../searchableobjects).

Μάθετε περισσότερα σχετικά με την αναζήτηση watermarks [Αναζήτηση υδατογραφημάτων](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Παραδείγματα

Καταργήστε όλες τις εικόνες που είναι παρόμοιες με την αναφορά από ένα έγγραφο οποιουδήποτε υποστηριζόμενου τύπου.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageThumbnailSearchCriteria criteria = new ImageThumbnailSearchCriteria("reference.png");
    WatermarkableImageCollection images = watermarker.GetImages(criteria);
    images.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### Δείτε επίσης

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [ImageSearchCriteria](../../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria)
* class [Watermarker](../../watermarker)
* χώρος ονομάτων [GroupDocs.Watermark](../../watermarker)
* συνέλευση [GroupDocs.Watermark](../../../)

---

## GetImages() {#getimages}

Βρίσκει όλες τις εικόνες στο έγγραφο.

```csharp
public WatermarkableImageCollection GetImages()
```

### Επιστρεφόμενη Αξία

Η συλλογή των εικόνων που βρέθηκαν.

### Παρατηρήσεις

Η αναζήτηση πραγματοποιείται σε αντικείμενα που καθορίζονται στο[`SearchableObjects`](../searchableobjects).

Μάθετε περισσότερα σχετικά με την αναζήτηση watermarks [Αναζήτηση υδατογραφημάτων](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Παραδείγματα

Προσθήκη υδατογραφήματος σε όλες τις εικόνες σε ένα έγγραφο οποιουδήποτε υποστηριζόμενου τύπου.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // Αρχικοποίηση υδατογραφήματος κειμένου ή εικόνας.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // Βρείτε όλες τις εικόνες στο έγγραφο.
    WatermarkableImageCollection images = watermarker.GetImages();

    // Προσθέστε υδατογράφημα.
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.AddWatermark(watermark);
    }

    // Αποθήκευσε τις αλλαγές.
    watermarker.Save(@"D:\output.doc");
}
```

### Δείτε επίσης

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [Watermarker](../../watermarker)
* χώρος ονομάτων [GroupDocs.Watermark](../../watermarker)
* συνέλευση [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->