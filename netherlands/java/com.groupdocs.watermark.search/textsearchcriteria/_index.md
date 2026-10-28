---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Geeft criteria weer die filteren op watermerktekst."
type: docs
weight: 67
url: /nl/java/com.groupdocs.watermark.search/textsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public class TextSearchCriteria extends PageSearchCriteria
```

Geeft criteria weer die filteren op watermerktekst.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Het volgende voorbeeld laat zien hoe je een watermerk kunt vinden en verwijderen met behulp van zoekcriteria.
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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [TextSearchCriteria(Pattern pattern)](#TextSearchCriteria-java.util.regex.Pattern-) | Initialiseert een nieuw exemplaar van de `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` klasse met een opgegeven reguliere expressie. |
|
| [TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)](#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-) |  |
|  | [TextSearchCriteria(String searchString, boolean isMatchCase)](#TextSearchCriteria-java.lang.String-boolean-) | Initialiseert een nieuw exemplaar van de `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` klasse met een zoekstring en een vlag voor vergelijking. |
|
|  | [TextSearchCriteria(String searchString)](#TextSearchCriteria-java.lang.String-) | Initialiseert een nieuw exemplaar van de `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` klasse met een zoekstring. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPattern()](#getPattern--) | Haalt het zoekpatroon op. |
|
| [getPatternInternal()](#getPatternInternal--) |  |
|  | [getSkipUnreadableCharacters()](#getSkipUnreadableCharacters--) | Haalt een waarde op die aangeeft dat onleesbare tekens worden overgeslagen tijdens de tekenreeksvergelijking. |
|
|  | [setSkipUnreadableCharacters(boolean value)](#setSkipUnreadableCharacters-boolean-) | Stelt een waarde in die aangeeft dat onleesbare tekens worden overgeslagen tijdens de tekenreeksvergelijking. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextSearchCriteria(Pattern pattern) {#TextSearchCriteria-java.util.regex.Pattern-}
```
public TextSearchCriteria(Pattern pattern)
```


Initialiseert een nieuw exemplaar van de `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` klasse met een opgegeven reguliere expressie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | patroon | java.util.regex.Pattern | De reguliere expressie om te matchen. |
|

### TextSearchCriteria(System.Text.RegularExpressions.Regex pattern) {#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-}
```
public TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| patroon | com.aspose.ms.System.Text.RegularExpressions.Regex |  |

### TextSearchCriteria(String searchString, boolean isMatchCase) {#TextSearchCriteria-java.lang.String-boolean-}
```
public TextSearchCriteria(String searchString, boolean isMatchCase)
```


Initialiseert een nieuw exemplaar van de `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` klasse met een zoekstring en een vlag voor vergelijking.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | searchString | java.lang.String | De exacte tekenreeks om naar te zoeken. |
|
|  | isMatchCase | boolean | `false` om hoofdlettergevoeligheid te negeren tijdens de vergelijking; anders `true`. |
|

### TextSearchCriteria(String searchString) {#TextSearchCriteria-java.lang.String-}
```
public TextSearchCriteria(String searchString)
```


Initialiseert een nieuw exemplaar van de `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` klasse met een zoekstring.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | searchString | java.lang.String | De exacte tekenreeks om naar te zoeken. |
|

### getPattern() {#getPattern--}
```
public final Pattern getPattern()
```


Haalt het zoekpatroon op.


**Returns:**
java.util.regex.Pattern - Het reguliere expressiepatroon om te matchen.

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


Haalt een waarde op die aangeeft dat onleesbare tekens worden overgeslagen tijdens de tekenreeksvergelijking.


**Returns:**
boolean - Een waarde die aangeeft dat onleesbare tekens worden overgeslagen tijdens de tekenreeksvergelijking.

### setSkipUnreadableCharacters(boolean value) {#setSkipUnreadableCharacters-boolean-}
```
public final void setSkipUnreadableCharacters(boolean value)
```


Stelt een waarde in die aangeeft dat onleesbare tekens worden overgeslagen tijdens de tekenreeksvergelijking.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | Een waarde die aangeeft dat onleesbare tekens worden overgeslagen tijdens tekenreeksvergelijking. |
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

