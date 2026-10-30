---
title: "Remove"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rimuove il watermark dal documento."
type: docs
weight: 90
url: /it/net/groupdocs.watermark/watermarker/remove/
---
## Remove(PossibleWatermark) {#remove}

Rimuove il watermark dal documento.

```csharp
public void Remove(PossibleWatermark possibleWatermark)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| possibleWatermark | PossibleWatermark | La filigrana da rimuovere. |

### Osservazioni

Maggiori informazioni sulla rimozione delle filigrane: [Rimozione delle filigrane trovate](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks).

### Esempi

Trova e rimuovi la prima possibile filigrana contenente testo o immagine specifici da un documento di qualsiasi tipo supportato.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    if (watermarks.Count > 0)
    {
        watermarker.Remove(watermarks[0]);
    }

    watermarker.Save(@"D:\output.doc");
}
```

### Vedi anche

* class [PossibleWatermark](../../../groupdocs.watermark.search/possiblewatermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Remove(PossibleWatermarkCollection) {#remove_1}

Rimuove tutti i watermark nella collezione dal documento.

```csharp
public void Remove(PossibleWatermarkCollection possibleWatermarks)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| possibleWatermarks | PossibleWatermarkCollection | La raccolta di filigrane da rimuovere. |

### Osservazioni

Maggiori informazioni sulla rimozione delle filigrane [Rimozione delle filigrane trovate](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks).

### Esempi

Trova e rimuovi tutte le filigrane possibili contenenti testo o immagine specifici da un documento di qualsiasi tipo supportato.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    watermarker.Remove(watermarks);
    watermarker.Save(@"D:\output.doc");
}
```

### Vedi anche

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
