---
title: "FontNotFoundException"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "L'eccezione che viene sollevata quando il font richiesto non viene trovato."
type: docs
weight: 12
url: /it/java/com.groupdocs.watermark.exceptions/fontnotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, [com.groupdocs.watermark.exceptions.WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception)
```
public class FontNotFoundException extends WatermarkException
```

L'eccezione che viene sollevata quando il font richiesto non viene trovato.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [FontNotFoundException()](#FontNotFoundException--) | Inizializza una nuova istanza della classe `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)`. |
|
|  | [FontNotFoundException(String fontName)](#FontNotFoundException-java.lang.String-) | Inizializza una nuova istanza della classe `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` con un nome di carattere specificato. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFontName()](#getFontName--) | Restituisce il nome del carattere richiesto. |
|
### FontNotFoundException() {#FontNotFoundException--}
```
public FontNotFoundException()
```


Inizializza una nuova istanza della classe `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)`.


### FontNotFoundException(String fontName) {#FontNotFoundException-java.lang.String-}
```
public FontNotFoundException(String fontName)
```


Inizializza una nuova istanza della classe `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` con un nome di carattere specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fontName | java.lang.String | Il nome del carattere richiesto. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Restituisce il nome del carattere richiesto.


**Returns:**
java.lang.String - Il nome del carattere richiesto.

