---
title: "TextFormattingSearchCriteria"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les critères permettant de filtrer par mise en forme du texte."
type: docs
weight: 66
url: /fr/java/com.groupdocs.watermark.search/textformattingsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class TextFormattingSearchCriteria extends SearchCriteria
```

Représente les critères permettant de filtrer par mise en forme du texte.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

L'exemple suivant montre comment supprimer les filigranes possibles avec un particulier
formatage de texte (indépendamment du type de document).
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


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [TextFormattingSearchCriteria()](#TextFormattingSearchCriteria--) | Initialise une nouvelle instance de la classe `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)`. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getForegroundColorRange()](#getForegroundColorRange--) | Obtient la plage de couleurs utilisée pour filtrer les filigranes par couleur de premier plan du texte. |
|
|  | [setForegroundColorRange(ColorRange value)](#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Définit la plage de couleurs utilisée pour filtrer les filigranes par couleur de premier plan du texte. |
|
|  | [getBackgroundColorRange()](#getBackgroundColorRange--) | Obtient la plage de couleurs utilisée pour filtrer les filigranes par couleur d'arrière-plan du texte. |
|
|  | [setBackgroundColorRange(ColorRange value)](#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Définit la plage de couleurs utilisée pour filtrer les filigranes par couleur d'arrière-plan du texte. |
|
|  | [getFontName()](#getFontName--) | Obtient le nom de la police utilisée dans le formatage de texte des filigranes possibles. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | Définit le nom de la police utilisée dans le formatage de texte des filigranes possibles. |
|
|  | [getMinFontSize()](#getMinFontSize--) | Obtient la valeur de départ de la taille de police. |
|
|  | [setMinFontSize(float value)](#setMinFontSize-float-) | Définit la valeur de départ de la taille de police. |
|
|  | [getMaxFontSize()](#getMaxFontSize--) | Obtient la valeur finale de la taille de police. |
|
|  | [setMaxFontSize(float value)](#setMaxFontSize-float-) | Définit la valeur finale de la taille de police. |
|
|  | [getFontBold()](#getFontBold--) | Obtient une valeur indiquant si la police utilisée dans le formatage de texte du filigrane est en gras. |
|
|  | [setFontBold(Boolean value)](#setFontBold-java.lang.Boolean-) | Définit une valeur indiquant si la police utilisée dans le formatage de texte du filigrane est en gras. |
|
|  | [getFontItalic()](#getFontItalic--) | Obtient une valeur indiquant si la police utilisée dans le formatage de texte du filigrane est en italique. |
|
|  | [setFontItalic(Boolean value)](#setFontItalic-java.lang.Boolean-) | Définit une valeur indiquant si la police utilisée dans le formatage de texte du filigrane est en italique. |
|
|  | [getFontUnderline()](#getFontUnderline--) | Obtient une valeur indiquant si la police utilisée dans le formatage de texte du filigrane est soulignée. |
|
|  | [setFontUnderline(Boolean value)](#setFontUnderline-java.lang.Boolean-) | Définit une valeur indiquant si la police utilisée dans le formatage de texte du filigrane est soulignée. |
|
|  | [getFontStrikeout()](#getFontStrikeout--) | Obtient une valeur indiquant si la police utilisée dans le formatage de texte du filigrane est barrée. |
|
|  | [setFontStrikeout(Boolean value)](#setFontStrikeout-java.lang.Boolean-) | Définit une valeur indiquant si la police utilisée dans le formatage de texte du filigrane est barrée. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextFormattingSearchCriteria() {#TextFormattingSearchCriteria--}
```
public TextFormattingSearchCriteria()
```


Initialise une nouvelle instance de la classe `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)`.


### getForegroundColorRange() {#getForegroundColorRange--}
```
public final ColorRange getForegroundColorRange()
```


Obtient la plage de couleurs utilisée pour filtrer les filigranes par couleur de premier plan du texte.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text foreground color.

### setForegroundColorRange(ColorRange value) {#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setForegroundColorRange(ColorRange value)
```


Définit la plage de couleurs utilisée pour filtrer les filigranes par couleur de premier plan du texte.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | La plage de couleurs utilisée pour filtrer les filigranes par couleur de premier plan du texte. |
|

### getBackgroundColorRange() {#getBackgroundColorRange--}
```
public final ColorRange getBackgroundColorRange()
```


Obtient la plage de couleurs utilisée pour filtrer les filigranes par couleur d'arrière-plan du texte.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text background color.

### setBackgroundColorRange(ColorRange value) {#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setBackgroundColorRange(ColorRange value)
```


Définit la plage de couleurs utilisée pour filtrer les filigranes par couleur d'arrière-plan du texte.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | La plage de couleurs utilisée pour filtrer les filigranes par couleur d'arrière-plan du texte. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Obtient le nom de la police utilisée dans le formatage de texte des filigranes possibles.


**Returns:**
java.lang.String - La valeur par défaut est null, ce qui signifie que le filtre n'est pas appliqué.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Définit le nom de la police utilisée dans le formatage de texte des filigranes possibles.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | La valeur par défaut est null, ce qui signifie que le filtre n'est pas appliqué. |
|

### getMinFontSize() {#getMinFontSize--}
```
public final float getMinFontSize()
```


Obtient la valeur de départ de la taille de police.


**Returns:**
float - La valeur de départ de la taille de police.

### setMinFontSize(float value) {#setMinFontSize-float-}
```
public final void setMinFontSize(float value)
```


Définit la valeur de départ de la taille de police.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | float | La valeur de départ de la taille de police. |
|

### getMaxFontSize() {#getMaxFontSize--}
```
public final float getMaxFontSize()
```


Obtient la valeur finale de la taille de police.


**Returns:**
float - La valeur finale de la taille de police.

### setMaxFontSize(float value) {#setMaxFontSize-float-}
```
public final void setMaxFontSize(float value)
```


Définit la valeur finale de la taille de police.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | float | La valeur finale de la taille de police. |
|

### getFontBold() {#getFontBold--}
```
public final Boolean getFontBold()
```


Obtient une valeur indiquant si la police utilisée dans le formatage de texte du filigrane est en gras.


**Returns:**
java.lang.Boolean - La valeur par défaut est null, ce qui signifie que le filtre n'est pas appliqué.

### setFontBold(Boolean value) {#setFontBold-java.lang.Boolean-}
```
public final void setFontBold(Boolean value)
```


Définit une valeur indiquant si la police utilisée dans le formatage de texte du filigrane est en gras.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.Boolean | La valeur par défaut est null, ce qui signifie que le filtre n'est pas appliqué. |
|

### getFontItalic() {#getFontItalic--}
```
public final Boolean getFontItalic()
```


Obtient une valeur indiquant si la police utilisée dans le formatage de texte du filigrane est en italique.


**Returns:**
java.lang.Boolean - La valeur par défaut est null, ce qui signifie que le filtre n'est pas appliqué.

### setFontItalic(Boolean value) {#setFontItalic-java.lang.Boolean-}
```
public final void setFontItalic(Boolean value)
```


Définit une valeur indiquant si la police utilisée dans le formatage de texte du filigrane est en italique.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.Boolean | La valeur par défaut est null, ce qui signifie que le filtre n'est pas appliqué. |
|

### getFontUnderline() {#getFontUnderline--}
```
public final Boolean getFontUnderline()
```


Obtient une valeur indiquant si la police utilisée dans le formatage de texte du filigrane est soulignée.


**Returns:**
java.lang.Boolean - La valeur par défaut est null, ce qui signifie que le filtre n'est pas appliqué.

### setFontUnderline(Boolean value) {#setFontUnderline-java.lang.Boolean-}
```
public final void setFontUnderline(Boolean value)
```


Définit une valeur indiquant si la police utilisée dans le formatage de texte du filigrane est soulignée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.Boolean | La valeur par défaut est null, ce qui signifie que le filtre n'est pas appliqué. |
|

### getFontStrikeout() {#getFontStrikeout--}
```
public final Boolean getFontStrikeout()
```


Obtient une valeur indiquant si la police utilisée dans le formatage de texte du filigrane est barrée.


**Returns:**
java.lang.Boolean - La valeur par défaut est null, ce qui signifie que le filtre n'est pas appliqué.

### setFontStrikeout(Boolean value) {#setFontStrikeout-java.lang.Boolean-}
```
public final void setFontStrikeout(Boolean value)
```


Définit une valeur indiquant si la police utilisée dans le formatage de texte du filigrane est barrée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.Boolean | La valeur par défaut est null, ce qui signifie que le filtre n'est pas appliqué. |
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

