---
title: "PresentationFormattedTextFragment"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar ett fragment av formaterad text i ett PowerPoint-dokument."
type: docs
weight: 82
url: /sv/java/com.groupdocs.watermark.contents/presentationformattedtextfragment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public class PresentationFormattedTextFragment extends FormattedTextFragment implements IPresentationHyperlinkContainer
```

Representerar ett fragment av formaterad text i ett PowerPoint-dokument.

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
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | Hämtar hyperlänken som är associerad med texten. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Ställer in hyperlänken som är associerad med texten. |
|
### getText() {#getText--}
```
public String getText()
```


Hämtar fragmenttexten.


**Returns:**
java.lang.String - Fragmenttexten.

### getFont() {#getFont--}
```
public Font getFont()
```


Hämtar teckensnittet för texten.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Hämtar förgrundsfärgen för texten.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Hämtar bakgrundsfärgen för texten.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Hämtar hyperlänken som är associerad med texten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | actionType | int | Åtgärden som aktiverar hyperlänken. |
|

**Returns:**
java.lang.String - URL:en för hyperlänken som aktiveras vid angiven åtgärd.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Ställer in hyperlänken som är associerad med texten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | actionType | int | Åtgärden som aktiverar hyperlänken. |
|
|  | url | java.lang.String | Hyperlänkens URL. |
|

