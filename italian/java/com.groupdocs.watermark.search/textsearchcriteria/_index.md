---
title: "TextSearchCriteria"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta i criteri che consentono il filtraggio per testo del watermark."
type: docs
weight: 67
url: /it/java/com.groupdocs.watermark.search/textsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public class TextSearchCriteria extends PageSearchCriteria
```

Rappresenta i criteri che consentono il filtraggio per testo del watermark.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Il seguente esempio dimostra come trovare e rimuovere il watermark utilizzando i criteri di ricerca.
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
|  | [TextSearchCriteria(Pattern pattern)](#TextSearchCriteria-java.util.regex.Pattern-) | Inizializza una nuova istanza della classe `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` con un'espressione regolare specificata. |
|
| [TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)](#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-) |  |
|  | [TextSearchCriteria(String searchString, boolean isMatchCase)](#TextSearchCriteria-java.lang.String-boolean-) | Inizializza una nuova istanza della classe `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` con una stringa di ricerca e un flag per il confronto. |
|
|  | [TextSearchCriteria(String searchString)](#TextSearchCriteria-java.lang.String-) | Inizializza una nuova istanza della classe `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` con una stringa di ricerca. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPattern()](#getPattern--) | Restituisce il modello di ricerca. |
|
| [getPatternInternal()](#getPatternInternal--) |  |
|  | [getSkipUnreadableCharacters()](#getSkipUnreadableCharacters--) | Restituisce un valore che indica che i caratteri illeggibili saranno ignorati durante il confronto delle stringhe. |
|
|  | [setSkipUnreadableCharacters(boolean value)](#setSkipUnreadableCharacters-boolean-) | Imposta un valore che indica che i caratteri illeggibili saranno ignorati durante il confronto delle stringhe. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextSearchCriteria(Pattern pattern) {#TextSearchCriteria-java.util.regex.Pattern-}
```
public TextSearchCriteria(Pattern pattern)
```


Inizializza una nuova istanza della classe `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` con un'espressione regolare specificata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pattern | java.util.regex.Pattern | L'espressione regolare da corrispondere. |
|

### TextSearchCriteria(System.Text.RegularExpressions.Regex pattern) {#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-}
```
public TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pattern | com.aspose.ms.System.Text.RegularExpressions.Regex |  |

### TextSearchCriteria(String searchString, boolean isMatchCase) {#TextSearchCriteria-java.lang.String-boolean-}
```
public TextSearchCriteria(String searchString, boolean isMatchCase)
```


Inizializza una nuova istanza della classe `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` con una stringa di ricerca e un flag per il confronto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | searchString | java.lang.String | La stringa esatta da cercare. |
|
|  | isMatchCase | boolean | `false` per ignorare il case durante il confronto; altrimenti, `true`. |
|

### TextSearchCriteria(String searchString) {#TextSearchCriteria-java.lang.String-}
```
public TextSearchCriteria(String searchString)
```


Inizializza una nuova istanza della classe `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` con una stringa di ricerca.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | searchString | java.lang.String | La stringa esatta da cercare. |
|

### getPattern() {#getPattern--}
```
public final Pattern getPattern()
```


Restituisce il modello di ricerca.


**Returns:**
java.util.regex.Pattern - Il modello di espressione regolare da corrispondere.

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


Restituisce un valore che indica che i caratteri illeggibili saranno ignorati durante il confronto delle stringhe.


**Returns:**
boolean - Un valore che indica che i caratteri illeggibili saranno ignorati durante il confronto delle stringhe.

### setSkipUnreadableCharacters(boolean value) {#setSkipUnreadableCharacters-boolean-}
```
public final void setSkipUnreadableCharacters(boolean value)
```


Imposta un valore che indica che i caratteri illeggibili saranno ignorati durante il confronto delle stringhe.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | Un valore che indica che i caratteri illeggibili saranno ignorati durante il confronto di stringhe. |
|

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

