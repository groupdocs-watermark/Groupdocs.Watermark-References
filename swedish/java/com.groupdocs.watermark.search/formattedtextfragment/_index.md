---
title: "FormattedTextFragment"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Tillhandahåller en abstrakt basklass för ett fragment av formaterad text i ett innehåll."
type: docs
weight: 26
url: /sv/java/com.groupdocs.watermark.search/formattedtextfragment/
---
**Inheritance:**
java.lang.Object
```
public abstract class FormattedTextFragment
```

Tillhandahåller en abstrakt basklass för ett fragment av formaterad text i ett innehåll.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FormattedTextFragment()](#FormattedTextFragment--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getText()](#getText--) | Hämtar fragmenttexten. |
|
|  | [getFont()](#getFont--) | Hämtar teckensnittet för texten. |
|
|  | [getForegroundColor()](#getForegroundColor--) | Hämtar förgrundsfärgen för texten. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Hämtar bakgrundsfärgen för texten. |
|
### FormattedTextFragment() {#FormattedTextFragment--}
```
public FormattedTextFragment()
```




### getText() {#getText--}
```
public abstract String getText()
```


Hämtar fragmenttexten.


**Returns:**
java.lang.String - Fragmenttexten.

### getFont() {#getFont--}
```
public abstract Font getFont()
```


Hämtar teckensnittet för texten.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public abstract Color getForegroundColor()
```


Hämtar förgrundsfärgen för texten.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public abstract Color getBackgroundColor()
```


Hämtar bakgrundsfärgen för texten.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

