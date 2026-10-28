---
title: "RotateAngleSearchCriteria"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Kriterien dar, die eine Filterung nach dem Rotationswinkel des Wasserzeichens ermöglichen."
type: docs
weight: 52
url: /de/java/com.groupdocs.watermark.search/rotateanglesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class RotateAngleSearchCriteria extends SearchCriteria
```

Stellt Kriterien dar, die eine Filterung nach dem Rotationswinkel des Wasserzeichens ermöglichen.

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
|  | [RotateAngleSearchCriteria(double minAngle, double maxAngle)](#RotateAngleSearchCriteria-double-double-) | Initialisiert eine neue Instanz der `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)`-Klasse mit einem Startwinkel und einem Endwinkel. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getMinimumAngle()](#getMinimumAngle--) | Gibt den Startwinkel in Grad zurück. |
|
|  | [getMaximumAngle()](#getMaximumAngle--) | Gibt den Endwinkel in Grad zurück. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### RotateAngleSearchCriteria(double minAngle, double maxAngle) {#RotateAngleSearchCriteria-double-double-}
```
public RotateAngleSearchCriteria(double minAngle, double maxAngle)
```


Initialisiert eine neue Instanz der `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)`-Klasse mit einem Startwinkel und einem Endwinkel.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | minAngle | double | Der Startwinkel in Grad. |
|
|  | maxAngle | double | Der Endwinkel in Grad. |
|

### getMinimumAngle() {#getMinimumAngle--}
```
public final double getMinimumAngle()
```


Gibt den Startwinkel in Grad zurück.


**Returns:**
double - Der Startwinkel.

### getMaximumAngle() {#getMaximumAngle--}
```
public final double getMaximumAngle()
```


Gibt den Endwinkel in Grad zurück.


**Returns:**
double - Der Endwinkel.

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

