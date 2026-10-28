---
title: "FormattedTextFragment"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Fournit une classe de base abstraite pour un fragment de texte formaté dans un contenu."
type: docs
weight: 26
url: /fr/java/com.groupdocs.watermark.search/formattedtextfragment/
---
**Inheritance:**
java.lang.Object
```
public abstract class FormattedTextFragment
```

Fournit une classe de base abstraite pour un fragment de texte formaté dans un contenu.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FormattedTextFragment()](#FormattedTextFragment--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getText()](#getText--) | Obtient le texte du fragment. |
|
|  | [getFont()](#getFont--) | Obtient la police du texte. |
|
|  | [getForegroundColor()](#getForegroundColor--) | Obtient la couleur de premier plan du texte. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Obtient la couleur d'arrière-plan du texte. |
|
### FormattedTextFragment() {#FormattedTextFragment--}
```
public FormattedTextFragment()
```




### getText() {#getText--}
```
public abstract String getText()
```


Obtient le texte du fragment.


**Returns:**
java.lang.String - Le texte du fragment.

### getFont() {#getFont--}
```
public abstract Font getFont()
```


Obtient la police du texte.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public abstract Color getForegroundColor()
```


Obtient la couleur de premier plan du texte.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public abstract Color getBackgroundColor()
```


Obtient la couleur d'arrière-plan du texte.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

