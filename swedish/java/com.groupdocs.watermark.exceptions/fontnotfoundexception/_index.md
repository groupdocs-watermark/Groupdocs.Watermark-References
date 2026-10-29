---
title: "FontNotFoundException"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Undantaget som kastas när det begärda teckensnittet inte hittas."
type: docs
weight: 12
url: /sv/java/com.groupdocs.watermark.exceptions/fontnotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, [com.groupdocs.watermark.exceptions.WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception)
```
public class FontNotFoundException extends WatermarkException
```

Undantaget som kastas när det begärda teckensnittet inte hittas.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [FontNotFoundException()](#FontNotFoundException--) | Initierar en ny instans av klassen `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)`. |
|
|  | [FontNotFoundException(String fontName)](#FontNotFoundException-java.lang.String-) | Initierar en ny instans av klassen `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` med ett specificerat typsnittsnamn. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFontName()](#getFontName--) | Hämtar det begärda typsnittsnamnet. |
|
### FontNotFoundException() {#FontNotFoundException--}
```
public FontNotFoundException()
```


Initierar en ny instans av klassen `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)`.


### FontNotFoundException(String fontName) {#FontNotFoundException-java.lang.String-}
```
public FontNotFoundException(String fontName)
```


Initierar en ny instans av klassen `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` med ett specificerat typsnittsnamn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fontName | java.lang.String | Det begärda typsnittsnamnet. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Hämtar det begärda typsnittsnamnet.


**Returns:**
java.lang.String - Det begärda typsnittsnamnet.

