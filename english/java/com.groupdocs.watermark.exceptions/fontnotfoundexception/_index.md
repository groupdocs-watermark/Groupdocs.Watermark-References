---
title: FontNotFoundException
second_title: GroupDocs.Watermark for Java API Reference
description: The exception that is thrown when requested font is not found.
type: docs
weight: 12
url: /java/com.groupdocs.watermark.exceptions/fontnotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, [com.groupdocs.watermark.exceptions.WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception)
```
public class FontNotFoundException extends WatermarkException
```

The exception that is thrown when requested font is not found.
## Constructors

| Constructor | Description |
| --- | --- |
| [FontNotFoundException()](#FontNotFoundException--) | Initializes a new instance of the `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` class. |
| [FontNotFoundException(String fontName)](#FontNotFoundException-java.lang.String-) | Initializes a new instance of the `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` class with a specified font name. |
## Methods

| Method | Description |
| --- | --- |
| [getFontName()](#getFontName--) | Gets the requested font name. |
### FontNotFoundException() {#FontNotFoundException--}
```
public FontNotFoundException()
```


Initializes a new instance of the `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` class.

### FontNotFoundException(String fontName) {#FontNotFoundException-java.lang.String-}
```
public FontNotFoundException(String fontName)
```


Initializes a new instance of the `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` class with a specified font name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | The requested font name. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Gets the requested font name.

**Returns:**
java.lang.String - The requested font name.
