---
title: "PresentationWatermarkMasterSlideOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le opzioni quando si aggiunge una filigrana a una diapositiva master di un documento di presentazione."
type: docs
weight: 43
url: /it/java/com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkMasterSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Rappresenta le opzioni quando si aggiunge una filigrana a una diapositiva master di un documento di presentazione.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Vedi gli esempi di utilizzo in `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)`.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PresentationWatermarkMasterSlideOptions()](#PresentationWatermarkMasterSlideOptions--) | Inizializza una nuova istanza della classe `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)`. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getMasterSlideIndex()](#getMasterSlideIndex--) | Ottiene l'indice della diapositiva master a cui aggiungere la filigrana. |
|
|  | [setMasterSlideIndex(int value)](#setMasterSlideIndex-int-) | Imposta l'indice della diapositiva master a cui aggiungere la filigrana. |
|
### PresentationWatermarkMasterSlideOptions() {#PresentationWatermarkMasterSlideOptions--}
```
public PresentationWatermarkMasterSlideOptions()
```


Inizializza una nuova istanza della classe `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)`.


### getMasterSlideIndex() {#getMasterSlideIndex--}
```
public final int getMasterSlideIndex()
```


Ottiene l'indice della diapositiva master a cui aggiungere la filigrana.


**Returns:**
int - L'indice della diapositiva master a cui aggiungere la filigrana.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setMasterSlideIndex(int value) {#setMasterSlideIndex-int-}
```
public final void setMasterSlideIndex(int value)
```


Imposta l'indice della diapositiva master a cui aggiungere la filigrana.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | L'indice della diapositiva master a cui aggiungere la filigrana. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

