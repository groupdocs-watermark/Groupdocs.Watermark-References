---
title: Save
second_title: GroupDocs.Watermark για Αναφορά API .NET
description: Αποθηκεύει τα δεδομένα του εγγράφου στην υποκείμενη ροή.
type: docs
weight: 100
url: /el/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Αποθηκεύει τα δεδομένα του εγγράφου στην υποκείμενη ροή.

```csharp
public void Save()
```

### Παρατηρήσεις

Μάθετε περισσότερα σχετικά με την αποθήκευση των εγγράφων [Αποθήκευση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Παραδείγματα

Αφαιρέστε συγκεκριμένα θραύσματα κειμένου από το σώμα/θέμα του μηνύματος email και αποθηκεύστε το μήνυμα email.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Σημείωση, η αναζήτηση εκτελείται μόνο εάν περάσετε την παρουσία TextSearchCriteria στη μέθοδο αναζήτησης
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Αφαίρεση τεμαχίων κειμένου που βρέθηκαν
    watermarker.Remove(watermarks);
    // Αποθήκευσε τις αλλαγές
    watermarker.Save();
}
```

### Δείτε επίσης

* class [Watermarker](../../watermarker)
* χώρος ονομάτων [GroupDocs.Watermark](../../watermarker)
* συνέλευση [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Αποθηκεύει το έγγραφο στην καθορισμένη θέση αρχείου.

```csharp
public void Save(string filePath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου στην οποία αποθηκεύονται τα δεδομένα του εγγράφου. |

### Παρατηρήσεις

Μάθετε περισσότερα σχετικά με την αποθήκευση των εγγράφων [Αποθήκευση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Παραδείγματα

Προσθέστε το υδατογράφημα και αποθηκεύστε το έγγραφο σε άλλο αρχείο.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### Δείτε επίσης

* class [Watermarker](../../watermarker)
* χώρος ονομάτων [GroupDocs.Watermark](../../watermarker)
* συνέλευση [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Αποθηκεύει το έγγραφο στην καθορισμένη ροή.

```csharp
public void Save(Stream document)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Η ροή στην οποία αποθηκεύονται τα δεδομένα του εγγράφου. |

### Παρατηρήσεις

Μάθετε περισσότερα σχετικά με την αποθήκευση των εγγράφων [Αποθήκευση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Παραδείγματα

Προσθέστε υδατογράφημα και αποθηκεύστε το έγγραφο στη ροή μνήμης.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream);
        //...
    }
}
```

### Δείτε επίσης

* class [Watermarker](../../watermarker)
* χώρος ονομάτων [GroupDocs.Watermark](../../watermarker)
* συνέλευση [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Αποθηκεύει τα δεδομένα του εγγράφου στην υποκείμενη ροή χρησιμοποιώντας τις επιλογές αποθήκευσης.

```csharp
public void Save(SaveOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | SaveOptions | Πρόσθετες επιλογές για χρήση κατά την αποθήκευση ενός εγγράφου. |

### Παρατηρήσεις

Μάθετε περισσότερα σχετικά με την αποθήκευση των εγγράφων [Αποθήκευση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Παραδείγματα

Προσθέστε υδατογράφημα και αποθηκεύστε το έγγραφο με προεπιλογή[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Δείτε επίσης

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* χώρος ονομάτων [GroupDocs.Watermark](../../watermarker)
* συνέλευση [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Αποθηκεύει το έγγραφο στην καθορισμένη θέση αρχείου χρησιμοποιώντας τις επιλογές αποθήκευσης.

```csharp
public void Save(string filePath, SaveOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου στην οποία αποθηκεύονται τα δεδομένα του εγγράφου. |
| options | SaveOptions | Πρόσθετες επιλογές για χρήση κατά την αποθήκευση ενός εγγράφου. |

### Παρατηρήσεις

Μάθετε περισσότερα σχετικά με την αποθήκευση των εγγράφων [Αποθήκευση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Παραδείγματα

Προσθέστε το υδατογράφημα και αποθηκεύστε το έγγραφο σε άλλο αρχείο με προεπιλογή[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Δείτε επίσης

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* χώρος ονομάτων [GroupDocs.Watermark](../../watermarker)
* συνέλευση [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Αποθηκεύει το έγγραφο στην καθορισμένη ροή χρησιμοποιώντας τις επιλογές αποθήκευσης.

```csharp
public void Save(Stream document, SaveOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Η ροή στην οποία αποθηκεύονται τα δεδομένα του εγγράφου. |
| options | SaveOptions | Πρόσθετες επιλογές για χρήση κατά την αποθήκευση ενός εγγράφου. |

### Παρατηρήσεις

Μάθετε περισσότερα σχετικά με την αποθήκευση των εγγράφων [Αποθήκευση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Παραδείγματα

Προσθέστε υδατογράφημα και αποθηκεύστε το έγγραφο στη ροή μνήμης με προεπιλογή[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream, new SaveOptions());
        //...
    }
}
```

### Δείτε επίσης

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* χώρος ονομάτων [GroupDocs.Watermark](../../watermarker)
* συνέλευση [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
