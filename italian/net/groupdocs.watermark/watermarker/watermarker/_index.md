---
title: Watermarker
second_title: Riferimento API GroupDocs.Watermark per .NET
description: Inizializza una nuova istanza diWatermarkergroupdocs.watermark/watermarker classe con il percorso del documento specificato.
type: docs
weight: 10
url: /it/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Inizializza una nuova istanza di[`Watermarker`](../../watermarker) classe con il percorso del documento specificato.

```csharp
public Watermarker(string filePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file da cui caricare il documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Il tipo di documento fornito non è supportato. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La password fornita non è corretta. |

### Osservazioni

Ulteriori informazioni sul caricamento dei documenti: [Caricamento documenti](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Esempi

Carica e salva un contenuto di qualsiasi formato supportato.

```csharp
// Carica un contenuto da un file.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Utilizza i metodi della classe Watermarker per aggiungere, cercare o rimuovere filigrane.

    // Salva il documento.
    watermarker.Save("D:\\output.pdf");
}
```

### Guarda anche

* class [Watermarker](../../watermarker)
* spazio dei nomi [GroupDocs.Watermark](../../watermarker)
* assemblea [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Inizializza una nuova istanza di[`Watermarker`](../../watermarker)class con il percorso del documento specificato e le opzioni di caricamento.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file da cui caricare il documento. |
| options | LoadOptions | Opzioni aggiuntive da utilizzare durante il caricamento di un documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Il tipo di documento fornito non è supportato. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La password fornita non è corretta. |

### Osservazioni

Ulteriori informazioni sul caricamento dei documenti: [Caricamento documenti](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Esempi

Carica il documento PDF crittografato utilizzando la password.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    //...
}
```

### Guarda anche

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* spazio dei nomi [GroupDocs.Watermark](../../watermarker)
* assemblea [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Inizializza una nuova istanza di[`Watermarker`](../../watermarker) class con il percorso e le impostazioni del documento specificati .

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file da cui caricare il documento. |
| settings | WatermarkerSettings | Impostazioni aggiuntive da utilizzare quando si lavora con il documento caricato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Il tipo di documento fornito non è supportato. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La password fornita non è corretta. |

### Osservazioni

Ulteriori informazioni sul caricamento dei documenti: [Caricamento documenti](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Esempi

Imposta gli oggetti ricercabili a livello globale (per tutti i documenti che verranno caricati successivamente).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (Watermarker watermarker = new Watermarker(file, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // Il codice per lavorare con le filigrane trovate va qui.
    }
}
```

### Guarda anche

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* spazio dei nomi [GroupDocs.Watermark](../../watermarker)
* assemblea [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Inizializza una nuova istanza di[`Watermarker`](../../watermarker) classe con il percorso del documento specificato , caricare le opzioni e le impostazioni.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file da cui caricare il documento. |
| options | LoadOptions | Opzioni aggiuntive da utilizzare durante il caricamento di un documento. |
| settings | WatermarkerSettings | Impostazioni aggiuntive da utilizzare quando si lavora con il documento caricato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Il tipo di documento fornito non è supportato. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La password fornita non è corretta. |

### Osservazioni

Ulteriori informazioni sul caricamento dei documenti: [Caricamento documenti](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Esempi

Trova particolari frammenti di testo nel corpo/oggetto del messaggio di posta elettronica.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.msg", loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Nota, la ricerca viene eseguita solo se passi l'istanza TextSearchCriteria al metodo Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Rimuovi i frammenti di testo trovati
    watermarks.Clear();
    // Salvare le modifiche
    watermarker.Save();
}
```

### Guarda anche

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* spazio dei nomi [GroupDocs.Watermark](../../watermarker)
* assemblea [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Inizializza una nuova istanza di[`Watermarker`](../../watermarker) classe con il flusso specificato.

```csharp
public Watermarker(Stream document)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Il flusso da cui caricare il documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Il tipo di documento fornito non è supportato. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La password fornita non è corretta. |

### Osservazioni

Ulteriori informazioni sul caricamento dei documenti [Caricamento documenti](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Esempi

Carica e salva un documento di qualsiasi formato supportato.

```csharp
// Carica un contenuto da uno stream.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Utilizza i metodi della classe Watermarker per aggiungere, cercare o rimuovere filigrane.

    // Salvare le modifiche.
    watermarker.Save(outputStream);
}
```

### Guarda anche

* class [Watermarker](../../watermarker)
* spazio dei nomi [GroupDocs.Watermark](../../watermarker)
* assemblea [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Inizializza una nuova istanza di[`Watermarker`](../../watermarker) classe con lo stream specificato e le opzioni di caricamento.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Il flusso da cui caricare il documento. |
| options | LoadOptions | Opzioni aggiuntive da utilizzare durante il caricamento di un documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Il tipo di documento fornito non è supportato. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La password fornita non è corretta. |

### Osservazioni

Ulteriori informazioni sul caricamento dei documenti [Caricamento documenti](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Esempi

Carica il documento PDF crittografato utilizzando la password

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    //...
}
```

### Guarda anche

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* spazio dei nomi [GroupDocs.Watermark](../../watermarker)
* assemblea [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Inizializza una nuova istanza di[`Watermarker`](../../watermarker) classe con lo stream e le impostazioni specificati.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Il flusso da cui caricare il documento. |
| settings | WatermarkerSettings | Impostazioni aggiuntive da utilizzare quando si lavora con il documento caricato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Il tipo di documento fornito non è supportato. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La password fornita non è corretta. |

### Osservazioni

Ulteriori informazioni sul caricamento dei documenti [Caricamento documenti](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Esempi

Imposta gli oggetti ricercabili a livello globale (per tutti i documenti che verranno caricati successivamente).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (FileStream fileStream = File.Open(file, FileMode.Open))
    using (Watermarker watermarker = new Watermarker(fileStream, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // Il codice per lavorare con le filigrane trovate va qui.
    }
}
```

### Guarda anche

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* spazio dei nomi [GroupDocs.Watermark](../../watermarker)
* assemblea [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Inizializza una nuova istanza di[`Watermarker`](../../watermarker) classe con il flusso specificato, carica le opzioni e le impostazioni.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Il flusso da cui caricare il documento. |
| options | LoadOptions | Opzioni aggiuntive da utilizzare durante il caricamento di un documento. |
| settings | WatermarkerSettings | Impostazioni aggiuntive da utilizzare quando si lavora con il documento caricato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Il tipo di documento fornito non è supportato. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La password fornita non è corretta. |

### Osservazioni

Ulteriori informazioni sul caricamento dei documenti [Caricamento documenti](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Esempi

Trova particolari frammenti di testo nel corpo/oggetto del messaggio di posta elettronica.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (FileStream fileStream = File.Open(@"D:\test.msg", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Nota, la ricerca viene eseguita solo se passi l'istanza TextSearchCriteria al metodo Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Rimuovi i frammenti di testo trovati
    watermarks.Clear();
    // Salvare le modifiche
    watermarker.Save();
}
```

### Guarda anche

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* spazio dei nomi [GroupDocs.Watermark](../../watermarker)
* assemblea [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
