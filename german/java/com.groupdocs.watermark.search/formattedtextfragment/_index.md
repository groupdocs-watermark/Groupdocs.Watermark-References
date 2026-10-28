---
title: "FormattedTextFragment"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine abstrakte Basisklasse für ein Fragment formatierten Textes in einem Inhalt bereit."
type: docs
weight: 26
url: /de/java/com.groupdocs.watermark.search/formattedtextfragment/
---
**Inheritance:**
java.lang.Object
```
public abstract class FormattedTextFragment
```

Stellt eine abstrakte Basisklasse für ein Fragment formatierten Textes in einem Inhalt bereit.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FormattedTextFragment()](#FormattedTextFragment--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getText()](#getText--) | Ruft den Fragmenttext ab. |
|
|  | [getFont()](#getFont--) | Ruft die Schriftart des Textes ab. |
|
|  | [getForegroundColor()](#getForegroundColor--) | Ruft die Vordergrundfarbe des Textes ab. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Ruft die Hintergrundfarbe des Textes ab. |
|
### FormattedTextFragment() {#FormattedTextFragment--}
```
public FormattedTextFragment()
```




### getText() {#getText--}
```
public abstract String getText()
```


Ruft den Fragmenttext ab.


**Returns:**
java.lang.String - Der Fragmenttext.

### getFont() {#getFont--}
```
public abstract Font getFont()
```


Ruft die Schriftart des Textes ab.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public abstract Color getForegroundColor()
```


Ruft die Vordergrundfarbe des Textes ab.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public abstract Color getBackgroundColor()
```


Ruft die Hintergrundfarbe des Textes ab.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

