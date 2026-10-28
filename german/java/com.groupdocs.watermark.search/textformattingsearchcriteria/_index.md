---
title: "TextFormattingSearchCriteria"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Kriterien dar, die eine Filterung nach Textformatierung ermöglichen."
type: docs
weight: 66
url: /de/java/com.groupdocs.watermark.search/textformattingsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class TextFormattingSearchCriteria extends SearchCriteria
```

Stellt Kriterien dar, die eine Filterung nach Textformatierung ermöglichen.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Das folgende Beispiel zeigt, wie mögliche Wasserzeichen mit einem bestimmten
Textformatierung (unabhängig vom Dokumenttyp) entfernt.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.doc");
>    TextFormattingSearchCriteria criteria = new TextFormattingSearchCriteria();
>
>    criteria.setForegroundColorRange(new ColorRange());
>    criteria.getForegroundColorRange().setMinHue(-5);
>    criteria.getForegroundColorRange().setMaxHue(10);
>    criteria.getForegroundColorRange().setMinBrightness(0.01f);
>    criteria.getForegroundColorRange().setMaxBrightness(0.99f);
>    criteria.setBackgroundColorRange(new ColorRange());
>    criteria.getBackgroundColorRange().setEmpty(true);
>    criteria.setFontName("Arial");
>    criteria.setMinFontSize(19);
>    criteria.setMaxFontSize(42);
>    criteria.setFontBold(true);
>
>    PossibleWatermarkCollection watermarks = watermarker.search(criteria);
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
|  | [TextFormattingSearchCriteria()](#TextFormattingSearchCriteria--) | Initialisiert eine neue Instanz der Klasse `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)`. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getForegroundColorRange()](#getForegroundColorRange--) | Gibt den Farbbereich zurück, der verwendet wird, um Wasserzeichen nach Textvordergrundfarbe zu filtern. |
|
|  | [setForegroundColorRange(ColorRange value)](#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Legt den Farbbereich fest, der zum Filtern von Wasserzeichen nach Text-Vordergrundfarbe verwendet wird. |
|
|  | [getBackgroundColorRange()](#getBackgroundColorRange--) | Ruft den Farbbereich ab, der zum Filtern von Wasserzeichen nach Text-Hintergrundfarbe verwendet wird. |
|
|  | [setBackgroundColorRange(ColorRange value)](#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Legt den Farbbereich fest, der zum Filtern von Wasserzeichen nach Text-Hintergrundfarbe verwendet wird. |
|
|  | [getFontName()](#getFontName--) | Ruft den Namen der Schriftart ab, die bei möglicher Wasserzeichen-Textformatierung verwendet wird. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | Legt den Namen der Schriftart fest, die bei möglicher Wasserzeichen-Textformatierung verwendet wird. |
|
|  | [getMinFontSize()](#getMinFontSize--) | Ruft den Startwert der Schriftgröße ab. |
|
|  | [setMinFontSize(float value)](#setMinFontSize-float-) | Legt den Startwert der Schriftgröße fest. |
|
|  | [getMaxFontSize()](#getMaxFontSize--) | Ruft den Endwert der Schriftgröße ab. |
|
|  | [setMaxFontSize(float value)](#setMaxFontSize-float-) | Legt den Endwert der Schriftgröße fest. |
|
|  | [getFontBold()](#getFontBold--) | Ruft einen Wert ab, der angibt, ob die in der Wasserzeichen-Textformatierung verwendete Schrift fett ist. |
|
|  | [setFontBold(Boolean value)](#setFontBold-java.lang.Boolean-) | Legt einen Wert fest, der angibt, ob die in der Wasserzeichen-Textformatierung verwendete Schrift fett ist. |
|
|  | [getFontItalic()](#getFontItalic--) | Ruft einen Wert ab, der angibt, ob die in der Wasserzeichen-Textformatierung verwendete Schrift kursiv ist. |
|
|  | [setFontItalic(Boolean value)](#setFontItalic-java.lang.Boolean-) | Legt einen Wert fest, der angibt, ob die in der Wasserzeichen-Textformatierung verwendete Schrift kursiv ist. |
|
|  | [getFontUnderline()](#getFontUnderline--) | Ruft einen Wert ab, der angibt, ob die in der Wasserzeichen-Textformatierung verwendete Schrift unterstrichen ist. |
|
|  | [setFontUnderline(Boolean value)](#setFontUnderline-java.lang.Boolean-) | Legt einen Wert fest, der angibt, ob die in der Wasserzeichen-Textformatierung verwendete Schrift unterstrichen ist. |
|
|  | [getFontStrikeout()](#getFontStrikeout--) | Ruft einen Wert ab, der angibt, ob die in der Wasserzeichen-Textformatierung verwendete Schrift durchgestrichen ist. |
|
|  | [setFontStrikeout(Boolean value)](#setFontStrikeout-java.lang.Boolean-) | Legt einen Wert fest, der angibt, ob die in der Wasserzeichen-Textformatierung verwendete Schrift durchgestrichen ist. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextFormattingSearchCriteria() {#TextFormattingSearchCriteria--}
```
public TextFormattingSearchCriteria()
```


Initialisiert eine neue Instanz der Klasse `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)`.


### getForegroundColorRange() {#getForegroundColorRange--}
```
public final ColorRange getForegroundColorRange()
```


Gibt den Farbbereich zurück, der verwendet wird, um Wasserzeichen nach Textvordergrundfarbe zu filtern.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text foreground color.

### setForegroundColorRange(ColorRange value) {#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setForegroundColorRange(ColorRange value)
```


Legt den Farbbereich fest, der zum Filtern von Wasserzeichen nach Text-Vordergrundfarbe verwendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | Der Farbbereich, der zum Filtern von Wasserzeichen nach Text-Vordergrundfarbe verwendet wird. |
|

### getBackgroundColorRange() {#getBackgroundColorRange--}
```
public final ColorRange getBackgroundColorRange()
```


Ruft den Farbbereich ab, der zum Filtern von Wasserzeichen nach Text-Hintergrundfarbe verwendet wird.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text background color.

### setBackgroundColorRange(ColorRange value) {#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setBackgroundColorRange(ColorRange value)
```


Legt den Farbbereich fest, der zum Filtern von Wasserzeichen nach Text-Hintergrundfarbe verwendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | Der Farbbereich, der zum Filtern von Wasserzeichen nach Text-Hintergrundfarbe verwendet wird. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Ruft den Namen der Schriftart ab, die bei möglicher Wasserzeichen-Textformatierung verwendet wird.


**Returns:**
java.lang.String - Der Standardwert ist null, was bedeutet, dass der Filter nicht angewendet wird.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Legt den Namen der Schriftart fest, die bei möglicher Wasserzeichen-Textformatierung verwendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der Standardwert ist null, was bedeutet, dass der Filter nicht angewendet wird. |
|

### getMinFontSize() {#getMinFontSize--}
```
public final float getMinFontSize()
```


Ruft den Startwert der Schriftgröße ab.


**Returns:**
float - Der Startwert der Schriftgröße.

### setMinFontSize(float value) {#setMinFontSize-float-}
```
public final void setMinFontSize(float value)
```


Legt den Startwert der Schriftgröße fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | float | Der Startwert der Schriftgröße. |
|

### getMaxFontSize() {#getMaxFontSize--}
```
public final float getMaxFontSize()
```


Ruft den Endwert der Schriftgröße ab.


**Returns:**
float - Der Endwert der Schriftgröße.

### setMaxFontSize(float value) {#setMaxFontSize-float-}
```
public final void setMaxFontSize(float value)
```


Legt den Endwert der Schriftgröße fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | float | Der Endwert der Schriftgröße. |
|

### getFontBold() {#getFontBold--}
```
public final Boolean getFontBold()
```


Ruft einen Wert ab, der angibt, ob die in der Wasserzeichen-Textformatierung verwendete Schrift fett ist.


**Returns:**
java.lang.Boolean - Der Standardwert ist null, was bedeutet, dass der Filter nicht angewendet wird.

### setFontBold(Boolean value) {#setFontBold-java.lang.Boolean-}
```
public final void setFontBold(Boolean value)
```


Legt einen Wert fest, der angibt, ob die in der Wasserzeichen-Textformatierung verwendete Schrift fett ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.Boolean | Der Standardwert ist null, was bedeutet, dass der Filter nicht angewendet wird. |
|

### getFontItalic() {#getFontItalic--}
```
public final Boolean getFontItalic()
```


Ruft einen Wert ab, der angibt, ob die in der Wasserzeichen-Textformatierung verwendete Schrift kursiv ist.


**Returns:**
java.lang.Boolean - Der Standardwert ist null, was bedeutet, dass der Filter nicht angewendet wird.

### setFontItalic(Boolean value) {#setFontItalic-java.lang.Boolean-}
```
public final void setFontItalic(Boolean value)
```


Legt einen Wert fest, der angibt, ob die in der Wasserzeichen-Textformatierung verwendete Schrift kursiv ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.Boolean | Der Standardwert ist null, was bedeutet, dass der Filter nicht angewendet wird. |
|

### getFontUnderline() {#getFontUnderline--}
```
public final Boolean getFontUnderline()
```


Ruft einen Wert ab, der angibt, ob die in der Wasserzeichen-Textformatierung verwendete Schrift unterstrichen ist.


**Returns:**
java.lang.Boolean - Der Standardwert ist null, was bedeutet, dass der Filter nicht angewendet wird.

### setFontUnderline(Boolean value) {#setFontUnderline-java.lang.Boolean-}
```
public final void setFontUnderline(Boolean value)
```


Legt einen Wert fest, der angibt, ob die in der Wasserzeichen-Textformatierung verwendete Schrift unterstrichen ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.Boolean | Der Standardwert ist null, was bedeutet, dass der Filter nicht angewendet wird. |
|

### getFontStrikeout() {#getFontStrikeout--}
```
public final Boolean getFontStrikeout()
```


Ruft einen Wert ab, der angibt, ob die in der Wasserzeichen-Textformatierung verwendete Schrift durchgestrichen ist.


**Returns:**
java.lang.Boolean - Der Standardwert ist null, was bedeutet, dass der Filter nicht angewendet wird.

### setFontStrikeout(Boolean value) {#setFontStrikeout-java.lang.Boolean-}
```
public final void setFontStrikeout(Boolean value)
```


Legt einen Wert fest, der angibt, ob die in der Wasserzeichen-Textformatierung verwendete Schrift durchgestrichen ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.Boolean | Der Standardwert ist null, was bedeutet, dass der Filter nicht angewendet wird. |
|

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

