---
title: "FontNotFoundException"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "De uitzondering die wordt gegooid wanneer het gevraagde lettertype niet wordt gevonden."
type: docs
weight: 12
url: /nl/java/com.groupdocs.watermark.exceptions/fontnotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, [com.groupdocs.watermark.exceptions.WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception)
```
public class FontNotFoundException extends WatermarkException
```

De uitzondering die wordt gegooid wanneer het gevraagde lettertype niet wordt gevonden.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [FontNotFoundException()](#FontNotFoundException--) | Initialiseert een nieuw exemplaar van de `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` klasse. |
|
|  | [FontNotFoundException(String fontName)](#FontNotFoundException-java.lang.String-) | Initialiseert een nieuw exemplaar van de `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` klasse met een opgegeven lettertype‑naam. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFontName()](#getFontName--) | Haalt de gevraagde lettertype‑naam op. |
|
### FontNotFoundException() {#FontNotFoundException--}
```
public FontNotFoundException()
```


Initialiseert een nieuw exemplaar van de `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` klasse.


### FontNotFoundException(String fontName) {#FontNotFoundException-java.lang.String-}
```
public FontNotFoundException(String fontName)
```


Initialiseert een nieuw exemplaar van de `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` klasse met een opgegeven lettertype‑naam.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fontName | java.lang.String | De gevraagde lettertype‑naam. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Haalt de gevraagde lettertype‑naam op.


**Returns:**
java.lang.String - De gevraagde lettertype‑naam.

