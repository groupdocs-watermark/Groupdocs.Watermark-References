---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Kriterien dar, die eine Filterung nach Wasserzeichentext ermöglichen."
type: docs
weight: 67
url: /de/java/com.groupdocs.watermark.search/textsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public class TextSearchCriteria extends PageSearchCriteria
```

Stellt Kriterien dar, die eine Filterung nach Wasserzeichentext ermöglichen.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Das folgende Beispiel zeigt, wie man ein Wasserzeichen mithilfe von Suchkriterien findet und entfernt.
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
|  | [TextSearchCriteria(Pattern pattern)](#TextSearchCriteria-java.util.regex.Pattern-) | Initialisiert eine neue Instanz der `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)`-Klasse mit einem angegebenen regulären Ausdruck. |
|
| [TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)](#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-) |  |
|  | [TextSearchCriteria(String searchString, boolean isMatchCase)](#TextSearchCriteria-java.lang.String-boolean-) | Initialisiert eine neue Instanz der `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)`-Klasse mit einem Suchstring und einem Vergleichs-Flag. |
|
|  | [TextSearchCriteria(String searchString)](#TextSearchCriteria-java.lang.String-) | Initialisiert eine neue Instanz der `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)`-Klasse mit einem Suchstring. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPattern()](#getPattern--) | Gibt das Suchmuster zurück. |
|
| [getPatternInternal()](#getPatternInternal--) |  |
|  | [getSkipUnreadableCharacters()](#getSkipUnreadableCharacters--) | Gibt einen Wert zurück, der angibt, dass nicht lesbare Zeichen beim String-Vergleich übersprungen werden. |
|
|  | [setSkipUnreadableCharacters(boolean value)](#setSkipUnreadableCharacters-boolean-) | Setzt einen Wert, der angibt, dass nicht lesbare Zeichen beim String-Vergleich übersprungen werden. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextSearchCriteria(Pattern pattern) {#TextSearchCriteria-java.util.regex.Pattern-}
```
public TextSearchCriteria(Pattern pattern)
```


Initialisiert eine neue Instanz der `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)`-Klasse mit einem angegebenen regulären Ausdruck.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Muster | java.util.regex.Pattern | Der reguläre Ausdruck, der übereinstimmen soll. |
|

### TextSearchCriteria(System.Text.RegularExpressions.Regex pattern) {#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-}
```
public TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Muster | com.aspose.ms.System.Text.RegularExpressions.Regex |  |

### TextSearchCriteria(String searchString, boolean isMatchCase) {#TextSearchCriteria-java.lang.String-boolean-}
```
public TextSearchCriteria(String searchString, boolean isMatchCase)
```


Initialisiert eine neue Instanz der `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)`-Klasse mit einem Suchstring und einem Vergleichs-Flag.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | searchString | java.lang.String | Der genaue zu suchende String. |
|
|  | isMatchCase | boolean | `false`, um die Groß-/Kleinschreibung beim Vergleich zu ignorieren; andernfalls `true`. |
|

### TextSearchCriteria(String searchString) {#TextSearchCriteria-java.lang.String-}
```
public TextSearchCriteria(String searchString)
```


Initialisiert eine neue Instanz der `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)`-Klasse mit einem Suchstring.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | searchString | java.lang.String | Der genaue zu suchende String. |
|

### getPattern() {#getPattern--}
```
public final Pattern getPattern()
```


Gibt das Suchmuster zurück.


**Returns:**
java.util.regex.Pattern - Das reguläre Ausdrucksmuster, das übereinstimmen soll.

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


Gibt einen Wert zurück, der angibt, dass nicht lesbare Zeichen beim String-Vergleich übersprungen werden.


**Returns:**
boolean - Ein Wert, der angibt, dass nicht lesbare Zeichen beim String-Vergleich übersprungen werden.

### setSkipUnreadableCharacters(boolean value) {#setSkipUnreadableCharacters-boolean-}
```
public final void setSkipUnreadableCharacters(boolean value)
```


Setzt einen Wert, der angibt, dass nicht lesbare Zeichen beim String-Vergleich übersprungen werden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | Ein Wert, der angibt, dass nicht lesbare Zeichen beim String-Vergleich übersprungen werden. |
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

