---
title: "PresentationContent"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta un documento PowerPoint in cui è possibile posizionare una filigrana."
type: docs
weight: 900
url: /it/net/groupdocs.watermark.contents.presentation/presentationcontent/
---
## PresentationContent class

Rappresenta un documento PowerPoint in cui è possibile posizionare una filigrana.

```csharp
public class PresentationContent : Content
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [LayoutSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/layoutslides) { get; } | Ottiene la collezione di tutte le diapositive layout di questo [`PresentationContent`](../presentationcontent). |
| [MasterHandoutSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masterhandoutslide) { get; } | Ottiene la diapositiva master handout di questo [`PresentationContent`](../presentationcontent). |
| [MasterNotesSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masternotesslide) { get; } | Ottiene la diapositiva master per tutte le diapositive delle note di questo [`PresentationContent`](../presentationcontent). |
| [MasterSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/masterslides) { get; } | Ottiene la raccolta di tutte le diapositive master di questo [`PresentationContent`](../presentationcontent). |
| [NotesSlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslideheight) { get; } | Ottiene l'altezza di una diapositiva delle note in punti. |
| [NotesSlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslidewidth) { get; } | Ottiene la larghezza di una diapositiva delle note in punti. |
| [SlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/slideheight) { get; } | Ottiene l'altezza di una diapositiva in punti. |
| [Slides](../../groupdocs.watermark.contents.presentation/presentationcontent/slides) { get; } | Ottiene la raccolta di tutte le diapositive di questo [`PresentationContent`](../presentationcontent). |
| [SlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/slidewidth) { get; } | Ottiene la larghezza di una diapositiva in punti. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/decrypt)() | Decripta il documento. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Elimina l'istanza corrente. |
| [Encrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/encrypt)(string) | Cifra il documento. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Trova tutte le immagini nel contenuto. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trova le immagini secondo i criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Trova tutte le possibili filigrane nel contenuto. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trova possibili filigrane in base ai criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Osservazioni

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)
* [Working with slide backgrounds](https://docs.groupdocs.com/display/watermarknet/Working+with+slide+backgrounds)

### Esempi

Carica e salva documenti PowerPoint di qualsiasi tipo supportato.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.ppt", loadOptions))
{
    // Usa il metodo Add per aggiungere una filigrana a una diapositiva specifica o a tutte le diapositive.

    // Salva le modifiche.
    watermarker.Save(@"D:\output.ppt");
}
```

### Vedi anche

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
