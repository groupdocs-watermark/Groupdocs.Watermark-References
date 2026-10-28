---
title: "FormattedTextFragment"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Biedt een abstracte basisklasse voor een fragment van opgemaakte tekst in een inhoud."
type: docs
weight: 26
url: /nl/java/com.groupdocs.watermark.search/formattedtextfragment/
---
**Inheritance:**
java.lang.Object
```
public abstract class FormattedTextFragment
```

Biedt een abstracte basisklasse voor een fragment van opgemaakte tekst in een inhoud.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FormattedTextFragment()](#FormattedTextFragment--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getText()](#getText--) | Haalt de fragmenttekst op. |
|
|  | [getFont()](#getFont--) | Haalt het lettertype van de tekst op. |
|
|  | [getForegroundColor()](#getForegroundColor--) | Haalt de voorgrondkleur van de tekst op. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Haalt de achtergrondkleur van de tekst op. |
|
### FormattedTextFragment() {#FormattedTextFragment--}
```
public FormattedTextFragment()
```




### getText() {#getText--}
```
public abstract String getText()
```


Haalt de fragmenttekst op.


**Returns:**
java.lang.String - De fragmenttekst.

### getFont() {#getFont--}
```
public abstract Font getFont()
```


Haalt het lettertype van de tekst op.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public abstract Color getForegroundColor()
```


Haalt de voorgrondkleur van de tekst op.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public abstract Color getBackgroundColor()
```


Haalt de achtergrondkleur van de tekst op.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

