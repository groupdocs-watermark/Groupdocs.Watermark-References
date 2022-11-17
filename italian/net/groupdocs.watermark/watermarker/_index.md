---
title: Watermarker
second_title: Riferimento API GroupDocs.Watermark per .NET
description: Rappresenta una classe per la gestione della filigrana in un documento.
type: docs
weight: 3060
url: /it/net/groupdocs.watermark/watermarker/
---
## Watermarker class

Rappresenta una classe per la gestione della filigrana in un documento.

```csharp
public class Watermarker : IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | Inizializza una nuova istanza di[`Watermarker`](../watermarker) classe con il flusso specificato. |
| [Watermarker](watermarker#constructor_4)(string) | Inizializza una nuova istanza di[`Watermarker`](../watermarker) classe con il percorso del documento specificato. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | Inizializza una nuova istanza di[`Watermarker`](../watermarker) classe con lo stream specificato e le opzioni di caricamento. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | Inizializza una nuova istanza di[`Watermarker`](../watermarker) classe con lo stream e le impostazioni specificati. |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | Inizializza una nuova istanza di[`Watermarker`](../watermarker)class con il percorso del documento specificato e le opzioni di caricamento. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | Inizializza una nuova istanza di[`Watermarker`](../watermarker) class con il percorso e le impostazioni del documento specificati . |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | Inizializza una nuova istanza di[`Watermarker`](../watermarker) classe con il flusso specificato, carica le opzioni e le impostazioni. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | Inizializza una nuova istanza di[`Watermarker`](../watermarker) classe con il percorso del documento specificato , caricare le opzioni e le impostazioni. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | Ottiene o imposta gli oggetti contenuto da includere in una ricerca filigrana. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | Aggiunge una filigrana al documento caricato. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | Aggiunge una filigrana al documento caricato utilizzando le opzioni filigrana. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | Elimina l'istanza corrente. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | Genera immagini di anteprima per il documento. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | Restituisce il[`Content`](../../groupdocs.watermark.contents/content) oggetto per il documento caricato. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | Recupera le informazioni sul formato del documento caricato. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | Trova tutte le immagini nel documento. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | Trova le immagini in base ai criteri di ricerca specificati. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | Rimuove la filigrana dal documento. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | Rimuove tutte le filigrane nella raccolta dal documento. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | Salva i dati del documento nel flusso sottostante. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | Salva i dati del documento nel flusso sottostante utilizzando le opzioni di salvataggio. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | Salva il documento nel flusso specificato. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | Salva il documento nella posizione file specificata. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | Salva il documento nel flusso specificato utilizzando le opzioni di salvataggio. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | Salva il documento nella posizione del file specificata utilizzando le opzioni di salvataggio. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | Cerca tutte le possibili filigrane nel documento. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | Cerca possibili filigrane in base ai criteri di ricerca specificati. |

### Esempi

Carica e salva un contenuto di qualsiasi formato supportato.

```csharp
// Carica un contenuto da un file.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Utilizza i metodi della classe Watermarker per aggiungere, cercare o rimuovere filigrane.

    // Salvare le modifiche.
    watermarker.Save("D:\\output.pdf");
}
```

### Guarda anche

* spazio dei nomi [GroupDocs.Watermark](../../groupdocs.watermark)
* assemblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
