---
title: "FontNotFoundException"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "La excepción que se lanza cuando no se encuentra la fuente solicitada."
type: docs
weight: 12
url: /es/java/com.groupdocs.watermark.exceptions/fontnotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, [com.groupdocs.watermark.exceptions.WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception)
```
public class FontNotFoundException extends WatermarkException
```

La excepción que se lanza cuando no se encuentra la fuente solicitada.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [FontNotFoundException()](#FontNotFoundException--) | Inicializa una nueva instancia de la clase `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)`. |
|
|  | [FontNotFoundException(String fontName)](#FontNotFoundException-java.lang.String-) | Inicializa una nueva instancia de la clase `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` con un nombre de fuente especificado. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFontName()](#getFontName--) | Obtiene el nombre de fuente solicitado. |
|
### FontNotFoundException() {#FontNotFoundException--}
```
public FontNotFoundException()
```


Inicializa una nueva instancia de la clase `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)`.


### FontNotFoundException(String fontName) {#FontNotFoundException-java.lang.String-}
```
public FontNotFoundException(String fontName)
```


Inicializa una nueva instancia de la clase `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` con un nombre de fuente especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fontName | java.lang.String | El nombre de fuente solicitado. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Obtiene el nombre de fuente solicitado.


**Returns:**
java.lang.String - El nombre de fuente solicitado.

