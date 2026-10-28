---
title: "SizeSearchCriteria"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Kriterien dar, die eine Filterung nach der Größe des Wasserzeichens ermöglichen."
type: docs
weight: 57
url: /de/java/com.groupdocs.watermark.search/sizesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class SizeSearchCriteria extends SearchCriteria
```

Stellt Kriterien dar, die eine Filterung nach der Größe des Wasserzeichens ermöglichen.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Das folgende Beispiel zeigt, wie man Wasserzeichen mithilfe von Suchkriterien findet und entfernt.
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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SizeSearchCriteria(int dimension, double min, double max)](#SizeSearchCriteria-int-double-double-) | Initialisiert eine neue Instanz der `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` Klasse mit einer angegebenen Dimension, einem Startwert und einem Endwert. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getMinimum()](#getMinimum--) | Gibt den Startwert zurück. |
|
|  | [getMaximum()](#getMaximum--) | Gibt den Endwert zurück. |
|
|  | [getDimension()](#getDimension--) | Gibt die Dimension des zu suchenden Wasserzeichens zurück. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### SizeSearchCriteria(int dimension, double min, double max) {#SizeSearchCriteria-int-double-double-}
```
public SizeSearchCriteria(int dimension, double min, double max)
```


Initialisiert eine neue Instanz der `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` Klasse mit einer angegebenen Dimension, einem Startwert und einem Endwert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | dimension | int | Die Dimension `[Dimension](../../com.groupdocs.watermark.common/dimension)` eines zu suchenden Wasserzeichens. |
|
|  | min | double | Der Startwert. |
|
|  | max | double | Der Endwert. |
|

### getMinimum() {#getMinimum--}
```
public final double getMinimum()
```


Gibt den Startwert zurück.


**Returns:**
double - Der Startwert.

### getMaximum() {#getMaximum--}
```
public final double getMaximum()
```


Gibt den Endwert zurück.


**Returns:**
double - Der Endwert.

### getDimension() {#getDimension--}
```
public final int getDimension()
```


Gibt die Dimension des zu suchenden Wasserzeichens zurück.


**Returns:**
int - Die Dimension des zu suchenden Wasserzeichens.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

