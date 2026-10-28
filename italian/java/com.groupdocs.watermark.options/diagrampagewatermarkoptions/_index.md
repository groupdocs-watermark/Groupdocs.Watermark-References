---
title: "DiagramPageWatermarkOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le opzioni di aggiunta del watermark quando si aggiunge un watermark forma a una pagina specifica di un documento Visio."
type: docs
weight: 11
url: /it/java/com.groupdocs.watermark.options/diagrampagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramPageWatermarkOptions extends DiagramWatermarkOptions
```

Rappresenta le opzioni di aggiunta del watermark quando si aggiunge un watermark forma a una pagina specifica di un documento Visio.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

Il seguente esempio dimostra come aggiungere un watermark protetto alla prima pagina di un documento Visio.
>
> ````
> ```
>
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
>
>    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
>    options.setLocked(true);
>    options.setPageIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.vsdx");
>    watermarker.close();
>  
> ```
> ````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [DiagramPageWatermarkOptions()](#DiagramPageWatermarkOptions--) | Inizializza una nuova istanza della classe `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)`. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Ottiene l'indice della pagina a cui aggiungere il watermark. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Imposta l'indice della pagina a cui aggiungere il watermark. |
|
### DiagramPageWatermarkOptions() {#DiagramPageWatermarkOptions--}
```
public DiagramPageWatermarkOptions()
```


Inizializza una nuova istanza della classe `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)`.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Ottiene l'indice della pagina a cui aggiungere il watermark.


**Returns:**
int - L'indice della pagina a cui aggiungere il watermark.

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Imposta l'indice della pagina a cui aggiungere il watermark.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | L'indice della pagina a cui aggiungere il watermark. |
|

