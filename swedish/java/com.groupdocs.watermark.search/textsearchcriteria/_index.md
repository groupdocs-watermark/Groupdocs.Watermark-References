---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar kriterier som möjliggör filtrering efter vattenstämpelns text."
type: docs
weight: 67
url: /sv/java/com.groupdocs.watermark.search/textsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public class TextSearchCriteria extends PageSearchCriteria
```

Representerar kriterier som möjliggör filtrering efter vattenstämpelns text.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Följande exempel visar hur man hittar och tar bort vattenstämpel med hjälp av sökkriterier.
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


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [TextSearchCriteria(Pattern pattern)](#TextSearchCriteria-java.util.regex.Pattern-) | Initierar en ny instans av klassen `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` med ett specificerat reguljärt uttryck. |
|
| [TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)](#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-) |  |
|  | [TextSearchCriteria(String searchString, boolean isMatchCase)](#TextSearchCriteria-java.lang.String-boolean-) | Initierar en ny instans av klassen `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` med en söksträng och en flagga för jämförelse. |
|
|  | [TextSearchCriteria(String searchString)](#TextSearchCriteria-java.lang.String-) | Initierar en ny instans av klassen `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` med en söksträng. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPattern()](#getPattern--) | Hämtar sökmönstret. |
|
| [getPatternInternal()](#getPatternInternal--) |  |
|  | [getSkipUnreadableCharacters()](#getSkipUnreadableCharacters--) | Hämtar ett värde som indikerar att oläsliga tecken kommer att hoppas över under strängjämförelse. |
|
|  | [setSkipUnreadableCharacters(boolean value)](#setSkipUnreadableCharacters-boolean-) | Ställer in ett värde som indikerar att oläsliga tecken kommer att hoppas över under strängjämförelse. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextSearchCriteria(Pattern pattern) {#TextSearchCriteria-java.util.regex.Pattern-}
```
public TextSearchCriteria(Pattern pattern)
```


Initierar en ny instans av klassen `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` med ett specificerat reguljärt uttryck.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | mönster | java.util.regex.Pattern | Det reguljära uttrycket att matcha. |
|

### TextSearchCriteria(System.Text.RegularExpressions.Regex pattern) {#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-}
```
public TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mönster | com.aspose.ms.System.Text.RegularExpressions.Regex |  |

### TextSearchCriteria(String searchString, boolean isMatchCase) {#TextSearchCriteria-java.lang.String-boolean-}
```
public TextSearchCriteria(String searchString, boolean isMatchCase)
```


Initierar en ny instans av klassen `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` med en söksträng och en flagga för jämförelse.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | searchString | java.lang.String | Den exakta strängen att söka efter. |
|
|  | isMatchCase | boolean | `false` för att ignorera skiftläge under jämförelsen; annars `true`. |
|

### TextSearchCriteria(String searchString) {#TextSearchCriteria-java.lang.String-}
```
public TextSearchCriteria(String searchString)
```


Initierar en ny instans av klassen `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` med en söksträng.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | searchString | java.lang.String | Den exakta strängen att söka efter. |
|

### getPattern() {#getPattern--}
```
public final Pattern getPattern()
```


Hämtar sökmönstret.


**Returns:**
java.util.regex.Pattern - Det reguljära uttrycksmönstret att matcha.

### getPatternInternal() {#getPatternInternal--}
```
public final System.Text.RegularExpressions.Regex getPatternInternal()
```




**Returns:**
com.aspose.ms.System.Text.RegularExpressions.Regex
### getSkipUnreadableCharacters() {#getSkipUnreadableCharacters--}
```
public final boolean getSkipUnreadableCharacters()
```


Hämtar ett värde som indikerar att oläsliga tecken kommer att hoppas över under strängjämförelse.


**Returns:**
boolean - Ett värde som indikerar att oläsliga tecken kommer att hoppas över under strängjämförelsen.

### setSkipUnreadableCharacters(boolean value) {#setSkipUnreadableCharacters-boolean-}
```
public final void setSkipUnreadableCharacters(boolean value)
```


Ställer in ett värde som indikerar att oläsliga tecken kommer att hoppas över under strängjämförelse.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Ett värde som indikerar att oläsliga tecken kommer att hoppas över under strängjämförelsen. |
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

