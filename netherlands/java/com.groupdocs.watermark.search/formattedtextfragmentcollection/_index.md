---
title: "FormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een mutabele collectie van opgemaakte tekstfragmenten voor."
type: docs
weight: 27
url: /nl/java/com.groupdocs.watermark.search/formattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class FormattedTextFragmentCollection extends RemoveOnlyListBase<FormattedTextFragment>
```

Stelt een mutabele collectie van opgemaakte tekstfragmenten voor.

Deze collectie bevat de items van het basistype `[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)`.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FormattedTextFragmentCollection(int collectionType)](#FormattedTextFragmentCollection-int-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getCollectionType()](#getCollectionType--) | Haalt het type van de opgemaakte fragmentcollectie op. |
|
| [getDefaultFont()](#getDefaultFont--) |  |
| [getDefaultForegroundColor()](#getDefaultForegroundColor--) |  |
| [getDefaultBackgroundColor()](#getDefaultBackgroundColor--) |  |
| [getText()](#getText--) |  |
|  | [add(String text)](#add-java.lang.String-) | Voegt een opgemaakt tekstfragment toe aan de collectie. |
|
|  | [add(String text, Font font)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Voegt een opgemaakt tekstfragment toe aan de collectie. |
|
|  | [add(String text, Font font, Color foregroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Voegt een opgemaakt tekstfragment toe aan de collectie. |
|
|  | [add(String text, Font font, Color foregroundColor, Color backgroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Voegt een opgemaakt tekstfragment toe aan de collectie. |
|
|  | [insert(int index, String text)](#insert-int-java.lang.String-) | Voegt een opgemaakt tekstfragment in de collectie in op een opgegeven index. |
|
|  | [insert(int index, String text, Font font)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Voegt een opgemaakt tekstfragment in de collectie in op een opgegeven index. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Voegt een opgemaakt tekstfragment in de collectie in op een opgegeven index. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Voegt een opgemaakt tekstfragment in de collectie in op een opgegeven index. |
|
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
| [setText(String text)](#setText-java.lang.String-) |  |
### FormattedTextFragmentCollection(int collectionType) {#FormattedTextFragmentCollection-int-}
```
public FormattedTextFragmentCollection(int collectionType)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| collectionType | int |  |

### getCollectionType() {#getCollectionType--}
```
public final int getCollectionType()
```


Haalt het type van de opgemaakte fragmentcollectie op.


**Returns:**
int - Het type van de opgemaakte fragmentcollectie.

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


Voegt een opgemaakt tekstfragment toe aan de collectie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | tekst | java.lang.String | De fragmenttekst. |
|

### add(String text, Font font) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void add(String text, Font font)
```


Voegt een opgemaakt tekstfragment toe aan de collectie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | tekst | java.lang.String | De fragmenttekst. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Het lettertype van de tekst. |
|

### add(String text, Font font, Color foregroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor)
```


Voegt een opgemaakt tekstfragment toe aan de collectie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | tekst | java.lang.String | De fragmenttekst. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Het lettertype van de tekst. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | De voorgrondkleur van de tekst. |
|

### add(String text, Font font, Color foregroundColor, Color backgroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor, Color backgroundColor)
```


Voegt een opgemaakt tekstfragment toe aan de collectie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | tekst | java.lang.String | De fragmenttekst. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Het lettertype van de tekst. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | De voorgrondkleur van de tekst. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | De achtergrondkleur van de tekst. |
|

### insert(int index, String text) {#insert-int-java.lang.String-}
```
public final void insert(int index, String text)
```


Voegt een opgemaakt tekstfragment in de collectie in op een opgegeven index.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | index | int | De nulgebaseerde index waarop het opgemaakte tekstfragment moet worden ingevoegd. |
|
|  | tekst | java.lang.String | De fragmenttekst. |
|

### insert(int index, String text, Font font) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void insert(int index, String text, Font font)
```


Voegt een opgemaakt tekstfragment in de collectie in op een opgegeven index.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | index | int | De nulgebaseerde index waarop het opgemaakte tekstfragment moet worden ingevoegd. |
|
|  | tekst | java.lang.String | De fragmenttekst. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Het lettertype van de tekst. |
|

### insert(int index, String text, Font font, Color foregroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor)
```


Voegt een opgemaakt tekstfragment in de collectie in op een opgegeven index.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | index | int | De nulgebaseerde index waarop het opgemaakte tekstfragment moet worden ingevoegd. |
|
|  | tekst | java.lang.String | De fragmenttekst. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Het lettertype van de tekst. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | De voorgrondkleur van de tekst. |
|

### insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


Voegt een opgemaakt tekstfragment in de collectie in op een opgegeven index.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | index | int | De nulgebaseerde index waarop het opgemaakte tekstfragment moet worden ingevoegd. |
|
|  | tekst | java.lang.String | De fragmenttekst. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Het lettertype van de tekst. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | De voorgrondkleur van de tekst. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | De achtergrondkleur van de tekst. |
|

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |
| tekst | java.lang.String |  |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tekst | java.lang.String |  |

