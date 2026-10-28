---
title: "FontNotFoundException"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Die Ausnahme, die ausgelöst wird, wenn die angeforderte Schriftart nicht gefunden wird."
type: docs
weight: 12
url: /de/java/com.groupdocs.watermark.exceptions/fontnotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, [com.groupdocs.watermark.exceptions.WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception)
```
public class FontNotFoundException extends WatermarkException
```

Die Ausnahme, die ausgelöst wird, wenn die angeforderte Schriftart nicht gefunden wird.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [FontNotFoundException()](#FontNotFoundException--) | Initialisiert eine neue Instanz der `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` Klasse. |
|
|  | [FontNotFoundException(String fontName)](#FontNotFoundException-java.lang.String-) | Initialisiert eine neue Instanz der `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` Klasse mit einem angegebenen Schriftartnamen. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFontName()](#getFontName--) | Gibt den angeforderten Schriftartnamen zurück. |
|
### FontNotFoundException() {#FontNotFoundException--}
```
public FontNotFoundException()
```


Initialisiert eine neue Instanz der `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` Klasse.


### FontNotFoundException(String fontName) {#FontNotFoundException-java.lang.String-}
```
public FontNotFoundException(String fontName)
```


Initialisiert eine neue Instanz der `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` Klasse mit einem angegebenen Schriftartnamen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fontName | java.lang.String | Der angeforderte Schriftartname. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Gibt den angeforderten Schriftartnamen zurück.


**Returns:**
java.lang.String - Der angeforderte Schriftartname.

