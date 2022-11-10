---
title: FormattedTextFragment
second_title: GroupDocs.Watermark for Java API Reference
description: Provides abstract base class for a fragment of formatted text in a content.
type: docs
weight: 26
url: /java/com.groupdocs.watermark.search/formattedtextfragment/
---
**Inheritance:**
java.lang.Object
```
public abstract class FormattedTextFragment
```

Provides abstract base class for a fragment of formatted text in a content.
## Constructors

| Constructor | Description |
| --- | --- |
| [FormattedTextFragment()](#FormattedTextFragment--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Gets the fragment text. |
| [getFont()](#getFont--) | Gets the font of the text. |
| [getForegroundColor()](#getForegroundColor--) | Gets the foreground color of the text. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets the background color of the text. |
### FormattedTextFragment() {#FormattedTextFragment--}
```
public FormattedTextFragment()
```




### getText() {#getText--}
```
public abstract String getText()
```


Gets the fragment text.

**Returns:**
java.lang.String - The fragment text.
### getFont() {#getFont--}
```
public abstract Font getFont()
```


Gets the font of the text.

**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.
### getForegroundColor() {#getForegroundColor--}
```
public abstract Color getForegroundColor()
```


Gets the foreground color of the text.

**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.
### getBackgroundColor() {#getBackgroundColor--}
```
public abstract Color getBackgroundColor()
```


Gets the background color of the text.

**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.
