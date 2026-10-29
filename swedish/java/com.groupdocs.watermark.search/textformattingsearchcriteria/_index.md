---
title: "TextFormattingSearchCriteria"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar kriterier som möjliggör filtrering efter textformatering."
type: docs
weight: 66
url: /sv/java/com.groupdocs.watermark.search/textformattingsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class TextFormattingSearchCriteria extends SearchCriteria
```

Representerar kriterier som möjliggör filtrering efter textformatering.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Följande exempel visar hur man tar bort möjliga vattenstämplar med en specifik
textformatering (oavsett dokumenttyp).
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


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [TextFormattingSearchCriteria()](#TextFormattingSearchCriteria--) | Initierar en ny instans av klassen `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)`. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getForegroundColorRange()](#getForegroundColorRange--) | Hämtar färgomfånget som används för att filtrera vattenstämplar efter textens förgrundsfärg. |
|
|  | [setForegroundColorRange(ColorRange value)](#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Ställer in färgomfånget som används för att filtrera vattenstämplar efter textens förgrundsfärg. |
|
|  | [getBackgroundColorRange()](#getBackgroundColorRange--) | Hämtar färgomfånget som används för att filtrera vattenstämplar efter textens bakgrundsfärg. |
|
|  | [setBackgroundColorRange(ColorRange value)](#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Ställer in färgomfånget som används för att filtrera vattenstämplar efter textens bakgrundsfärg. |
|
|  | [getFontName()](#getFontName--) | Hämtar namnet på teckensnittet som används i möjlig vattenstämpeltextformatering. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | Ställer in namnet på teckensnittet som används i möjlig vattenstämpeltextformatering. |
|
|  | [getMinFontSize()](#getMinFontSize--) | Hämtar startvärdet för teckenstorleken. |
|
|  | [setMinFontSize(float value)](#setMinFontSize-float-) | Ställer in startvärdet för teckenstorleken. |
|
|  | [getMaxFontSize()](#getMaxFontSize--) | Hämtar slutvärdet för teckenstorleken. |
|
|  | [setMaxFontSize(float value)](#setMaxFontSize-float-) | Ställer in slutvärdet för teckenstorleken. |
|
|  | [getFontBold()](#getFontBold--) | Hämtar ett värde som indikerar om teckensnittet som används i vattenstämpeltextformatering är fetstil. |
|
|  | [setFontBold(Boolean value)](#setFontBold-java.lang.Boolean-) | Ställer in ett värde som indikerar om teckensnittet som används i vattenstämpeltextformatering är fetstil. |
|
|  | [getFontItalic()](#getFontItalic--) | Hämtar ett värde som indikerar om teckensnittet som används i vattenstämpeltextformatering är kursiv. |
|
|  | [setFontItalic(Boolean value)](#setFontItalic-java.lang.Boolean-) | Ställer in ett värde som indikerar om teckensnittet som används i vattenstämpeltextformatering är kursiv. |
|
|  | [getFontUnderline()](#getFontUnderline--) | Hämtar ett värde som indikerar om teckensnittet som används i vattenstämpeltextformatering är understruket. |
|
|  | [setFontUnderline(Boolean value)](#setFontUnderline-java.lang.Boolean-) | Ställer in ett värde som indikerar om teckensnittet som används i vattenstämpeltextformatering är understruket. |
|
|  | [getFontStrikeout()](#getFontStrikeout--) | Hämtar ett värde som indikerar om teckensnittet som används i vattenstämpeltextformatering är genomstreckt. |
|
|  | [setFontStrikeout(Boolean value)](#setFontStrikeout-java.lang.Boolean-) | Ställer in ett värde som anger om teckensnittet som används i vattenstämpelns textformatering är genomstruket. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextFormattingSearchCriteria() {#TextFormattingSearchCriteria--}
```
public TextFormattingSearchCriteria()
```


Initierar en ny instans av klassen `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)`.


### getForegroundColorRange() {#getForegroundColorRange--}
```
public final ColorRange getForegroundColorRange()
```


Hämtar färgomfånget som används för att filtrera vattenstämplar efter textens förgrundsfärg.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text foreground color.

### setForegroundColorRange(ColorRange value) {#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setForegroundColorRange(ColorRange value)
```


Ställer in färgomfånget som används för att filtrera vattenstämplar efter textens förgrundsfärg.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | Det färgomfång som används för att filtrera vattenstämplar efter textens förgrundsfärg. |
|

### getBackgroundColorRange() {#getBackgroundColorRange--}
```
public final ColorRange getBackgroundColorRange()
```


Hämtar färgomfånget som används för att filtrera vattenstämplar efter textens bakgrundsfärg.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text background color.

### setBackgroundColorRange(ColorRange value) {#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setBackgroundColorRange(ColorRange value)
```


Ställer in färgomfånget som används för att filtrera vattenstämplar efter textens bakgrundsfärg.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | Det färgomfång som används för att filtrera vattenstämplar efter textens bakgrundsfärg. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Hämtar namnet på teckensnittet som används i möjlig vattenstämpeltextformatering.


**Returns:**
java.lang.String - Standardvärdet är null, vilket betyder att filtret inte tillämpas.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Ställer in namnet på teckensnittet som används i möjlig vattenstämpeltextformatering.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Standardvärdet är null, vilket betyder att filtret inte tillämpas. |
|

### getMinFontSize() {#getMinFontSize--}
```
public final float getMinFontSize()
```


Hämtar startvärdet för teckenstorleken.


**Returns:**
float - Startvärdet för teckenstorleken.

### setMinFontSize(float value) {#setMinFontSize-float-}
```
public final void setMinFontSize(float value)
```


Ställer in startvärdet för teckenstorleken.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | float | Startvärdet för teckenstorleken. |
|

### getMaxFontSize() {#getMaxFontSize--}
```
public final float getMaxFontSize()
```


Hämtar slutvärdet för teckenstorleken.


**Returns:**
float - Slutvärdet för teckenstorleken.

### setMaxFontSize(float value) {#setMaxFontSize-float-}
```
public final void setMaxFontSize(float value)
```


Ställer in slutvärdet för teckenstorleken.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | float | Slutvärdet för teckenstorleken. |
|

### getFontBold() {#getFontBold--}
```
public final Boolean getFontBold()
```


Hämtar ett värde som indikerar om teckensnittet som används i vattenstämpeltextformatering är fetstil.


**Returns:**
java.lang.Boolean - Standardvärdet är null, vilket betyder att filtret inte tillämpas.

### setFontBold(Boolean value) {#setFontBold-java.lang.Boolean-}
```
public final void setFontBold(Boolean value)
```


Ställer in ett värde som indikerar om teckensnittet som används i vattenstämpeltextformatering är fetstil.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.Boolean | Standardvärdet är null, vilket betyder att filtret inte tillämpas. |
|

### getFontItalic() {#getFontItalic--}
```
public final Boolean getFontItalic()
```


Hämtar ett värde som indikerar om teckensnittet som används i vattenstämpeltextformatering är kursiv.


**Returns:**
java.lang.Boolean - Standardvärdet är null, vilket betyder att filtret inte tillämpas.

### setFontItalic(Boolean value) {#setFontItalic-java.lang.Boolean-}
```
public final void setFontItalic(Boolean value)
```


Ställer in ett värde som indikerar om teckensnittet som används i vattenstämpeltextformatering är kursiv.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.Boolean | Standardvärdet är null, vilket betyder att filtret inte tillämpas. |
|

### getFontUnderline() {#getFontUnderline--}
```
public final Boolean getFontUnderline()
```


Hämtar ett värde som indikerar om teckensnittet som används i vattenstämpeltextformatering är understruket.


**Returns:**
java.lang.Boolean - Standardvärdet är null, vilket betyder att filtret inte tillämpas.

### setFontUnderline(Boolean value) {#setFontUnderline-java.lang.Boolean-}
```
public final void setFontUnderline(Boolean value)
```


Ställer in ett värde som indikerar om teckensnittet som används i vattenstämpeltextformatering är understruket.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.Boolean | Standardvärdet är null, vilket betyder att filtret inte tillämpas. |
|

### getFontStrikeout() {#getFontStrikeout--}
```
public final Boolean getFontStrikeout()
```


Hämtar ett värde som indikerar om teckensnittet som används i vattenstämpeltextformatering är genomstreckt.


**Returns:**
java.lang.Boolean - Standardvärdet är null, vilket betyder att filtret inte tillämpas.

### setFontStrikeout(Boolean value) {#setFontStrikeout-java.lang.Boolean-}
```
public final void setFontStrikeout(Boolean value)
```


Ställer in ett värde som anger om teckensnittet som används i vattenstämpelns textformatering är genomstruket.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.Boolean | Standardvärdet är null, vilket betyder att filtret inte tillämpas. |
|

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

