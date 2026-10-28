---
title: "WordProcessingWatermarkHeaderFooterOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le opzioni quando si aggiunge la filigrana all'intestazione/piè di pagina di una sezione Word."
type: docs
weight: 74
url: /it/java/com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkHeaderFooterOptions extends WordProcessingWatermarkBaseOptions
```

Rappresenta le opzioni quando si aggiunge la filigrana all'intestazione/piè di pagina di una sezione Word.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WordProcessingWatermarkHeaderFooterOptions()](#WordProcessingWatermarkHeaderFooterOptions--) | Inizializza una nuova istanza della classe `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)`. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | Ottiene l'indice di una sezione a cui aggiungere il watermark. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | Imposta l'indice di una sezione a cui aggiungere il watermark. |
|
|  | [getHeaderFooterType()](#getHeaderFooterType--) | Ottiene il valore che identifica il tipo di intestazione o piè di pagina a cui aggiungere il watermark. |
|
|  | [setHeaderFooterType(int value)](#setHeaderFooterType-int-) | Imposta il valore che identifica il tipo di intestazione o piè di pagina a cui aggiungere la filigrana. |
|
### WordProcessingWatermarkHeaderFooterOptions() {#WordProcessingWatermarkHeaderFooterOptions--}
```
public WordProcessingWatermarkHeaderFooterOptions()
```


Inizializza una nuova istanza della classe `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)`.


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


Ottiene l'indice di una sezione a cui aggiungere il watermark.


**Returns:**
int - L'indice di una sezione a cui aggiungere la filigrana.

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


Imposta l'indice di una sezione a cui aggiungere il watermark.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | L'indice di una sezione a cui aggiungere la filigrana. |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


Ottiene il valore che identifica il tipo di intestazione o piè di pagina a cui aggiungere il watermark.


**Returns:**
int - Il valore di tipo `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` che identifica il tipo di intestazione o piè di pagina a cui aggiungere la filigrana.

### setHeaderFooterType(int value) {#setHeaderFooterType-int-}
```
public final void setHeaderFooterType(int value)
```


Imposta il valore che identifica il tipo di intestazione o piè di pagina a cui aggiungere la filigrana.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | int | Il valore di tipo `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` che identifica il tipo di intestazione o piè di pagina a cui aggiungere la filigrana. |
|

