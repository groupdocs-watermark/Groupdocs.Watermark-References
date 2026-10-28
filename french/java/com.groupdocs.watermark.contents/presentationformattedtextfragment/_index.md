---
title: "PresentationFormattedTextFragment"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente un fragment de texte formaté dans un document PowerPoint."
type: docs
weight: 82
url: /fr/java/com.groupdocs.watermark.contents/presentationformattedtextfragment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public class PresentationFormattedTextFragment extends FormattedTextFragment implements IPresentationHyperlinkContainer
```

Représente un fragment de texte formaté dans un document PowerPoint.

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
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | Obtient le lien hypertexte associé au texte. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Définit le lien hypertexte associé au texte. |
|
### getText() {#getText--}
```
public String getText()
```


Obtient le texte du fragment.


**Returns:**
java.lang.String - Le texte du fragment.

### getFont() {#getFont--}
```
public Font getFont()
```


Obtient la police du texte.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Obtient la couleur de premier plan du texte.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtient la couleur d'arrière-plan du texte.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Obtient le lien hypertexte associé au texte.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | actionType | int | L'action qui active le lien hypertexte. |
|

**Returns:**
java.lang.String - L'url du lien hypertexte qui est activé lors de l'action spécifiée.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Définit le lien hypertexte associé au texte.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | actionType | int | L'action qui active le lien hypertexte. |
|
|  | url | java.lang.String | L'url du lien hypertexte. |
|

