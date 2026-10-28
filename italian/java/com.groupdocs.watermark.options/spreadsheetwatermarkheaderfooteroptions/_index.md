---
title: "SpreadsheetWatermarkHeaderFooterOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le opzioni quando si aggiunge la filigrana a un'intestazione/piè di pagina Spreadsheet."
type: docs
weight: 57
url: /it/java/com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetWatermarkHeaderFooterOptions extends SpreadsheetWatermarkOptions
```

Rappresenta le opzioni quando si aggiunge la filigrana a un'intestazione/piè di pagina Spreadsheet.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Il seguente esempio dimostra come aggiungere un watermark di testo nell'intestazione del foglio di lavoro Excel.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkHeaderFooterOptions options = new SpreadsheetWatermarkHeaderFooterOptions();
>    options.setWorksheetIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [SpreadsheetWatermarkHeaderFooterOptions()](#SpreadsheetWatermarkHeaderFooterOptions--) | Inizializza una nuova istanza della classe `[SpreadsheetWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions)`. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Ottiene l'indice del foglio di lavoro a cui aggiungere la filigrana. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Imposta l'indice del foglio di lavoro a cui aggiungere la filigrana. |
|
### SpreadsheetWatermarkHeaderFooterOptions() {#SpreadsheetWatermarkHeaderFooterOptions--}
```
public SpreadsheetWatermarkHeaderFooterOptions()
```


Inizializza una nuova istanza della classe `[SpreadsheetWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions)`.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Ottiene l'indice del foglio di lavoro a cui aggiungere la filigrana.


**Returns:**
int - L'indice del foglio di lavoro a cui aggiungere la filigrana.

<br />

*** ** * ** ***

-1 means every worksheet.

<br />


### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Imposta l'indice del foglio di lavoro a cui aggiungere la filigrana.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | L'indice del foglio di lavoro a cui aggiungere la filigrana. |

<br />

*** ** * ** ***

-1 means every worksheet.

<br />

|

