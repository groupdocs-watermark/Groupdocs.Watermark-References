---
title: "Salva"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Salva i dati del documento nello stream sottostante."
type: docs
weight: 100
url: /it/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Salva i dati del documento nello stream sottostante.

```csharp
public WatermarkResult Save()
```

### Osservazioni

Scopri di più sul salvataggio dei documenti [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Esempi

Rimuovi specifici frammenti di testo dal corpo/oggetto del messaggio email e salva il messaggio email.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Nota, la ricerca viene eseguita solo se si passa un'istanza di TextSearchCriteria al metodo Search.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Rimuovi i frammenti di testo trovati
    watermarker.Remove(watermarks);
    // Salva le modifiche
    watermarker.Save();
}
```

### Vedi anche

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Salva il documento nella posizione file specificata.

```csharp
public WatermarkResult Save(string filePath)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso file dove salvare i dati del documento. |

### Osservazioni

Scopri di più sul salvataggio dei documenti [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Esempi

Aggiungi la filigrana e salva il documento in un altro file.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### Vedi anche

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Salva il documento nello stream specificato.

```csharp
public WatermarkResult Save(Stream document)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| documento | Stream | Lo stream dove salvare i dati del documento. |

### Osservazioni

Scopri di più sul salvataggio dei documenti [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Esempi

Aggiungi la filigrana e salva il documento nello stream di memoria.

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

### Vedi anche

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Salva i dati del documento nello stream sottostante utilizzando le opzioni di salvataggio.

```csharp
public WatermarkResult Save(SaveOptions options)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| opzioni | SaveOptions | Opzioni aggiuntive da utilizzare durante il salvataggio di un documento. |

### Osservazioni

Scopri di più sul salvataggio dei documenti [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Esempi

Aggiungi una filigrana e salva il documento con le [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) predefinite.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Vedi anche

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Salva il documento nella posizione file specificata utilizzando le opzioni di salvataggio.

```csharp
public WatermarkResult Save(string filePath, SaveOptions options)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso file dove salvare i dati del documento. |
| opzioni | SaveOptions | Opzioni aggiuntive da utilizzare durante il salvataggio di un documento. |

### Osservazioni

Scopri di più sul salvataggio dei documenti [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Esempi

Aggiungi la filigrana e salva il documento in un altro file con le [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) predefinite.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Vedi anche

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Salva il documento nello stream specificato utilizzando le opzioni di salvataggio.

```csharp
public WatermarkResult Save(Stream document, SaveOptions options)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| documento | Stream | Lo stream dove salvare i dati del documento. |
| opzioni | SaveOptions | Opzioni aggiuntive da utilizzare durante il salvataggio di un documento. |

### Osservazioni

Scopri di più sul salvataggio dei documenti [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Esempi

Aggiungi una filigrana e salva il documento nello stream di memoria con le [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) predefinite.

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

### Vedi anche

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
