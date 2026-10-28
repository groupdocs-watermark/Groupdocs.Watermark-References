---
title: "FormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine veränderbare Sammlung formatierter Textfragmente dar."
type: docs
weight: 27
url: /de/java/com.groupdocs.watermark.search/formattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class FormattedTextFragmentCollection extends RemoveOnlyListBase<FormattedTextFragment>
```

Stellt eine veränderbare Sammlung formatierter Textfragmente dar.

Diese Sammlung enthält die Elemente des Basistyps `[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)`.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FormattedTextFragmentCollection(int collectionType)](#FormattedTextFragmentCollection-int-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getCollectionType()](#getCollectionType--) | Ermittelt den Typ der formatierten Fragmentsammlung. |
|
| [getDefaultFont()](#getDefaultFont--) |  |
| [getDefaultForegroundColor()](#getDefaultForegroundColor--) |  |
| [getDefaultBackgroundColor()](#getDefaultBackgroundColor--) |  |
| [getText()](#getText--) |  |
|  | [add(String text)](#add-java.lang.String-) | Fügt der Sammlung ein formatiertes Textfragment hinzu. |
|
|  | [add(String text, Font font)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Fügt der Sammlung ein formatiertes Textfragment hinzu. |
|
|  | [add(String text, Font font, Color foregroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Fügt der Sammlung ein formatiertes Textfragment hinzu. |
|
|  | [add(String text, Font font, Color foregroundColor, Color backgroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Fügt der Sammlung ein formatiertes Textfragment hinzu. |
|
|  | [insert(int index, String text)](#insert-int-java.lang.String-) | Fügt an einem angegebenen Index ein formatiertes Textfragment in die Sammlung ein. |
|
|  | [insert(int index, String text, Font font)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Fügt an einem angegebenen Index ein formatiertes Textfragment in die Sammlung ein. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Fügt an einem angegebenen Index ein formatiertes Textfragment in die Sammlung ein. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Fügt an einem angegebenen Index ein formatiertes Textfragment in die Sammlung ein. |
|
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
| [setText(String text)](#setText-java.lang.String-) |  |
### FormattedTextFragmentCollection(int collectionType) {#FormattedTextFragmentCollection-int-}
```
public FormattedTextFragmentCollection(int collectionType)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| collectionType | int |  |

### getCollectionType() {#getCollectionType--}
```
public final int getCollectionType()
```


Ermittelt den Typ der formatierten Fragmentsammlung.


**Returns:**
int – Der Typ der formatierten Fragmentsammlung.

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


Fügt der Sammlung ein formatiertes Textfragment hinzu.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | Der Fragmenttext. |
|

### add(String text, Font font) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void add(String text, Font font)
```


Fügt der Sammlung ein formatiertes Textfragment hinzu.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | Der Fragmenttext. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Die Schriftart des Textes. |
|

### add(String text, Font font, Color foregroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor)
```


Fügt der Sammlung ein formatiertes Textfragment hinzu.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | Der Fragmenttext. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Die Schriftart des Textes. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Die Vordergrundfarbe des Textes. |
|

### add(String text, Font font, Color foregroundColor, Color backgroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor, Color backgroundColor)
```


Fügt der Sammlung ein formatiertes Textfragment hinzu.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | Der Fragmenttext. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Die Schriftart des Textes. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Die Vordergrundfarbe des Textes. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Die Hintergrundfarbe des Textes. |
|

### insert(int index, String text) {#insert-int-java.lang.String-}
```
public final void insert(int index, String text)
```


Fügt an einem angegebenen Index ein formatiertes Textfragment in die Sammlung ein.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Index | int | Der nullbasierte Index, an dem das formatierte Textfragment eingefügt werden soll. |
|
|  | Text | java.lang.String | Der Fragmenttext. |
|

### insert(int index, String text, Font font) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void insert(int index, String text, Font font)
```


Fügt an einem angegebenen Index ein formatiertes Textfragment in die Sammlung ein.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Index | int | Der nullbasierte Index, an dem das formatierte Textfragment eingefügt werden soll. |
|
|  | Text | java.lang.String | Der Fragmenttext. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Die Schriftart des Textes. |
|

### insert(int index, String text, Font font, Color foregroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor)
```


Fügt an einem angegebenen Index ein formatiertes Textfragment in die Sammlung ein.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Index | int | Der nullbasierte Index, an dem das formatierte Textfragment eingefügt werden soll. |
|
|  | Text | java.lang.String | Der Fragmenttext. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Die Schriftart des Textes. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Die Vordergrundfarbe des Textes. |
|

### insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


Fügt an einem angegebenen Index ein formatiertes Textfragment in die Sammlung ein.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Index | int | Der nullbasierte Index, an dem das formatierte Textfragment eingefügt werden soll. |
|
|  | Text | java.lang.String | Der Fragmenttext. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Die Schriftart des Textes. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Die Vordergrundfarbe des Textes. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Die Hintergrundfarbe des Textes. |
|

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int |  |
| Text | java.lang.String |  |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Text | java.lang.String |  |

