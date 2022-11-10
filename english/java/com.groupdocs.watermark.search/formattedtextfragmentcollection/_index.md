---
title: FormattedTextFragmentCollection
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a mutable collection of formatted text fragments.
type: docs
weight: 27
url: /java/com.groupdocs.watermark.search/formattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class FormattedTextFragmentCollection extends RemoveOnlyListBase<FormattedTextFragment>
```

Represents a mutable collection of formatted text fragments.

This collection contains the items of `[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)` base type.
## Constructors

| Constructor | Description |
| --- | --- |
| [FormattedTextFragmentCollection(int collectionType)](#FormattedTextFragmentCollection-int-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCollectionType()](#getCollectionType--) | Gets the formatted fragment collection type. |
| [getDefaultFont()](#getDefaultFont--) |  |
| [getDefaultForegroundColor()](#getDefaultForegroundColor--) |  |
| [getDefaultBackgroundColor()](#getDefaultBackgroundColor--) |  |
| [getText()](#getText--) |  |
| [add(String text)](#add-java.lang.String-) | Adds a formatted text fragment to the collection. |
| [add(String text, Font font)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Adds a formatted text fragment to the collection. |
| [add(String text, Font font, Color foregroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Adds a formatted text fragment to the collection. |
| [add(String text, Font font, Color foregroundColor, Color backgroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Adds a formatted text fragment to the collection. |
| [insert(int index, String text)](#insert-int-java.lang.String-) | Inserts a formatted text fragment into the collection at a given index. |
| [insert(int index, String text, Font font)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Inserts a formatted text fragment into the collection at a given index. |
| [insert(int index, String text, Font font, Color foregroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Inserts a formatted text fragment into the collection at a given index. |
| [insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Inserts a formatted text fragment into the collection at a given index. |
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
| [setText(String text)](#setText-java.lang.String-) |  |
### FormattedTextFragmentCollection(int collectionType) {#FormattedTextFragmentCollection-int-}
```
public FormattedTextFragmentCollection(int collectionType)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| collectionType | int |  |

### getCollectionType() {#getCollectionType--}
```
public final int getCollectionType()
```


Gets the formatted fragment collection type.

**Returns:**
int - The formatted fragment collection type.
### getDefaultFont() {#getDefaultFont--}
```
public final Font getDefaultFont()
```




**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font)
### getDefaultForegroundColor() {#getDefaultForegroundColor--}
```
public final Color getDefaultForegroundColor()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getDefaultBackgroundColor() {#getDefaultBackgroundColor--}
```
public final Color getDefaultBackgroundColor()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### add(String text) {#add-java.lang.String-}
```
public final void add(String text)
```


Adds a formatted text fragment to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The fragment text. |

### add(String text, Font font) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void add(String text, Font font)
```


Adds a formatted text fragment to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The fragment text. |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) | The font of the text. |

### add(String text, Font font, Color foregroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor)
```


Adds a formatted text fragment to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The fragment text. |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) | The font of the text. |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | The foreground color of the text. |

### add(String text, Font font, Color foregroundColor, Color backgroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor, Color backgroundColor)
```


Adds a formatted text fragment to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The fragment text. |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) | The font of the text. |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | The foreground color of the text. |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | The background color of the text. |

### insert(int index, String text) {#insert-int-java.lang.String-}
```
public final void insert(int index, String text)
```


Inserts a formatted text fragment into the collection at a given index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which formatted text fragment should be inserted. |
| text | java.lang.String | The fragment text. |

### insert(int index, String text, Font font) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void insert(int index, String text, Font font)
```


Inserts a formatted text fragment into the collection at a given index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which formatted text fragment should be inserted. |
| text | java.lang.String | The fragment text. |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) | The font of the text. |

### insert(int index, String text, Font font, Color foregroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor)
```


Inserts a formatted text fragment into the collection at a given index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which formatted text fragment should be inserted. |
| text | java.lang.String | The fragment text. |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) | The font of the text. |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | The foreground color of the text. |

### insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


Inserts a formatted text fragment into the collection at a given index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which formatted text fragment should be inserted. |
| text | java.lang.String | The fragment text. |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) | The font of the text. |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | The foreground color of the text. |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | The background color of the text. |

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| text | java.lang.String |  |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) |  |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |

**Returns:**
[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)
### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |

