---
title: "Search"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Cerca tutte le possibili filigrane nel documento."
type: docs
weight: 110
url: /it/net/groupdocs.watermark/watermarker/search/
---
## Search() {#search}

Cerca tutte le possibili filigrane nel documento.

```csharp
public PossibleWatermarkCollection Search()
```

### Valore di ritorno

La collezione di filigrane possibili.

### Osservazioni

La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../searchableobjects).

Scopri di più sulla ricerca delle filigrane [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Esempi

Conta le filigrane possibili in un documento di qualsiasi tipo supportato.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    PossibleWatermarkCollection watermarks = watermarker.Search();
    Console.WrileLine(watermarks.Count);
}
```

### Vedi anche

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Search(SearchCriteria) {#search_1}

Cerca le filigrane possibili secondo i criteri di ricerca specificati.

```csharp
public PossibleWatermarkCollection Search(SearchCriteria searchCriteria)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| searchCriteria | SearchCriteria | I criteri di ricerca da utilizzare. |

### Valore di ritorno

La collezione di filigrane possibili.

### Osservazioni

La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../searchableobjects).

Scopri di più sulla ricerca delle filigrane [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Esempi

Trova e rimuovi tutte le filigrane possibili contenenti testo o immagine specifici da un documento di qualsiasi tipo supportato.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    watermarks.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### Vedi anche

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [SearchCriteria](../../../groupdocs.watermark.search.searchcriteria/searchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
