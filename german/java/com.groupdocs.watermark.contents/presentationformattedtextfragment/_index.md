---
title: "PresentationFormattedTextFragment"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt ein Fragment formatierten Textes in einem PowerPoint-Dokument dar."
type: docs
weight: 82
url: /de/java/com.groupdocs.watermark.contents/presentationformattedtextfragment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public class PresentationFormattedTextFragment extends FormattedTextFragment implements IPresentationHyperlinkContainer
```

Stellt ein Fragment formatierten Textes in einem PowerPoint-Dokument dar.

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
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | Ruft den Hyperlink ab, der mit dem Text verknüpft ist. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Setzt den Hyperlink, der mit dem Text verknüpft ist. |
|
### getText() {#getText--}
```
public String getText()
```


Ruft den Fragmenttext ab.


**Returns:**
java.lang.String - Der Fragmenttext.

### getFont() {#getFont--}
```
public Font getFont()
```


Ruft die Schriftart des Textes ab.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Ruft die Vordergrundfarbe des Textes ab.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Ruft die Hintergrundfarbe des Textes ab.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Ruft den Hyperlink ab, der mit dem Text verknüpft ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | actionType | int | Die Aktion, die den Hyperlink aktiviert. |
|

**Returns:**
java.lang.String - Die URL des Hyperlinks, der bei der angegebenen Aktion aktiviert wird.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Setzt den Hyperlink, der mit dem Text verknüpft ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | actionType | int | Die Aktion, die den Hyperlink aktiviert. |
|
|  | URL | java.lang.String | Die URL des Hyperlinks. |
|

