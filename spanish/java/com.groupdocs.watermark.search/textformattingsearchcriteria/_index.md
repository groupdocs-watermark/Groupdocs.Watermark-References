---
title: "TextFormattingSearchCriteria"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa criterios que permiten filtrar por formato de texto."
type: docs
weight: 66
url: /es/java/com.groupdocs.watermark.search/textformattingsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class TextFormattingSearchCriteria extends SearchCriteria
```

Representa criterios que permiten filtrar por formato de texto.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

El siguiente ejemplo muestra cómo eliminar posibles marcas de agua con un formato particular
formato de texto (independientemente del tipo de documento).
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


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [TextFormattingSearchCriteria()](#TextFormattingSearchCriteria--) | Inicializa una nueva instancia de la `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)` clase. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getForegroundColorRange()](#getForegroundColorRange--) | Obtiene el rango de colores que se utilizan para filtrar marcas de agua por color de primer plano del texto. |
|
|  | [setForegroundColorRange(ColorRange value)](#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Establece el rango de colores que se utilizan para filtrar marcas de agua por color de primer plano del texto. |
|
|  | [getBackgroundColorRange()](#getBackgroundColorRange--) | Obtiene el rango de colores que se utilizan para filtrar marcas de agua por color de fondo del texto. |
|
|  | [setBackgroundColorRange(ColorRange value)](#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Establece el rango de colores que se utilizan para filtrar marcas de agua por color de fondo del texto. |
|
|  | [getFontName()](#getFontName--) | Obtiene el nombre de la fuente que se utiliza en el posible formato de texto de la marca de agua. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | Establece el nombre de la fuente que se utiliza en el posible formato de texto de la marca de agua. |
|
|  | [getMinFontSize()](#getMinFontSize--) | Obtiene el valor inicial del tamaño de la fuente. |
|
|  | [setMinFontSize(float value)](#setMinFontSize-float-) | Establece el valor inicial del tamaño de la fuente. |
|
|  | [getMaxFontSize()](#getMaxFontSize--) | Obtiene el valor final del tamaño de la fuente. |
|
|  | [setMaxFontSize(float value)](#setMaxFontSize-float-) | Establece el valor final del tamaño de la fuente. |
|
|  | [getFontBold()](#getFontBold--) | Obtiene un valor que indica si la fuente utilizada en el formato de texto de la marca de agua está en negrita. |
|
|  | [setFontBold(Boolean value)](#setFontBold-java.lang.Boolean-) | Establece un valor que indica si la fuente utilizada en el formato de texto de la marca de agua está en negrita. |
|
|  | [getFontItalic()](#getFontItalic--) | Obtiene un valor que indica si la fuente utilizada en el formato de texto de la marca de agua está en cursiva. |
|
|  | [setFontItalic(Boolean value)](#setFontItalic-java.lang.Boolean-) | Establece un valor que indica si la fuente utilizada en el formato de texto de la marca de agua está en cursiva. |
|
|  | [getFontUnderline()](#getFontUnderline--) | Obtiene un valor que indica si la fuente utilizada en el formato de texto de la marca de agua está subrayada. |
|
|  | [setFontUnderline(Boolean value)](#setFontUnderline-java.lang.Boolean-) | Establece un valor que indica si la fuente utilizada en el formato de texto de la marca de agua está subrayada. |
|
|  | [getFontStrikeout()](#getFontStrikeout--) | Obtiene un valor que indica si la fuente utilizada en el formato de texto de la marca de agua está tachada. |
|
|  | [setFontStrikeout(Boolean value)](#setFontStrikeout-java.lang.Boolean-) | Establece un valor que indica si la fuente utilizada en el formato de texto de la marca de agua está tachada. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextFormattingSearchCriteria() {#TextFormattingSearchCriteria--}
```
public TextFormattingSearchCriteria()
```


Inicializa una nueva instancia de la `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)` clase.


### getForegroundColorRange() {#getForegroundColorRange--}
```
public final ColorRange getForegroundColorRange()
```


Obtiene el rango de colores que se utilizan para filtrar marcas de agua por color de primer plano del texto.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text foreground color.

### setForegroundColorRange(ColorRange value) {#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setForegroundColorRange(ColorRange value)
```


Establece el rango de colores que se utilizan para filtrar marcas de agua por color de primer plano del texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | El rango de colores que se utilizan para filtrar marcas de agua por color de primer plano del texto. |
|

### getBackgroundColorRange() {#getBackgroundColorRange--}
```
public final ColorRange getBackgroundColorRange()
```


Obtiene el rango de colores que se utilizan para filtrar marcas de agua por color de fondo del texto.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text background color.

### setBackgroundColorRange(ColorRange value) {#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setBackgroundColorRange(ColorRange value)
```


Establece el rango de colores que se utilizan para filtrar marcas de agua por color de fondo del texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | El rango de colores que se utilizan para filtrar marcas de agua por color de fondo del texto. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Obtiene el nombre de la fuente que se utiliza en el posible formato de texto de la marca de agua.


**Returns:**
java.lang.String - El valor predeterminado es null, lo que significa que el filtro no se aplica.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Establece el nombre de la fuente que se utiliza en el posible formato de texto de la marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El valor predeterminado es null, lo que significa que el filtro no se aplica. |
|

### getMinFontSize() {#getMinFontSize--}
```
public final float getMinFontSize()
```


Obtiene el valor inicial del tamaño de la fuente.


**Returns:**
float - El valor inicial del tamaño de fuente.

### setMinFontSize(float value) {#setMinFontSize-float-}
```
public final void setMinFontSize(float value)
```


Establece el valor inicial del tamaño de la fuente.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | float | El valor inicial del tamaño de fuente. |
|

### getMaxFontSize() {#getMaxFontSize--}
```
public final float getMaxFontSize()
```


Obtiene el valor final del tamaño de la fuente.


**Returns:**
float - El valor final del tamaño de fuente.

### setMaxFontSize(float value) {#setMaxFontSize-float-}
```
public final void setMaxFontSize(float value)
```


Establece el valor final del tamaño de la fuente.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | float | El valor final del tamaño de fuente. |
|

### getFontBold() {#getFontBold--}
```
public final Boolean getFontBold()
```


Obtiene un valor que indica si la fuente utilizada en el formato de texto de la marca de agua está en negrita.


**Returns:**
java.lang.Boolean - El valor predeterminado es null, lo que significa que el filtro no se aplica.

### setFontBold(Boolean value) {#setFontBold-java.lang.Boolean-}
```
public final void setFontBold(Boolean value)
```


Establece un valor que indica si la fuente utilizada en el formato de texto de la marca de agua está en negrita.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.Boolean | El valor predeterminado es null, lo que significa que el filtro no se aplica. |
|

### getFontItalic() {#getFontItalic--}
```
public final Boolean getFontItalic()
```


Obtiene un valor que indica si la fuente utilizada en el formato de texto de la marca de agua está en cursiva.


**Returns:**
java.lang.Boolean - El valor predeterminado es null, lo que significa que el filtro no se aplica.

### setFontItalic(Boolean value) {#setFontItalic-java.lang.Boolean-}
```
public final void setFontItalic(Boolean value)
```


Establece un valor que indica si la fuente utilizada en el formato de texto de la marca de agua está en cursiva.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.Boolean | El valor predeterminado es null, lo que significa que el filtro no se aplica. |
|

### getFontUnderline() {#getFontUnderline--}
```
public final Boolean getFontUnderline()
```


Obtiene un valor que indica si la fuente utilizada en el formato de texto de la marca de agua está subrayada.


**Returns:**
java.lang.Boolean - El valor predeterminado es null, lo que significa que el filtro no se aplica.

### setFontUnderline(Boolean value) {#setFontUnderline-java.lang.Boolean-}
```
public final void setFontUnderline(Boolean value)
```


Establece un valor que indica si la fuente utilizada en el formato de texto de la marca de agua está subrayada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.Boolean | El valor predeterminado es null, lo que significa que el filtro no se aplica. |
|

### getFontStrikeout() {#getFontStrikeout--}
```
public final Boolean getFontStrikeout()
```


Obtiene un valor que indica si la fuente utilizada en el formato de texto de la marca de agua está tachada.


**Returns:**
java.lang.Boolean - El valor predeterminado es null, lo que significa que el filtro no se aplica.

### setFontStrikeout(Boolean value) {#setFontStrikeout-java.lang.Boolean-}
```
public final void setFontStrikeout(Boolean value)
```


Establece un valor que indica si la fuente utilizada en el formato de texto de la marca de agua está tachada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.Boolean | El valor predeterminado es null, lo que significa que el filtro no se aplica. |
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

