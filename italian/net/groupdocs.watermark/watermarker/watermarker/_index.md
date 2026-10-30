---
title: "Watermarker"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Inizializza una nuova istanza della classe Watermarkergroupdocs.watermark/watermarker con il percorso del documento specificato."
type: docs
weight: 10
url: /it/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Inizializza una nuova istanza della classe [`Watermarker`](../../watermarker) con il percorso del documento specificato.

```csharp
public Watermarker(string filePath)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file da cui caricare il documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Il tipo di documento fornito non è supportato. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La password fornita è errata. |

### Osservazioni

Scopri di più sul caricamento dei documenti: [Caricamento dei documenti](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Esempi

Carica e salva un contenuto in qualsiasi formato supportato.

```csharp
// Carica un contenuto da un file.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Utilizza i metodi della classe Watermarker per aggiungere, cercare o rimuovere le filigrane.

    // Salva il documento.
    watermarker.Save("D:\\output.pdf");
}
```

### Vedi anche

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Inizializza una nuova istanza della classe [`Watermarker`](../../watermarker) con il percorso del documento specificato e le opzioni di caricamento.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file da cui caricare il documento. |
| opzioni | LoadOptions | Opzioni aggiuntive da utilizzare durante il caricamento di un documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Il tipo di documento fornito non è supportato. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La password fornita è errata. |

### Osservazioni

Scopri di più sul caricamento dei documenti: [Caricamento dei documenti](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Esempi

Carica un documento PDF crittografato usando la password.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### Vedi anche

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Inizializza una nuova istanza della classe [`Watermarker`](../../watermarker) con il percorso del documento specificato e le impostazioni.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file da cui caricare il documento. |
| impostazioni | WatermarkerSettings | Impostazioni aggiuntive da utilizzare durante la lavorazione del documento caricato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Il tipo di documento fornito non è supportato. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La password fornita è errata. |

### Osservazioni

Scopri di più sul caricamento dei documenti: [Caricamento dei documenti](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

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

### Vedi anche

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Inizializza una nuova istanza della classe [`Watermarker`](../../watermarker) con il percorso del documento specificato, le opzioni di caricamento e le impostazioni.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file da cui caricare il documento. |
| opzioni | LoadOptions | Opzioni aggiuntive da utilizzare durante il caricamento di un documento. |
| impostazioni | WatermarkerSettings | Impostazioni aggiuntive da utilizzare durante la lavorazione del documento caricato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Il tipo di documento fornito non è supportato. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La password fornita è errata. |

### Osservazioni

Scopri di più sul caricamento dei documenti: [Caricamento dei documenti](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Esempi

Trova particolari frammenti di testo nel corpo/oggetto del messaggio email.

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
    // Nota, la ricerca viene eseguita solo se si passa un'istanza di TextSearchCriteria al metodo Search.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Rimuovi i frammenti di testo trovati
    watermarks.Clear();
    // Salva le modifiche
    watermarker.Save();
}
```

### Vedi anche

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Inizializza una nuova istanza della classe [`Watermarker`](../../watermarker) con lo stream specificato.

```csharp
public Watermarker(Stream document)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| documento | Stream | Lo stream da cui caricare il documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Il tipo di documento fornito non è supportato. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La password fornita è errata. |

### Osservazioni

Scopri di più sul caricamento dei documenti [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Esempi

Carica e salva un documento in qualsiasi formato supportato.

```csharp
// Carica un contenuto da uno stream.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Utilizza i metodi della classe Watermarker per aggiungere, cercare o rimuovere le filigrane.

    // Salva le modifiche.
    watermarker.Save(outputStream);
}
```

### Vedi anche

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Inizializza una nuova istanza della classe [`Watermarker`](../../watermarker) con lo stream specificato e le opzioni di caricamento.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| documento | Stream | Lo stream da cui caricare il documento. |
| opzioni | LoadOptions | Opzioni aggiuntive da utilizzare durante il caricamento di un documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Il tipo di documento fornito non è supportato. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La password fornita è errata. |

### Osservazioni

Scopri di più sul caricamento dei documenti [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Esempi

Carica un documento PDF crittografato usando la password

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### Vedi anche

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Inizializza una nuova istanza della classe [`Watermarker`](../../watermarker) con lo stream specificato e le impostazioni.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| documento | Stream | Lo stream da cui caricare il documento. |
| impostazioni | WatermarkerSettings | Impostazioni aggiuntive da utilizzare durante la lavorazione del documento caricato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Il tipo di documento fornito non è supportato. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La password fornita è errata. |

### Osservazioni

Scopri di più sul caricamento dei documenti [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

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

### Vedi anche

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Inizializza una nuova istanza della classe [`Watermarker`](../../watermarker) con lo stream specificato, le opzioni di caricamento e le impostazioni.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| documento | Stream | Lo stream da cui caricare il documento. |
| opzioni | LoadOptions | Opzioni aggiuntive da utilizzare durante il caricamento di un documento. |
| impostazioni | WatermarkerSettings | Impostazioni aggiuntive da utilizzare durante la lavorazione del documento caricato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Il tipo di documento fornito non è supportato. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La password fornita è errata. |

### Osservazioni

Scopri di più sul caricamento dei documenti [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Esempi

Trova particolari frammenti di testo nel corpo/oggetto del messaggio email.

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
    // Nota, la ricerca viene eseguita solo se si passa un'istanza di TextSearchCriteria al metodo Search.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Rimuovi i frammenti di testo trovati
    watermarks.Clear();
    // Salva le modifiche
    watermarker.Save();
}
```

### Vedi anche

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
