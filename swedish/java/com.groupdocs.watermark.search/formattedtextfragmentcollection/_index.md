---
title: "FormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en muterbar samling av formaterade textfragment."
type: docs
weight: 27
url: /sv/java/com.groupdocs.watermark.search/formattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class FormattedTextFragmentCollection extends RemoveOnlyListBase<FormattedTextFragment>
```

Representerar en muterbar samling av formaterade textfragment.

Denna samling innehåller objekt av bastypen `[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)`.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FormattedTextFragmentCollection(int collectionType)](#FormattedTextFragmentCollection-int-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getCollectionType()](#getCollectionType--) | Hämtar typen för den formaterade fragmentssamlingen. |
|
| [getDefaultFont()](#getDefaultFont--) |  |
| [getDefaultForegroundColor()](#getDefaultForegroundColor--) |  |
| [getDefaultBackgroundColor()](#getDefaultBackgroundColor--) |  |
| [getText()](#getText--) |  |
|  | [add(String text)](#add-java.lang.String-) | Lägger till ett formaterat textfragment i samlingen. |
|
|  | [add(String text, Font font)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Lägger till ett formaterat textfragment i samlingen. |
|
|  | [add(String text, Font font, Color foregroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Lägger till ett formaterat textfragment i samlingen. |
|
|  | [add(String text, Font font, Color foregroundColor, Color backgroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Lägger till ett formaterat textfragment i samlingen. |
|
|  | [insert(int index, String text)](#insert-int-java.lang.String-) | Infogar ett formaterat textfragment i samlingen på ett givet index. |
|
|  | [insert(int index, String text, Font font)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Infogar ett formaterat textfragment i samlingen på ett givet index. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Infogar ett formaterat textfragment i samlingen på ett givet index. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Infogar ett formaterat textfragment i samlingen på ett givet index. |
|
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
| [setText(String text)](#setText-java.lang.String-) |  |
### FormattedTextFragmentCollection(int collectionType) {#FormattedTextFragmentCollection-int-}
```
public FormattedTextFragmentCollection(int collectionType)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| samlingstyp | int |  |

### getCollectionType() {#getCollectionType--}
```
public final int getCollectionType()
```


Hämtar typen för den formaterade fragmentssamlingen.


**Returns:**
int - Den formaterade fragmentssamlingens typ.

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


Lägger till ett formaterat textfragment i samlingen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | Fragmentets text. |
|

### add(String text, Font font) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void add(String text, Font font)
```


Lägger till ett formaterat textfragment i samlingen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | Fragmentets text. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Teckensnittet för texten. |
|

### add(String text, Font font, Color foregroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor)
```


Lägger till ett formaterat textfragment i samlingen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | Fragmentets text. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Teckensnittet för texten. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Förgrundsfärgen för texten. |
|

### add(String text, Font font, Color foregroundColor, Color backgroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor, Color backgroundColor)
```


Lägger till ett formaterat textfragment i samlingen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | Fragmentets text. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Teckensnittet för texten. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Förgrundsfärgen för texten. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Bakgrundsfärgen för texten. |
|

### insert(int index, String text) {#insert-int-java.lang.String-}
```
public final void insert(int index, String text)
```


Infogar ett formaterat textfragment i samlingen på ett givet index.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | index | int | Det nollbaserade indexet där det formaterade textfragmentet ska infogas. |
|
|  | text | java.lang.String | Fragmentets text. |
|

### insert(int index, String text, Font font) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void insert(int index, String text, Font font)
```


Infogar ett formaterat textfragment i samlingen på ett givet index.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | index | int | Det nollbaserade indexet där det formaterade textfragmentet ska infogas. |
|
|  | text | java.lang.String | Fragmentets text. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Teckensnittet för texten. |
|

### insert(int index, String text, Font font, Color foregroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor)
```


Infogar ett formaterat textfragment i samlingen på ett givet index.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | index | int | Det nollbaserade indexet där det formaterade textfragmentet ska infogas. |
|
|  | text | java.lang.String | Fragmentets text. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Teckensnittet för texten. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Förgrundsfärgen för texten. |
|

### insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


Infogar ett formaterat textfragment i samlingen på ett givet index.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | index | int | Det nollbaserade indexet där det formaterade textfragmentet ska infogas. |
|
|  | text | java.lang.String | Fragmentets text. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Teckensnittet för texten. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Förgrundsfärgen för texten. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Bakgrundsfärgen för texten. |
|

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String |  |

