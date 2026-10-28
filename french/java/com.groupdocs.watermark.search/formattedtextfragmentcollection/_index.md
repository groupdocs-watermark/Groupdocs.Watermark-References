---
title: "FormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une collection mutable de fragments de texte formaté."
type: docs
weight: 27
url: /fr/java/com.groupdocs.watermark.search/formattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class FormattedTextFragmentCollection extends RemoveOnlyListBase<FormattedTextFragment>
```

Représente une collection mutable de fragments de texte formaté.

Cette collection contient les éléments du type de base `[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)`.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FormattedTextFragmentCollection(int collectionType)](#FormattedTextFragmentCollection-int-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getCollectionType()](#getCollectionType--) | Obtient le type de collection de fragments formatés. |
|
| [getDefaultFont()](#getDefaultFont--) |  |
| [getDefaultForegroundColor()](#getDefaultForegroundColor--) |  |
| [getDefaultBackgroundColor()](#getDefaultBackgroundColor--) |  |
| [getText()](#getText--) |  |
|  | [add(String text)](#add-java.lang.String-) | Ajoute un fragment de texte formaté à la collection. |
|
|  | [add(String text, Font font)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Ajoute un fragment de texte formaté à la collection. |
|
|  | [add(String text, Font font, Color foregroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Ajoute un fragment de texte formaté à la collection. |
|
|  | [add(String text, Font font, Color foregroundColor, Color backgroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Ajoute un fragment de texte formaté à la collection. |
|
|  | [insert(int index, String text)](#insert-int-java.lang.String-) | Insère un fragment de texte formaté dans la collection à un indice donné. |
|
|  | [insert(int index, String text, Font font)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Insère un fragment de texte formaté dans la collection à un indice donné. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Insère un fragment de texte formaté dans la collection à un indice donné. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Insère un fragment de texte formaté dans la collection à un indice donné. |
|
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
| [setText(String text)](#setText-java.lang.String-) |  |
### FormattedTextFragmentCollection(int collectionType) {#FormattedTextFragmentCollection-int-}
```
public FormattedTextFragmentCollection(int collectionType)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| collectionType | int |  |

### getCollectionType() {#getCollectionType--}
```
public final int getCollectionType()
```


Obtient le type de collection de fragments formatés.


**Returns:**
int - Le type de collection de fragments formatés.

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


Ajoute un fragment de texte formaté à la collection.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | texte | java.lang.String | Le texte du fragment. |
|

### add(String text, Font font) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void add(String text, Font font)
```


Ajoute un fragment de texte formaté à la collection.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | texte | java.lang.String | Le texte du fragment. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | La police du texte. |
|

### add(String text, Font font, Color foregroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor)
```


Ajoute un fragment de texte formaté à la collection.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | texte | java.lang.String | Le texte du fragment. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | La police du texte. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | La couleur de premier plan du texte. |
|

### add(String text, Font font, Color foregroundColor, Color backgroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor, Color backgroundColor)
```


Ajoute un fragment de texte formaté à la collection.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | texte | java.lang.String | Le texte du fragment. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | La police du texte. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | La couleur de premier plan du texte. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | La couleur d'arrière-plan du texte. |
|

### insert(int index, String text) {#insert-int-java.lang.String-}
```
public final void insert(int index, String text)
```


Insère un fragment de texte formaté dans la collection à un indice donné.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | indice | int | L'indice basé sur zéro à lequel le fragment de texte formaté doit être inséré. |
|
|  | texte | java.lang.String | Le texte du fragment. |
|

### insert(int index, String text, Font font) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void insert(int index, String text, Font font)
```


Insère un fragment de texte formaté dans la collection à un indice donné.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | indice | int | L'indice basé sur zéro à lequel le fragment de texte formaté doit être inséré. |
|
|  | texte | java.lang.String | Le texte du fragment. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | La police du texte. |
|

### insert(int index, String text, Font font, Color foregroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor)
```


Insère un fragment de texte formaté dans la collection à un indice donné.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | indice | int | L'indice basé sur zéro à lequel le fragment de texte formaté doit être inséré. |
|
|  | texte | java.lang.String | Le texte du fragment. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | La police du texte. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | La couleur de premier plan du texte. |
|

### insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


Insère un fragment de texte formaté dans la collection à un indice donné.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | indice | int | L'indice basé sur zéro à lequel le fragment de texte formaté doit être inséré. |
|
|  | texte | java.lang.String | Le texte du fragment. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | La police du texte. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | La couleur de premier plan du texte. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | La couleur d'arrière-plan du texte. |
|

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int |  |
| texte | java.lang.String |  |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String |  |

