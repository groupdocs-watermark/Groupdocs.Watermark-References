---
title: "FormattedTextFragmentCollection"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una colección mutable de fragmentos de texto con formato."
type: docs
weight: 27
url: /es/java/com.groupdocs.watermark.search/formattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class FormattedTextFragmentCollection extends RemoveOnlyListBase<FormattedTextFragment>
```

Representa una colección mutable de fragmentos de texto con formato.

Esta colección contiene los elementos del tipo base `[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)`.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FormattedTextFragmentCollection(int collectionType)](#FormattedTextFragmentCollection-int-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getCollectionType()](#getCollectionType--) | Obtiene el tipo de colección de fragmentos formateados. |
|
| [getDefaultFont()](#getDefaultFont--) |  |
| [getDefaultForegroundColor()](#getDefaultForegroundColor--) |  |
| [getDefaultBackgroundColor()](#getDefaultBackgroundColor--) |  |
| [getText()](#getText--) |  |
|  | [add(String text)](#add-java.lang.String-) | Agrega un fragmento de texto formateado a la colección. |
|
|  | [add(String text, Font font)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Agrega un fragmento de texto formateado a la colección. |
|
|  | [add(String text, Font font, Color foregroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Agrega un fragmento de texto formateado a la colección. |
|
|  | [add(String text, Font font, Color foregroundColor, Color backgroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Agrega un fragmento de texto formateado a la colección. |
|
|  | [insert(int index, String text)](#insert-int-java.lang.String-) | Inserta un fragmento de texto formateado en la colección en un índice dado. |
|
|  | [insert(int index, String text, Font font)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Inserta un fragmento de texto formateado en la colección en un índice dado. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Inserta un fragmento de texto formateado en la colección en un índice dado. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Inserta un fragmento de texto formateado en la colección en un índice dado. |
|
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
| [setText(String text)](#setText-java.lang.String-) |  |
### FormattedTextFragmentCollection(int collectionType) {#FormattedTextFragmentCollection-int-}
```
public FormattedTextFragmentCollection(int collectionType)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| collectionType | int |  |

### getCollectionType() {#getCollectionType--}
```
public final int getCollectionType()
```


Obtiene el tipo de colección de fragmentos formateados.


**Returns:**
int - El tipo de colección de fragmentos formateados.

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


Agrega un fragmento de texto formateado a la colección.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | texto | java.lang.String | El texto del fragmento. |
|

### add(String text, Font font) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void add(String text, Font font)
```


Agrega un fragmento de texto formateado a la colección.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | texto | java.lang.String | El texto del fragmento. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | La fuente del texto. |
|

### add(String text, Font font, Color foregroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor)
```


Agrega un fragmento de texto formateado a la colección.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | texto | java.lang.String | El texto del fragmento. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | La fuente del texto. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | El color de primer plano del texto. |
|

### add(String text, Font font, Color foregroundColor, Color backgroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor, Color backgroundColor)
```


Agrega un fragmento de texto formateado a la colección.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | texto | java.lang.String | El texto del fragmento. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | La fuente del texto. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | El color de primer plano del texto. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | El color de fondo del texto. |
|

### insert(int index, String text) {#insert-int-java.lang.String-}
```
public final void insert(int index, String text)
```


Inserta un fragmento de texto formateado en la colección en un índice dado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | índice | int | El índice basado en cero en el que se debe insertar el fragmento de texto formateado. |
|
|  | texto | java.lang.String | El texto del fragmento. |
|

### insert(int index, String text, Font font) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void insert(int index, String text, Font font)
```


Inserta un fragmento de texto formateado en la colección en un índice dado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | índice | int | El índice basado en cero en el que se debe insertar el fragmento de texto formateado. |
|
|  | texto | java.lang.String | El texto del fragmento. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | La fuente del texto. |
|

### insert(int index, String text, Font font, Color foregroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor)
```


Inserta un fragmento de texto formateado en la colección en un índice dado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | índice | int | El índice basado en cero en el que se debe insertar el fragmento de texto formateado. |
|
|  | texto | java.lang.String | El texto del fragmento. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | La fuente del texto. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | El color de primer plano del texto. |
|

### insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


Inserta un fragmento de texto formateado en la colección en un índice dado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | índice | int | El índice basado en cero en el que se debe insertar el fragmento de texto formateado. |
|
|  | texto | java.lang.String | El texto del fragmento. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | La fuente del texto. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | El color de primer plano del texto. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | El color de fondo del texto. |
|

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int |  |
| texto | java.lang.String |  |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| texto | java.lang.String |  |

