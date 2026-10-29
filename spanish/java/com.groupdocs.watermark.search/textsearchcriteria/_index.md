---
title: "TextSearchCriteria"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa criterios que permiten filtrar por texto de la marca de agua."
type: docs
weight: 67
url: /es/java/com.groupdocs.watermark.search/textsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public class TextSearchCriteria extends PageSearchCriteria
```

Representa criterios que permiten filtrar por texto de la marca de agua.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

El siguiente ejemplo muestra cómo encontrar y eliminar la marca de agua usando criterios de búsqueda.
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


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [TextSearchCriteria(Pattern pattern)](#TextSearchCriteria-java.util.regex.Pattern-) | Inicializa una nueva instancia de la clase `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` con una expresión regular especificada. |
|
| [TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)](#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-) |  |
|  | [TextSearchCriteria(String searchString, boolean isMatchCase)](#TextSearchCriteria-java.lang.String-boolean-) | Inicializa una nueva instancia de la clase `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` con una cadena de búsqueda y una bandera para la comparación. |
|
|  | [TextSearchCriteria(String searchString)](#TextSearchCriteria-java.lang.String-) | Inicializa una nueva instancia de la clase `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` con una cadena de búsqueda. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPattern()](#getPattern--) | Obtiene el patrón de búsqueda. |
|
| [getPatternInternal()](#getPatternInternal--) |  |
|  | [getSkipUnreadableCharacters()](#getSkipUnreadableCharacters--) | Obtiene un valor que indica que los caracteres ilegibles se omitirán durante la comparación de cadenas. |
|
|  | [setSkipUnreadableCharacters(boolean value)](#setSkipUnreadableCharacters-boolean-) | Establece un valor que indica que los caracteres ilegibles se omitirán durante la comparación de cadenas. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextSearchCriteria(Pattern pattern) {#TextSearchCriteria-java.util.regex.Pattern-}
```
public TextSearchCriteria(Pattern pattern)
```


Inicializa una nueva instancia de la clase `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` con una expresión regular especificada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | patrón | java.util.regex.Pattern | La expresión regular a coincidir. |
|

### TextSearchCriteria(System.Text.RegularExpressions.Regex pattern) {#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-}
```
public TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| patrón | com.aspose.ms.System.Text.RegularExpressions.Regex |  |

### TextSearchCriteria(String searchString, boolean isMatchCase) {#TextSearchCriteria-java.lang.String-boolean-}
```
public TextSearchCriteria(String searchString, boolean isMatchCase)
```


Inicializa una nueva instancia de la clase `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` con una cadena de búsqueda y una bandera para la comparación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | searchString | java.lang.String | La cadena exacta a buscar. |
|
|  | isMatchCase | boolean | `false` para ignorar mayúsculas y minúsculas durante la comparación; de lo contrario, `true`. |
|

### TextSearchCriteria(String searchString) {#TextSearchCriteria-java.lang.String-}
```
public TextSearchCriteria(String searchString)
```


Inicializa una nueva instancia de la clase `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` con una cadena de búsqueda.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | searchString | java.lang.String | La cadena exacta a buscar. |
|

### getPattern() {#getPattern--}
```
public final Pattern getPattern()
```


Obtiene el patrón de búsqueda.


**Returns:**
java.util.regex.Pattern - El patrón de expresión regular a coincidir.

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


Obtiene un valor que indica que los caracteres ilegibles se omitirán durante la comparación de cadenas.


**Returns:**
boolean - Un valor que indica que los caracteres ilegibles se omitirán durante la comparación de cadenas.

### setSkipUnreadableCharacters(boolean value) {#setSkipUnreadableCharacters-boolean-}
```
public final void setSkipUnreadableCharacters(boolean value)
```


Establece un valor que indica que los caracteres ilegibles se omitirán durante la comparación de cadenas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | Un valor que indica que los caracteres ilegibles se omitirán durante la comparación de cadenas. |
|

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

