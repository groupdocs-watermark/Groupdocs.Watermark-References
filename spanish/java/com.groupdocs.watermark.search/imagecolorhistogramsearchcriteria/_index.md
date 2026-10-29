---
title: "ImageColorHistogramSearchCriteria"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa criterios de búsqueda para encontrar imágenes en un contenido."
type: docs
weight: 30
url: /es/java/com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageColorHistogramSearchCriteria extends ImageSearchCriteria
```

Representa criterios de búsqueda para encontrar imágenes en un contenido.

<br />

*** ** * ** ***

Este criterio de búsqueda utiliza histogramas de color de imagen para calcular la similitud de imágenes.

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [ImageColorHistogramSearchCriteria(String filePath)](#ImageColorHistogramSearchCriteria-java.lang.String-) | Inicializa una nueva instancia de la clase `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` con una ruta de archivo especificada. |
|
|  | [ImageColorHistogramSearchCriteria(InputStream stream)](#ImageColorHistogramSearchCriteria-java.io.InputStream-) | Inicializa una nueva instancia de la clase `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` con un flujo especificado. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getBinsCount()](#getBinsCount--) | Obtiene un recuento de bins que se usarán para construir histogramas de color. |
|
|  | [setBinsCount(byte value)](#setBinsCount-byte-) | Establece un recuento de bins que se usarán para construir histogramas de color. |
|
### ImageColorHistogramSearchCriteria(String filePath) {#ImageColorHistogramSearchCriteria-java.lang.String-}
```
public ImageColorHistogramSearchCriteria(String filePath)
```


Inicializa una nueva instancia de la clase `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` con una ruta de archivo especificada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta del archivo desde la cual cargar la imagen. |
|

### ImageColorHistogramSearchCriteria(InputStream stream) {#ImageColorHistogramSearchCriteria-java.io.InputStream-}
```
public ImageColorHistogramSearchCriteria(InputStream stream)
```


Inicializa una nueva instancia de la clase `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` con un flujo especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | stream | java.io.InputStream | El flujo desde el cual cargar la imagen. |
|

### getBinsCount() {#getBinsCount--}
```
public final byte getBinsCount()
```


Obtiene un recuento de bins que se usarán para construir histogramas de color.


**Returns:**
byte - El valor predeterminado es 10.

### setBinsCount(byte value) {#setBinsCount-byte-}
```
public final void setBinsCount(byte value)
```


Establece un recuento de bins que se usarán para construir histogramas de color.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | byte | El valor predeterminado es 10. |
|

