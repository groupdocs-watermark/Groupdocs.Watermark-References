---
title: "FormattedTextFragmentCollection"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili koleksi yang dapat diubah dari fragmen teks terformat."
type: docs
weight: 27
url: /id/java/com.groupdocs.watermark.search/formattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class FormattedTextFragmentCollection extends RemoveOnlyListBase<FormattedTextFragment>
```

Mewakili koleksi yang dapat diubah dari fragmen teks terformat.

Koleksi ini berisi item-item dari tipe dasar `[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)`.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FormattedTextFragmentCollection(int collectionType)](#FormattedTextFragmentCollection-int-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getCollectionType()](#getCollectionType--) | Mendapatkan tipe koleksi fragmen yang diformat. |
|
| [getDefaultFont()](#getDefaultFont--) |  |
| [getDefaultForegroundColor()](#getDefaultForegroundColor--) |  |
| [getDefaultBackgroundColor()](#getDefaultBackgroundColor--) |  |
| [getText()](#getText--) |  |
|  | [add(String text)](#add-java.lang.String-) | Menambahkan fragmen teks yang diformat ke koleksi. |
|
|  | [add(String text, Font font)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Menambahkan fragmen teks yang diformat ke koleksi. |
|
|  | [add(String text, Font font, Color foregroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Menambahkan fragmen teks yang diformat ke koleksi. |
|
|  | [add(String text, Font font, Color foregroundColor, Color backgroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Menambahkan fragmen teks yang diformat ke koleksi. |
|
|  | [insert(int index, String text)](#insert-int-java.lang.String-) | Menyisipkan fragmen teks yang diformat ke dalam koleksi pada indeks tertentu. |
|
|  | [insert(int index, String text, Font font)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Menyisipkan fragmen teks yang diformat ke dalam koleksi pada indeks tertentu. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Menyisipkan fragmen teks yang diformat ke dalam koleksi pada indeks tertentu. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Menyisipkan fragmen teks yang diformat ke dalam koleksi pada indeks tertentu. |
|
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
| [setText(String text)](#setText-java.lang.String-) |  |
### FormattedTextFragmentCollection(int collectionType) {#FormattedTextFragmentCollection-int-}
```
public FormattedTextFragmentCollection(int collectionType)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| collectionType | int |  |

### getCollectionType() {#getCollectionType--}
```
public final int getCollectionType()
```


Mendapatkan tipe koleksi fragmen yang diformat.


**Returns:**
int - Tipe koleksi fragmen yang diformat.

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


Menambahkan fragmen teks yang diformat ke koleksi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | teks | java.lang.String | Teks fragmen. |
|

### add(String text, Font font) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void add(String text, Font font)
```


Menambahkan fragmen teks yang diformat ke koleksi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | teks | java.lang.String | Teks fragmen. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Font teks. |
|

### add(String text, Font font, Color foregroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor)
```


Menambahkan fragmen teks yang diformat ke koleksi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | teks | java.lang.String | Teks fragmen. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Font teks. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Warna latar depan teks. |
|

### add(String text, Font font, Color foregroundColor, Color backgroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor, Color backgroundColor)
```


Menambahkan fragmen teks yang diformat ke koleksi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | teks | java.lang.String | Teks fragmen. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Font teks. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Warna latar depan teks. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Warna latar belakang teks. |
|

### insert(int index, String text) {#insert-int-java.lang.String-}
```
public final void insert(int index, String text)
```


Menyisipkan fragmen teks yang diformat ke dalam koleksi pada indeks tertentu.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | indeks | int | Indeks berbasis nol tempat fragmen teks yang diformat harus disisipkan. |
|
|  | teks | java.lang.String | Teks fragmen. |
|

### insert(int index, String text, Font font) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void insert(int index, String text, Font font)
```


Menyisipkan fragmen teks yang diformat ke dalam koleksi pada indeks tertentu.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | indeks | int | Indeks berbasis nol tempat fragmen teks yang diformat harus disisipkan. |
|
|  | teks | java.lang.String | Teks fragmen. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Font teks. |
|

### insert(int index, String text, Font font, Color foregroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor)
```


Menyisipkan fragmen teks yang diformat ke dalam koleksi pada indeks tertentu.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | indeks | int | Indeks berbasis nol tempat fragmen teks yang diformat harus disisipkan. |
|
|  | teks | java.lang.String | Teks fragmen. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Font teks. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Warna latar depan teks. |
|

### insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


Menyisipkan fragmen teks yang diformat ke dalam koleksi pada indeks tertentu.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | indeks | int | Indeks berbasis nol tempat fragmen teks yang diformat harus disisipkan. |
|
|  | teks | java.lang.String | Teks fragmen. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Font teks. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Warna latar depan teks. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Warna latar belakang teks. |
|

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int |  |
| teks | java.lang.String |  |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String |  |

