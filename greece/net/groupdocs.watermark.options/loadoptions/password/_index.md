---
title: Password
second_title: GroupDocs.Watermark για Αναφορά API .NET
description: Λαμβάνει ή ορίζει τον κωδικό πρόσβασης για το άνοιγμα ενός κρυπτογραφημένου εγγράφου.
type: docs
weight: 30
url: /el/net/groupdocs.watermark.options/loadoptions/password/
---
## LoadOptions.Password property

Λαμβάνει ή ορίζει τον κωδικό πρόσβασης για το άνοιγμα ενός κρυπτογραφημένου εγγράφου.

```csharp
public string Password { get; set; }
```

### Αξία περιουσίας

Ο κωδικός πρόσβασης για το άνοιγμα ενός κρυπτογραφημένου εγγράφου.

### Παρατηρήσεις

Ο κωδικός πρόσβασης είναι μηδενικός ή κενός συμβολοσειράς. Η προεπιλεγμένη τιμή είναι null. Εάν το περιεχόμενο δεν είναι κρυπτογραφημένο, ορίστε τη σε null ή άδεια συμβολοσειρά.

### Παραδείγματα

Φόρτωση περιεχομένου που προστατεύεται με κωδικό πρόσβασης.

```csharp
LoadOptions loadOptions = new LoadOptions
{
    Password = "pwd123"
};
using (Watermarker watermarker = new Watermarker(@"D:\doc.vsdx", loadOptions))
{
    //...
}
```

### Δείτε επίσης

* class [LoadOptions](../../loadoptions)
* χώρος ονομάτων [GroupDocs.Watermark.Options](../../loadoptions)
* συνέλευση [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
