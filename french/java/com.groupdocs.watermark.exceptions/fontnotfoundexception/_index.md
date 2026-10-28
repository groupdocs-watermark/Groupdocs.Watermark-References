---
title: "FontNotFoundException"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "L'exception qui est levée lorsque la police demandée n'est pas trouvée."
type: docs
weight: 12
url: /fr/java/com.groupdocs.watermark.exceptions/fontnotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, [com.groupdocs.watermark.exceptions.WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception)
```
public class FontNotFoundException extends WatermarkException
```

L'exception qui est levée lorsque la police demandée n'est pas trouvée.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [FontNotFoundException()](#FontNotFoundException--) | Initialise une nouvelle instance de la classe `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)`. |
|
|  | [FontNotFoundException(String fontName)](#FontNotFoundException-java.lang.String-) | Initialise une nouvelle instance de la classe `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` avec un nom de police spécifié. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFontName()](#getFontName--) | Obtient le nom de police demandé. |
|
### FontNotFoundException() {#FontNotFoundException--}
```
public FontNotFoundException()
```


Initialise une nouvelle instance de la classe `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)`.


### FontNotFoundException(String fontName) {#FontNotFoundException-java.lang.String-}
```
public FontNotFoundException(String fontName)
```


Initialise une nouvelle instance de la classe `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` avec un nom de police spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fontName | java.lang.String | Le nom de police demandé. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Obtient le nom de police demandé.


**Returns:**
java.lang.String - Le nom de police demandé.

