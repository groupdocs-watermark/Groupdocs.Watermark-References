---
title: "EmailSearchableObjects"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Especifica indicadores que representan objetos de mensaje de correo electrónico que deben incluirse en una búsqueda de marcas de agua."
type: docs
weight: 22
url: /es/java/com.groupdocs.watermark.search/emailsearchableobjects/
---
**Inheritance:**
java.lang.Object
```
public final class EmailSearchableObjects
```

Especifica indicadores que representan objetos de mensaje de correo electrónico que deben incluirse en una búsqueda de marcas de agua.

## Campos

| Campo | Descripción |
| --- | --- |
|  | [None](#None) | Especifica que no hay objetos de búsqueda. |
|
|  | [Subject](#Subject) | Buscar en el asunto del mensaje. |
|
|  | [PlainTextBody](#PlainTextBody) | Buscar en el cuerpo de texto plano del mensaje. |
|
|  | [HtmlBody](#HtmlBody) | Buscar en el cuerpo HTML del mensaje. |
|
|  | [AttachedImages](#AttachedImages) | Buscar en imágenes adjuntas. |
|
|  | [EmbeddedImages](#EmbeddedImages) | Buscar en imágenes incrustadas. |
|
|  | [All](#All) | Buscar en todos los objetos de correo electrónico. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getValues()](#getValues--) | Obtiene una matriz de todos los valores de la enumeración `[EmailSearchableObjects](../../com.groupdocs.watermark.search/emailsearchableobjects)`. |
|
### None {#None}
```
public static final int None
```


Especifica que no hay objetos de búsqueda.


### Subject {#Subject}
```
public static final int Subject
```


Buscar en el asunto del mensaje.


### PlainTextBody {#PlainTextBody}
```
public static final int PlainTextBody
```


Buscar en el cuerpo de texto plano del mensaje.


### HtmlBody {#HtmlBody}
```
public static final int HtmlBody
```


Buscar en el cuerpo HTML del mensaje.


### AttachedImages {#AttachedImages}
```
public static final int AttachedImages
```


Buscar en imágenes adjuntas.


### EmbeddedImages {#EmbeddedImages}
```
public static final int EmbeddedImages
```


Buscar en imágenes incrustadas.


### All {#All}
```
public static final int All
```


Buscar en todos los objetos de correo electrónico.


### getValues() {#getValues--}
```
public static final int[] getValues()
```


Obtiene una matriz de todos los valores de la enumeración `[EmailSearchableObjects](../../com.groupdocs.watermark.search/emailsearchableobjects)`.


**Returns:**
int[] - La matriz de todos los valores de la enumeración `[EmailSearchableObjects](../../com.groupdocs.watermark.search/emailsearchableobjects)`.

