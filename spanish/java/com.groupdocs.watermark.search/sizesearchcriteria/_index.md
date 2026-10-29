---
title: "SizeSearchCriteria"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa criterios que permiten filtrar por tamaño de la marca de agua."
type: docs
weight: 57
url: /es/java/com.groupdocs.watermark.search/sizesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class SizeSearchCriteria extends SearchCriteria
```

Representa criterios que permiten filtrar por tamaño de la marca de agua.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

El siguiente ejemplo muestra cómo encontrar y eliminar marcas de agua usando criterios de búsqueda.
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
|  | [SizeSearchCriteria(int dimension, double min, double max)](#SizeSearchCriteria-int-double-double-) | Inicializa una nueva instancia de la clase `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` con una dimensión especificada, un valor inicial y un valor final. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getMinimum()](#getMinimum--) | Obtiene el valor inicial. |
|
|  | [getMaximum()](#getMaximum--) | Obtiene el valor final. |
|
|  | [getDimension()](#getDimension--) | Obtiene la dimensión de la marca de agua por la cual buscar. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### SizeSearchCriteria(int dimension, double min, double max) {#SizeSearchCriteria-int-double-double-}
```
public SizeSearchCriteria(int dimension, double min, double max)
```


Inicializa una nueva instancia de la clase `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` con una dimensión especificada, un valor inicial y un valor final.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | dimension | int | La dimensión `[Dimension](../../com.groupdocs.watermark.common/dimension)` de una marca de agua por la cual buscar. |
|
|  | min | double | El valor inicial. |
|
|  | max | double | El valor final. |
|

### getMinimum() {#getMinimum--}
```
public final double getMinimum()
```


Obtiene el valor inicial.


**Returns:**
double - El valor inicial.

### getMaximum() {#getMaximum--}
```
public final double getMaximum()
```


Obtiene el valor final.


**Returns:**
double - El valor final.

### getDimension() {#getDimension--}
```
public final int getDimension()
```


Obtiene la dimensión de la marca de agua por la cual buscar.


**Returns:**
int - La dimensión de la marca de agua por la que buscar.

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

