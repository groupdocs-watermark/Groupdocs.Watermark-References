---
title: Save
second_title: Riferimento API GroupDocs.Watermark per .NET
description: Salva i dati del documento nel flusso sottostante.
type: docs
weight: 100
url: /it/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Salva i dati del documento nel flusso sottostante.

```csharp
public void Save()
```

### Osservazioni

Ulteriori informazioni sul salvataggio dei documenti [Salvataggio di documenti](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Esempi

Rimuove particolari frammenti di testo dal corpo/oggetto del messaggio e-mail e salva il messaggio e-mail.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Nota, la ricerca viene eseguita solo se passi l'istanza TextSearchCriteria al metodo Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Rimuovi i frammenti di testo trovati
    watermarker.Remove(watermarks);
    // Salvare le modifiche
    watermarker.Save();
}
```

### Guarda anche

* class [Watermarker](../../watermarker)
* spazio dei nomi [GroupDocs.Watermark](../../watermarker)
* assemblea [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Salva il documento nella posizione file specificata.

```csharp
public void Save(string filePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file in cui salvare i dati del documento. |

### Osservazioni

Ulteriori informazioni sul salvataggio dei documenti [Salvataggio di documenti](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

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

### Guarda anche

* class [Watermarker](../../watermarker)
* spazio dei nomi [GroupDocs.Watermark](../../watermarker)
* assemblea [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Salva il documento nel flusso specificato.

```csharp
public void Save(Stream document)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Il flusso in cui salvare i dati del documento. |

### Osservazioni

Ulteriori informazioni sul salvataggio dei documenti [Salvataggio di documenti](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Esempi

Aggiungi filigrana e salva il documento nel flusso di memoria.

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

### Guarda anche

* class [Watermarker](../../watermarker)
* spazio dei nomi [GroupDocs.Watermark](../../watermarker)
* assemblea [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Salva i dati del documento nel flusso sottostante utilizzando le opzioni di salvataggio.

```csharp
public void Save(SaveOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | SaveOptions | Opzioni aggiuntive da utilizzare durante il salvataggio di un documento. |

### Osservazioni

Ulteriori informazioni sul salvataggio dei documenti [Salvataggio di documenti](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Esempi

Aggiungi filigrana e salva il documento con l'impostazione predefinita[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Guarda anche

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* spazio dei nomi [GroupDocs.Watermark](../../watermarker)
* assemblea [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Salva il documento nella posizione del file specificata utilizzando le opzioni di salvataggio.

```csharp
public void Save(string filePath, SaveOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file in cui salvare i dati del documento. |
| options | SaveOptions | Opzioni aggiuntive da utilizzare durante il salvataggio di un documento. |

### Osservazioni

Ulteriori informazioni sul salvataggio dei documenti [Salvataggio di documenti](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Esempi

Aggiungi la filigrana e salva il documento in un altro file con default[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Guarda anche

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* spazio dei nomi [GroupDocs.Watermark](../../watermarker)
* assemblea [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Salva il documento nel flusso specificato utilizzando le opzioni di salvataggio.

```csharp
public void Save(Stream document, SaveOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Il flusso in cui salvare i dati del documento. |
| options | SaveOptions | Opzioni aggiuntive da utilizzare durante il salvataggio di un documento. |

### Osservazioni

Ulteriori informazioni sul salvataggio dei documenti [Salvataggio di documenti](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Esempi

Aggiungi filigrana e salva il documento nel flusso di memoria con impostazione predefinita[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

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

### Guarda anche

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* spazio dei nomi [GroupDocs.Watermark](../../watermarker)
* assemblea [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
