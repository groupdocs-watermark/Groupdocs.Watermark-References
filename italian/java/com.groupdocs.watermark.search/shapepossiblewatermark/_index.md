---
title: "ShapePossibleWatermark"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta un watermark di forma in un contenuto di qualsiasi formato supportato."
type: docs
weight: 55
url: /it/java/com.groupdocs.watermark.search/shapepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark), [com.groupdocs.watermark.search.TwoDObjectPossibleWatermark](../../com.groupdocs.watermark.search/twodobjectpossiblewatermark)
```
public abstract class ShapePossibleWatermark<T> extends TwoDObjectPossibleWatermark
```

Rappresenta un watermark di forma in un contenuto di qualsiasi formato supportato.


T
: Il tipo della forma.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | Ottiene l'angolo di rotazione della forma in gradi. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Ottiene la collezione di frammenti di testo formattati della forma. |
|
|  | [getText()](#getText--) | Ottiene il testo della forma. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Imposta il testo della forma. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Ottiene l'angolo di rotazione della forma in gradi.


**Returns:**
double - L'angolo di rotazione della forma in gradi.

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Ottiene la collezione di frammenti di testo formattati della forma.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of shape.

### getText() {#getText--}
```
public String getText()
```


Ottiene il testo della forma.


**Returns:**
java.lang.String - Il testo della forma.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Imposta il testo della forma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il testo della forma. |
|

### getImageInternally() {#getImageInternally--}
```
public WatermarkableImage getImageInternally()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### remove() {#remove--}
```
public void remove()
```




