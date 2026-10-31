---
title: "Panoramica delle funzionalità"
linkTitle: "Features overview"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "GroupDocs.Watermark per Python via .NET aggiunge, ricerca e rimuove filigrane di testo e immagine tramite un'unica API indipendente dal formato — con posizionamento specifico per formato, modifica dell'albero dei contenuti, blocco e rasterizzazione."
type: docs
url: /it/python-net/guides/features-overview/
is_root: false
weight: 30
---


GroupDocs.Watermark per Python via .NET aggiunge, ricerca e rimuove filigrane su un'ampia gamma di [formati di documento supportati](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/). Ogni operazione segue lo stesso flusso di lavoro: apri un documento con [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/), chiama `add()`, `search()` o `remove()`, quindi `save()` il risultato nel suo formato originale. Le funzionalità di seguito possono essere combinate liberamente in un unico passaggio.

## Text and image watermarks

Aggiungi filigrane di testo o immagine stilizzate con pieno controllo su font, colore, opacità, rotazione, allineamento e dimensioni. Le filigrane immagine possono essere caricate da un file o da uno stream. Vedi [Aggiungi filigrane di testo](/watermark/python-net/guides/add-text/) e [Aggiungi filigrane di immagine](/watermark/python-net/guides/add-image/).

## Customization and tiling

Posiziona una filigrana con coordinate assolute o allineamento e margini relativi al genitore, scala in base alla pagina, ruotala e ripetila su tutta la pagina in un motivo ricorrente. Vedi [Personalizza le filigrane](/watermark/python-net/guides/customize/), [Aggiungi filigrane ripetute](/watermark/python-net/guides/adding-repeated-watermarks/), e [Aggiungi filigrane di testo](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/).

## Format-specific placement

Posiziona le filigrane utilizzando le opzioni adatte a ciascun formato — artefatti PDF, annotazioni e annotazioni solo stampa; diapositive di presentazione, master, layout e note; fogli di calcolo, sfondi e intestazioni/piè di pagina; pagine Visio; e sezioni e pagine Word bloccate. Vedi [Aggiungi filigrane ai documenti PDF](https://docs.groupdocs.com/watermark/python-net/add-watermarks-to-pdf-documents/) e gli altri argomenti di formato nella [Guida per sviluppatori](https://docs.groupdocs.com/watermark/python-net/adding-watermarks/).

## Searching, modifying, and removing

Trova le filigrane già presenti in un documento — incluse quelle aggiunte da strumenti di terze parti — per testo esatto, espressione regolare, somiglianza di immagine o formattazione del testo, e combina i criteri con `and_`/`or_`/`not_`. Una volta trovate, sostituisci il loro testo o immagine, o rimuovile. Vedi [Ricerca di filigrane](/watermark/python-net/guides/searching-watermarks/), [Modifica delle proprietà delle filigrane trovate](https://docs.groupdocs.com/watermark/python-net/modifying-found-watermark-properties/), e [Rimozione delle filigrane trovate](https://docs.groupdocs.com/watermark/python-net/removing-found-watermarks/).

## Working with existing content

`Watermarker.get_content()` espone un albero di contenuti specifico per formato così puoi ispezionare e modificare forme esistenti, XObject/artifatti/annotazioni PDF, allegati, sfondi e intestazioni/piè di pagina — e puoi aggiungere filigrana alle immagini incorporate in un documento con `get_images()`. Vedi [Adding watermark to images inside a document](https://docs.groupdocs.com/watermark/python-net/adding-watermark-to-images-inside-a-document/).

## Tamper resistance

Rendi le filigrane difficili da rimuovere bloccandole, proteggendo i documenti Word, aggiungendo annotazioni PDF solo per stampa o rasterizzando le pagine PDF in modo che la filigrana non possa essere rimossa. Vedi [Locking watermark in word processing document](https://docs.groupdocs.com/watermark/python-net/locking-watermark-in-word-processing-document/) e [Rasterize document or page](https://docs.groupdocs.com/watermark/python-net/rasterize-document-or-page/).

## Document inspection

Leggi il tipo di file, il conteggio delle pagine e le dimensioni di un documento senza modificarlo, e elenca tutti i formati di file supportati dalla libreria. Vedi [Get document info](/watermark/python-net/guides/get-document-info/) e [Get supported file formats](/watermark/python-net/guides/get-supported-file-formats/).

## On-premise

GroupDocs.Watermark per Python via .NET funziona interamente sulla tua infrastruttura — i tuoi documenti non lasciano mai il tuo ambiente. Il pacchetto è una wheel auto‑contenuta che raggruppa tutto il necessario, quindi non è necessario installare Microsoft Office, OpenOffice o un runtime separato. Vedi [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) per le piattaforme supportate e le dipendenze native.
