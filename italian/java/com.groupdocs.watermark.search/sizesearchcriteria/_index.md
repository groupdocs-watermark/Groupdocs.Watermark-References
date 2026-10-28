---
title: "SizeSearchCriteria"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta i criteri che consentono il filtraggio per dimensione del watermark."
type: docs
weight: 57
url: /it/java/com.groupdocs.watermark.search/sizesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class SizeSearchCriteria extends SearchCriteria
```

Rappresenta i criteri che consentono il filtraggio per dimensione del watermark.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Il seguente esempio dimostra come trovare e rimuovere le filigrane usando i criteri di ricerca.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("C:\\test.some_ext");
>    SizeSearchCriteria widthRange = new SizeSearchCriteria(Dimension.Width, 50, 100);
>    RotateAngleSearchCriteria rotateAngle = new RotateAngleSearchCriteria(0, 45);
>    TextSearchCriteria textCriteria = new TextSearchCriteria(Pattern.compile("^Test watermark$"));
>
>    PossibleWatermarkCollection watermarks = watermarker.search(textCriteria.and(widthRange.or(rotateAngle)));
>    watermarks.clear();
>
>    watermarker.save("C:\\modified_test.some_ext");
>    watermarker.close();
>  
> ```
> ````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [SizeSearchCriteria(int dimension, double min, double max)](#SizeSearchCriteria-int-double-double-) | Inizializza una nuova istanza della classe `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` con una dimensione specificata, un valore iniziale e un valore finale. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getMinimum()](#getMinimum--) | Restituisce il valore iniziale. |
|
|  | [getMaximum()](#getMaximum--) | Restituisce il valore finale. |
|
|  | [getDimension()](#getDimension--) | Restituisce la dimensione della filigrana da cercare. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### SizeSearchCriteria(int dimension, double min, double max) {#SizeSearchCriteria-int-double-double-}
```
public SizeSearchCriteria(int dimension, double min, double max)
```


Inizializza una nuova istanza della classe `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` con una dimensione specificata, un valore iniziale e un valore finale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | dimension | int | La dimensione `[Dimension](../../com.groupdocs.watermark.common/dimension)` di una filigrana da cercare. |
|
|  | min | double | Il valore iniziale. |
|
|  | max | double | Il valore finale. |
|

### getMinimum() {#getMinimum--}
```
public final double getMinimum()
```


Restituisce il valore iniziale.


**Returns:**
double - Il valore iniziale.

### getMaximum() {#getMaximum--}
```
public final double getMaximum()
```


Restituisce il valore finale.


**Returns:**
double - Il valore finale.

### getDimension() {#getDimension--}
```
public final int getDimension()
```


Restituisce la dimensione della filigrana da cercare.


**Returns:**
int - La dimensione del watermark da cercare.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

