---
title: "WordProcessingWatermarkPagesOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta le opzioni quando si aggiunge la filigrana alle pagine di un documento Word."
type: docs
weight: 2410
url: /it/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/
---
## WordProcessingWatermarkPagesOptions class

Rappresenta le opzioni quando si aggiunge la filigrana alle pagine di un documento Word.

```csharp
public sealed class WordProcessingWatermarkPagesOptions : WordProcessingWatermarkBaseOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WordProcessingWatermarkPagesOptions](wordprocessingwatermarkpagesoptions)() | Inizializza una nuova istanza della classe [`WordProcessingWatermarkPagesOptions`](../wordprocessingwatermarkpagesoptions). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | Ottiene o imposta il testo descrittivo (alternativo) che sarà associato a una forma. |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | Ottiene o imposta un valore di [`WordProcessingImageEffects`](../wordprocessingimageeffects) o [`WordProcessingTextEffects`](../wordprocessingtexteffects) per gli effetti da applicare al watermark. |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | Ottiene o imposta un valore che indica se la modifica della forma in Word è vietata. |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | Ottiene o imposta il tipo di blocco del watermark. |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | Ottiene o imposta il nome di una forma. |
| [PageNumbers](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/pagenumbers) { get; set; } | Ottiene o imposta i numeri di pagina a cui aggiungere il watermark. |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | Ottiene o imposta una password utilizzata per bloccare il watermark. |

### Osservazioni

**Learn more:**

* [Add watermarks to word processing documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### Esempi

Aggiungi il watermark a una pagina specifica di un documento Word.

```csharp
WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.doc", loadOptions))
{
    TextWatermark watermark = new TextWatermark("text", new Font("Arial", 42));

    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
    options.PageNumbers = new[] { 1 };

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Vedi anche

* class [WordProcessingWatermarkBaseOptions](../wordprocessingwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
