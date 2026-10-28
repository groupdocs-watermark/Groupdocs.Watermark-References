---
title: "TextFormattingSearchCriteria"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Geeft criteria weer die filteren op tekstopmaak."
type: docs
weight: 66
url: /nl/java/com.groupdocs.watermark.search/textformattingsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class TextFormattingSearchCriteria extends SearchCriteria
```

Geeft criteria weer die filteren op tekstopmaak.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Het volgende voorbeeld toont hoe mogelijke watermerken met een specifieke
tekstopmaak (ongeacht het documenttype).
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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [TextFormattingSearchCriteria()](#TextFormattingSearchCriteria--) | Initialiseert een nieuw exemplaar van de `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)` klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getForegroundColorRange()](#getForegroundColorRange--) | Haalt het bereik van kleuren op dat wordt gebruikt om watermerken te filteren op tekst-voorgrondkleur. |
|
|  | [setForegroundColorRange(ColorRange value)](#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Stelt het bereik van kleuren in dat wordt gebruikt om watermerken te filteren op tekst-voorgrondkleur. |
|
|  | [getBackgroundColorRange()](#getBackgroundColorRange--) | Haalt het bereik van kleuren op dat wordt gebruikt om watermerken te filteren op tekst-achtergrondkleur. |
|
|  | [setBackgroundColorRange(ColorRange value)](#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Stelt het bereik van kleuren in dat wordt gebruikt om watermerken te filteren op tekst-achtergrondkleur. |
|
|  | [getFontName()](#getFontName--) | Haalt de naam van het lettertype op dat wordt gebruikt in mogelijke watermerk-tekstopmaak. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | Stelt de naam van het lettertype in dat wordt gebruikt in mogelijke watermerk-tekstopmaak. |
|
|  | [getMinFontSize()](#getMinFontSize--) | Haalt de beginwaarde van de lettergrootte op. |
|
|  | [setMinFontSize(float value)](#setMinFontSize-float-) | Stelt de beginwaarde van de lettergrootte in. |
|
|  | [getMaxFontSize()](#getMaxFontSize--) | Haalt de eindwaarde van de lettergrootte op. |
|
|  | [setMaxFontSize(float value)](#setMaxFontSize-float-) | Stelt de eindwaarde van de lettergrootte in. |
|
|  | [getFontBold()](#getFontBold--) | Haalt een waarde op die aangeeft of het lettertype dat wordt gebruikt in watermerk-tekstopmaak vetgedrukt is. |
|
|  | [setFontBold(Boolean value)](#setFontBold-java.lang.Boolean-) | Stelt een waarde in die aangeeft of het lettertype dat wordt gebruikt in watermerk-tekstopmaak vetgedrukt is. |
|
|  | [getFontItalic()](#getFontItalic--) | Haalt een waarde op die aangeeft of het lettertype dat wordt gebruikt in watermerk-tekstopmaak cursief is. |
|
|  | [setFontItalic(Boolean value)](#setFontItalic-java.lang.Boolean-) | Stelt een waarde in die aangeeft of het lettertype dat wordt gebruikt in watermerk-tekstopmaak cursief is. |
|
|  | [getFontUnderline()](#getFontUnderline--) | Haalt een waarde op die aangeeft of het lettertype dat wordt gebruikt in watermerk-tekstopmaak onderstreept is. |
|
|  | [setFontUnderline(Boolean value)](#setFontUnderline-java.lang.Boolean-) | Stelt een waarde in die aangeeft of het lettertype dat wordt gebruikt in watermerk-tekstopmaak onderstreept is. |
|
|  | [getFontStrikeout()](#getFontStrikeout--) | Haalt een waarde op die aangeeft of het lettertype dat wordt gebruikt in watermerk-tekstopmaak doorgestreept is. |
|
|  | [setFontStrikeout(Boolean value)](#setFontStrikeout-java.lang.Boolean-) | Stelt een waarde in die aangeeft of het lettertype dat wordt gebruikt in watermerk-tekstopmaak doorgestreept is. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextFormattingSearchCriteria() {#TextFormattingSearchCriteria--}
```
public TextFormattingSearchCriteria()
```


Initialiseert een nieuw exemplaar van de `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)` klasse.


### getForegroundColorRange() {#getForegroundColorRange--}
```
public final ColorRange getForegroundColorRange()
```


Haalt het bereik van kleuren op dat wordt gebruikt om watermerken te filteren op tekst-voorgrondkleur.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text foreground color.

### setForegroundColorRange(ColorRange value) {#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setForegroundColorRange(ColorRange value)
```


Stelt het bereik van kleuren in dat wordt gebruikt om watermerken te filteren op tekst-voorgrondkleur.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | Het bereik van kleuren dat wordt gebruikt om watermerken te filteren op tekst-voorgrondkleur. |
|

### getBackgroundColorRange() {#getBackgroundColorRange--}
```
public final ColorRange getBackgroundColorRange()
```


Haalt het bereik van kleuren op dat wordt gebruikt om watermerken te filteren op tekst-achtergrondkleur.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text background color.

### setBackgroundColorRange(ColorRange value) {#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setBackgroundColorRange(ColorRange value)
```


Stelt het bereik van kleuren in dat wordt gebruikt om watermerken te filteren op tekst-achtergrondkleur.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | Het bereik van kleuren dat wordt gebruikt om watermerken te filteren op tekst-achtergrondkleur. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Haalt de naam van het lettertype op dat wordt gebruikt in mogelijke watermerk-tekstopmaak.


**Returns:**
java.lang.String - De standaardwaarde is null, wat betekent dat het filter niet wordt toegepast.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Stelt de naam van het lettertype in dat wordt gebruikt in mogelijke watermerk-tekstopmaak.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De standaardwaarde is null, wat betekent dat het filter niet wordt toegepast. |
|

### getMinFontSize() {#getMinFontSize--}
```
public final float getMinFontSize()
```


Haalt de beginwaarde van de lettergrootte op.


**Returns:**
float - De beginnende waarde van de lettergrootte.

### setMinFontSize(float value) {#setMinFontSize-float-}
```
public final void setMinFontSize(float value)
```


Stelt de beginwaarde van de lettergrootte in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | float | De beginnende waarde van de lettergrootte. |
|

### getMaxFontSize() {#getMaxFontSize--}
```
public final float getMaxFontSize()
```


Haalt de eindwaarde van de lettergrootte op.


**Returns:**
float - De eindwaarde van de lettergrootte.

### setMaxFontSize(float value) {#setMaxFontSize-float-}
```
public final void setMaxFontSize(float value)
```


Stelt de eindwaarde van de lettergrootte in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | float | De eindwaarde van de lettergrootte. |
|

### getFontBold() {#getFontBold--}
```
public final Boolean getFontBold()
```


Haalt een waarde op die aangeeft of het lettertype dat wordt gebruikt in watermerk-tekstopmaak vetgedrukt is.


**Returns:**
java.lang.Boolean - De standaardwaarde is null, wat betekent dat het filter niet wordt toegepast.

### setFontBold(Boolean value) {#setFontBold-java.lang.Boolean-}
```
public final void setFontBold(Boolean value)
```


Stelt een waarde in die aangeeft of het lettertype dat wordt gebruikt in watermerk-tekstopmaak vetgedrukt is.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.Boolean | De standaardwaarde is null, wat betekent dat het filter niet wordt toegepast. |
|

### getFontItalic() {#getFontItalic--}
```
public final Boolean getFontItalic()
```


Haalt een waarde op die aangeeft of het lettertype dat wordt gebruikt in watermerk-tekstopmaak cursief is.


**Returns:**
java.lang.Boolean - De standaardwaarde is null, wat betekent dat het filter niet wordt toegepast.

### setFontItalic(Boolean value) {#setFontItalic-java.lang.Boolean-}
```
public final void setFontItalic(Boolean value)
```


Stelt een waarde in die aangeeft of het lettertype dat wordt gebruikt in watermerk-tekstopmaak cursief is.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.Boolean | De standaardwaarde is null, wat betekent dat het filter niet wordt toegepast. |
|

### getFontUnderline() {#getFontUnderline--}
```
public final Boolean getFontUnderline()
```


Haalt een waarde op die aangeeft of het lettertype dat wordt gebruikt in watermerk-tekstopmaak onderstreept is.


**Returns:**
java.lang.Boolean - De standaardwaarde is null, wat betekent dat het filter niet wordt toegepast.

### setFontUnderline(Boolean value) {#setFontUnderline-java.lang.Boolean-}
```
public final void setFontUnderline(Boolean value)
```


Stelt een waarde in die aangeeft of het lettertype dat wordt gebruikt in watermerk-tekstopmaak onderstreept is.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.Boolean | De standaardwaarde is null, wat betekent dat het filter niet wordt toegepast. |
|

### getFontStrikeout() {#getFontStrikeout--}
```
public final Boolean getFontStrikeout()
```


Haalt een waarde op die aangeeft of het lettertype dat wordt gebruikt in watermerk-tekstopmaak doorgestreept is.


**Returns:**
java.lang.Boolean - De standaardwaarde is null, wat betekent dat het filter niet wordt toegepast.

### setFontStrikeout(Boolean value) {#setFontStrikeout-java.lang.Boolean-}
```
public final void setFontStrikeout(Boolean value)
```


Stelt een waarde in die aangeeft of het lettertype dat wordt gebruikt in watermerk-tekstopmaak doorgestreept is.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.Boolean | De standaardwaarde is null, wat betekent dat het filter niet wordt toegepast. |
|

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

