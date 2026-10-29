---
title: "ImageThumbnailSearchCriteria"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa criterios de búsqueda para encontrar imágenes en un contenido."
type: docs
weight: 33
url: /es/java/com.groupdocs.watermark.search/imagethumbnailsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageThumbnailSearchCriteria extends ImageSearchCriteria
```

Representa criterios de búsqueda para encontrar imágenes en un contenido.

<br />

*** ** * ** ***

Este criterio de búsqueda utiliza una miniatura binarizada de la imagen para calcular la similitud de imágenes.

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [ImageThumbnailSearchCriteria(String filePath)](#ImageThumbnailSearchCriteria-java.lang.String-) | Inicializa una nueva instancia de la clase `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` con una ruta de archivo especificada. |
|
|  | [ImageThumbnailSearchCriteria(InputStream stream)](#ImageThumbnailSearchCriteria-java.io.InputStream-) | Inicializa una nueva instancia de la clase `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` con un flujo especificado. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getThumbnailSize()](#getThumbnailSize--) | Obtiene el tamaño de la miniatura. |
|
|  | [setThumbnailSize(byte value)](#setThumbnailSize-byte-) | Establece el tamaño de la miniatura. |
|
### ImageThumbnailSearchCriteria(String filePath) {#ImageThumbnailSearchCriteria-java.lang.String-}
```
public ImageThumbnailSearchCriteria(String filePath)
```


Inicializa una nueva instancia de la clase `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` con una ruta de archivo especificada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta del archivo desde la cual cargar la imagen. |
|

### ImageThumbnailSearchCriteria(InputStream stream) {#ImageThumbnailSearchCriteria-java.io.InputStream-}
```
public ImageThumbnailSearchCriteria(InputStream stream)
```


Inicializa una nueva instancia de la clase `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` con un flujo especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | stream | java.io.InputStream | El flujo desde el cual cargar la imagen. |
|

### getThumbnailSize() {#getThumbnailSize--}
```
public final byte getThumbnailSize()
```


Obtiene el tamaño de la miniatura.


**Returns:**
byte - Por defecto se usará una miniatura de 32X32.

### setThumbnailSize(byte value) {#setThumbnailSize-byte-}
```
public final void setThumbnailSize(byte value)
```


Establece el tamaño de la miniatura.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | byte | Por defecto se usará una miniatura de 32X32. |
|

