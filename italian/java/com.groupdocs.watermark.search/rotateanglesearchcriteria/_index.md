---
title: "RotateAngleSearchCriteria"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta i criteri che consentono il filtraggio per angolo di rotazione del watermark."
type: docs
weight: 52
url: /it/java/com.groupdocs.watermark.search/rotateanglesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class RotateAngleSearchCriteria extends SearchCriteria
```

Rappresenta i criteri che consentono il filtraggio per angolo di rotazione del watermark.

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
|  | [RotateAngleSearchCriteria(double minAngle, double maxAngle)](#RotateAngleSearchCriteria-double-double-) | Inizializza una nuova istanza della classe `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)` con un angolo iniziale e un angolo finale. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getMinimumAngle()](#getMinimumAngle--) | Ottiene l'angolo iniziale in gradi. |
|
|  | [getMaximumAngle()](#getMaximumAngle--) | Ottiene l'angolo finale in gradi. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### RotateAngleSearchCriteria(double minAngle, double maxAngle) {#RotateAngleSearchCriteria-double-double-}
```
public RotateAngleSearchCriteria(double minAngle, double maxAngle)
```


Inizializza una nuova istanza della classe `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)` con un angolo iniziale e un angolo finale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | minAngle | double | L'angolo iniziale in gradi. |
|
|  | maxAngle | double | L'angolo finale in gradi. |
|

### getMinimumAngle() {#getMinimumAngle--}
```
public final double getMinimumAngle()
```


Ottiene l'angolo iniziale in gradi.


**Returns:**
double - L'angolo iniziale.

### getMaximumAngle() {#getMaximumAngle--}
```
public final double getMaximumAngle()
```


Ottiene l'angolo finale in gradi.


**Returns:**
double - L'angolo finale.

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

