---
title: PresentationFormattedTextFragment
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a fragment of formatted text in a PowerPoint document.
type: docs
weight: 82
url: /java/com.groupdocs.watermark.contents/presentationformattedtextfragment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public class PresentationFormattedTextFragment extends FormattedTextFragment implements IPresentationHyperlinkContainer
```

Represents a fragment of formatted text in a PowerPoint document.
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Gets the fragment text. |
| [getFont()](#getFont--) | Gets the font of the text. |
| [getForegroundColor()](#getForegroundColor--) | Gets the foreground color of the text. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets the background color of the text. |
| [getHyperlink(int actionType)](#getHyperlink-int-) | Gets the hyperlink associated with the text. |
| [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Sets the hyperlink associated with the text. |
### getText() {#getText--}
```
public String getText()
```


Gets the fragment text.

**Returns:**
java.lang.String - The fragment text.
### getFont() {#getFont--}
```
public Font getFont()
```


Gets the font of the text.

**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Gets the foreground color of the text.

**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets the background color of the text.

**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.
### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Gets the hyperlink associated with the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| actionType | int | The action that activates the hyperlink. |

**Returns:**
java.lang.String - The url of the hyperlink that is activated on specified action.
### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Sets the hyperlink associated with the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| actionType | int | The action that activates the hyperlink. |
| url | java.lang.String | The hyperlink url. |

