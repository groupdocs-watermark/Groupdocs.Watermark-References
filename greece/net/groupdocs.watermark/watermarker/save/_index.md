---
title: "Αποθήκευση"
second_title: "GroupDocs.Watermark για .NET API Αναφορά"
description: "Αποθηκεύει τα δεδομένα του εγγράφου στο υποκείμενο stream."
type: docs
weight: 100
url: /el/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Αποθηκεύει τα δεδομένα του εγγράφου στο υποκείμενο stream.

```csharp
public WatermarkResult Save()
```

### Σχόλια

Μάθετε περισσότερα για την αποθήκευση των εγγράφων [Αποθήκευση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Παραδείγματα

Αφαιρέστε συγκεκριμένα αποσπάσματα κειμένου από το σώμα/θέμα του email και αποθηκεύστε το μήνυμα email.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Σημείωση, η αναζήτηση εκτελείται μόνο εάν περάσετε ένα αντικείμενο TextSearchCriteria στη μέθοδο Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Αφαιρέστε τα ευρεθέντα αποσπάσματα κειμένου
    watermarker.Remove(watermarks);
    // Αποθηκεύστε τις αλλαγές
    watermarker.Save();
}
```

### Δείτε επίσης

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Αποθηκεύει το έγγραφο στην καθορισμένη θέση αρχείου.

```csharp
public WatermarkResult Save(string filePath)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου όπου θα αποθηκευτούν τα δεδομένα του εγγράφου. |

### Σχόλια

Μάθετε περισσότερα για την αποθήκευση των εγγράφων [Αποθήκευση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Παραδείγματα

Προσθέστε την υδατογραφία και αποθηκεύστε το έγγραφο σε άλλο αρχείο.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### Δείτε επίσης

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Αποθηκεύει το έγγραφο στο καθορισμένο stream.

```csharp
public WatermarkResult Save(Stream document)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| έγγραφο | Stream | Η ροή όπου θα αποθηκευτούν τα δεδομένα του εγγράφου. |

### Σχόλια

Μάθετε περισσότερα για την αποθήκευση των εγγράφων [Αποθήκευση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Παραδείγματα

Προσθέστε υδατογραφία και αποθηκεύστε το έγγραφο στο memory stream.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream);
        // ...
    }
}
```

### Δείτε επίσης

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Αποθηκεύει τα δεδομένα του εγγράφου στο υποκείμενο stream χρησιμοποιώντας επιλογές αποθήκευσης.

```csharp
public WatermarkResult Save(SaveOptions options)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| επιλογές | SaveOptions | Πρόσθετες επιλογές για χρήση κατά την αποθήκευση ενός εγγράφου. |

### Σχόλια

Μάθετε περισσότερα για την αποθήκευση των εγγράφων [Αποθήκευση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Παραδείγματα

Προσθέστε υδατογράφημα και αποθηκεύστε το έγγραφο με τις προεπιλεγμένες [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Δείτε επίσης

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Αποθηκεύει το έγγραφο στην καθορισμένη θέση αρχείου χρησιμοποιώντας επιλογές αποθήκευσης.

```csharp
public WatermarkResult Save(string filePath, SaveOptions options)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου όπου θα αποθηκευτούν τα δεδομένα του εγγράφου. |
| επιλογές | SaveOptions | Πρόσθετες επιλογές για χρήση κατά την αποθήκευση ενός εγγράφου. |

### Σχόλια

Μάθετε περισσότερα για την αποθήκευση των εγγράφων [Αποθήκευση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Παραδείγματα

Προσθέστε το υδατογράφημα και αποθηκεύστε το έγγραφο σε άλλο αρχείο με τις προεπιλεγμένες [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Δείτε επίσης

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Αποθηκεύει το έγγραφο στο καθορισμένο stream χρησιμοποιώντας επιλογές αποθήκευσης.

```csharp
public WatermarkResult Save(Stream document, SaveOptions options)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| έγγραφο | Stream | Η ροή όπου θα αποθηκευτούν τα δεδομένα του εγγράφου. |
| επιλογές | SaveOptions | Πρόσθετες επιλογές για χρήση κατά την αποθήκευση ενός εγγράφου. |

### Σχόλια

Μάθετε περισσότερα για την αποθήκευση των εγγράφων [Αποθήκευση εγγράφων](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Παραδείγματα

Προσθέστε υδατογράφημα και αποθηκεύστε το έγγραφο στη ροή μνήμης με τις προεπιλεγμένες [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream, new SaveOptions());
        // ...
    }
}
```

### Δείτε επίσης

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
