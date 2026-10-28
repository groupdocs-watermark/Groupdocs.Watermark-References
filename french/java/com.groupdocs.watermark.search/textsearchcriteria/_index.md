---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les critères permettant de filtrer par texte du filigrane."
type: docs
weight: 67
url: /fr/java/com.groupdocs.watermark.search/textsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public class TextSearchCriteria extends PageSearchCriteria
```

Représente les critères permettant de filtrer par texte du filigrane.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

L'exemple suivant montre comment trouver et supprimer le filigrane en utilisant des critères de recherche.
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


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [TextSearchCriteria(Pattern pattern)](#TextSearchCriteria-java.util.regex.Pattern-) | Initialise une nouvelle instance de la classe `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` avec une expression régulière spécifiée. |
|
| [TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)](#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-) |  |
|  | [TextSearchCriteria(String searchString, boolean isMatchCase)](#TextSearchCriteria-java.lang.String-boolean-) | Initialise une nouvelle instance de la classe `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` avec une chaîne de recherche et un indicateur pour la comparaison. |
|
|  | [TextSearchCriteria(String searchString)](#TextSearchCriteria-java.lang.String-) | Initialise une nouvelle instance de la classe `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` avec une chaîne de recherche. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPattern()](#getPattern--) | Obtient le modèle de recherche. |
|
| [getPatternInternal()](#getPatternInternal--) |  |
|  | [getSkipUnreadableCharacters()](#getSkipUnreadableCharacters--) | Obtient une valeur indiquant que les caractères illisibles seront ignorés lors de la comparaison de chaînes. |
|
|  | [setSkipUnreadableCharacters(boolean value)](#setSkipUnreadableCharacters-boolean-) | Définit une valeur indiquant que les caractères illisibles seront ignorés lors de la comparaison de chaînes. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextSearchCriteria(Pattern pattern) {#TextSearchCriteria-java.util.regex.Pattern-}
```
public TextSearchCriteria(Pattern pattern)
```


Initialise une nouvelle instance de la classe `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` avec une expression régulière spécifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | pattern | java.util.regex.Pattern | L'expression régulière à correspondre. |
|

### TextSearchCriteria(System.Text.RegularExpressions.Regex pattern) {#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-}
```
public TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pattern | com.aspose.ms.System.Text.RegularExpressions.Regex |  |

### TextSearchCriteria(String searchString, boolean isMatchCase) {#TextSearchCriteria-java.lang.String-boolean-}
```
public TextSearchCriteria(String searchString, boolean isMatchCase)
```


Initialise une nouvelle instance de la classe `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` avec une chaîne de recherche et un indicateur pour la comparaison.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | searchString | java.lang.String | La chaîne exacte à rechercher. |
|
|  | isMatchCase | boolean | `false` pour ignorer la casse lors de la comparaison ; sinon, `true`. |
|

### TextSearchCriteria(String searchString) {#TextSearchCriteria-java.lang.String-}
```
public TextSearchCriteria(String searchString)
```


Initialise une nouvelle instance de la classe `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` avec une chaîne de recherche.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | searchString | java.lang.String | La chaîne exacte à rechercher. |
|

### getPattern() {#getPattern--}
```
public final Pattern getPattern()
```


Obtient le modèle de recherche.


**Returns:**
java.util.regex.Pattern - Le modèle d'expression régulière à correspondre.

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


Obtient une valeur indiquant que les caractères illisibles seront ignorés lors de la comparaison de chaînes.


**Returns:**
boolean - Une valeur indiquant que les caractères illisibles seront ignorés lors de la comparaison de chaînes.

### setSkipUnreadableCharacters(boolean value) {#setSkipUnreadableCharacters-boolean-}
```
public final void setSkipUnreadableCharacters(boolean value)
```


Définit une valeur indiquant que les caractères illisibles seront ignorés lors de la comparaison de chaînes.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | Une valeur indiquant que les caractères illisibles seront ignorés lors de la comparaison de chaînes. |
|

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

