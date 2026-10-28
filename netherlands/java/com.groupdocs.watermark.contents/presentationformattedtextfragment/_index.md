---
title: "PresentationFormattedTextFragment"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een fragment van opgemaakte tekst voor in een PowerPoint-document."
type: docs
weight: 82
url: /nl/java/com.groupdocs.watermark.contents/presentationformattedtextfragment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public class PresentationFormattedTextFragment extends FormattedTextFragment implements IPresentationHyperlinkContainer
```

Stelt een fragment van opgemaakte tekst voor in een PowerPoint-document.

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
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | Haalt de hyperlink op die bij de tekst hoort. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Stelt de hyperlink in die bij de tekst hoort. |
|
### getText() {#getText--}
```
public String getText()
```


Haalt de fragmenttekst op.


**Returns:**
java.lang.String - De fragmenttekst.

### getFont() {#getFont--}
```
public Font getFont()
```


Haalt het lettertype van de tekst op.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Haalt de voorgrondkleur van de tekst op.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Haalt de achtergrondkleur van de tekst op.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Haalt de hyperlink op die bij de tekst hoort.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | actionType | int | De actie die de hyperlink activeert. |
|

**Returns:**
java.lang.String - De url van de hyperlink die wordt geactiveerd bij de opgegeven actie.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Stelt de hyperlink in die bij de tekst hoort.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | actionType | int | De actie die de hyperlink activeert. |
|
|  | url | java.lang.String | De hyperlink‑url. |
|

