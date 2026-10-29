---
title: "FormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Biçimlendirilmiş metin parçacıklarının değiştirilebilir bir koleksiyonunu temsil eder."
type: docs
weight: 27
url: /tr/java/com.groupdocs.watermark.search/formattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class FormattedTextFragmentCollection extends RemoveOnlyListBase<FormattedTextFragment>
```

Biçimlendirilmiş metin parçacıklarının değiştirilebilir bir koleksiyonunu temsil eder.

Bu koleksiyon, `[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)` temel türünün öğelerini içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FormattedTextFragmentCollection(int collectionType)](#FormattedTextFragmentCollection-int-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getCollectionType()](#getCollectionType--) | Biçimlendirilmiş parçacık koleksiyon türünü alır. |
|
| [getDefaultFont()](#getDefaultFont--) |  |
| [getDefaultForegroundColor()](#getDefaultForegroundColor--) |  |
| [getDefaultBackgroundColor()](#getDefaultBackgroundColor--) |  |
| [getText()](#getText--) |  |
|  | [add(String text)](#add-java.lang.String-) | Biçimlendirilmiş bir metin parçacığını koleksiyona ekler. |
|
|  | [add(String text, Font font)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Biçimlendirilmiş bir metin parçacığını koleksiyona ekler. |
|
|  | [add(String text, Font font, Color foregroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Biçimlendirilmiş bir metin parçacığını koleksiyona ekler. |
|
|  | [add(String text, Font font, Color foregroundColor, Color backgroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Biçimlendirilmiş bir metin parçacığını koleksiyona ekler. |
|
|  | [insert(int index, String text)](#insert-int-java.lang.String-) | Belirli bir indeksde biçimlendirilmiş bir metin parçacığını koleksiyona ekler. |
|
|  | [insert(int index, String text, Font font)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Belirli bir indeksde biçimlendirilmiş bir metin parçacığını koleksiyona ekler. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Belirli bir indeksde biçimlendirilmiş bir metin parçacığını koleksiyona ekler. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Belirli bir indeksde biçimlendirilmiş bir metin parçacığını koleksiyona ekler. |
|
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
| [setText(String text)](#setText-java.lang.String-) |  |
### FormattedTextFragmentCollection(int collectionType) {#FormattedTextFragmentCollection-int-}
```
public FormattedTextFragmentCollection(int collectionType)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| collectionType | int |  |

### getCollectionType() {#getCollectionType--}
```
public final int getCollectionType()
```


Biçimlendirilmiş parçacık koleksiyon türünü alır.


**Returns:**
int - Biçimlendirilmiş parçacık koleksiyon türü.

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


Biçimlendirilmiş bir metin parçacığını koleksiyona ekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | metin | java.lang.String | Parçacık metni. |
|

### add(String text, Font font) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void add(String text, Font font)
```


Biçimlendirilmiş bir metin parçacığını koleksiyona ekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | metin | java.lang.String | Parçacık metni. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Metnin yazı tipi. |
|

### add(String text, Font font, Color foregroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor)
```


Biçimlendirilmiş bir metin parçacığını koleksiyona ekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | metin | java.lang.String | Parçacık metni. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Metnin yazı tipi. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Metnin ön plan rengi. |
|

### add(String text, Font font, Color foregroundColor, Color backgroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor, Color backgroundColor)
```


Biçimlendirilmiş bir metin parçacığını koleksiyona ekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | metin | java.lang.String | Parçacık metni. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Metnin yazı tipi. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Metnin ön plan rengi. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Metnin arka plan rengi. |
|

### insert(int index, String text) {#insert-int-java.lang.String-}
```
public final void insert(int index, String text)
```


Belirli bir indeksde biçimlendirilmiş bir metin parçacığını koleksiyona ekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | index | int | Biçimlendirilmiş metin parçacığının eklenmesi gereken sıfır tabanlı indeks. |
|
|  | metin | java.lang.String | Parçacık metni. |
|

### insert(int index, String text, Font font) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void insert(int index, String text, Font font)
```


Belirli bir indeksde biçimlendirilmiş bir metin parçacığını koleksiyona ekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | index | int | Biçimlendirilmiş metin parçacığının eklenmesi gereken sıfır tabanlı indeks. |
|
|  | metin | java.lang.String | Parçacık metni. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Metnin yazı tipi. |
|

### insert(int index, String text, Font font, Color foregroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor)
```


Belirli bir indeksde biçimlendirilmiş bir metin parçacığını koleksiyona ekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | index | int | Biçimlendirilmiş metin parçacığının eklenmesi gereken sıfır tabanlı indeks. |
|
|  | metin | java.lang.String | Parçacık metni. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Metnin yazı tipi. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Metnin ön plan rengi. |
|

### insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


Belirli bir indeksde biçimlendirilmiş bir metin parçacığını koleksiyona ekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | index | int | Biçimlendirilmiş metin parçacığının eklenmesi gereken sıfır tabanlı indeks. |
|
|  | metin | java.lang.String | Parçacık metni. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Metnin yazı tipi. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Metnin ön plan rengi. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Metnin arka plan rengi. |
|

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |
| metin | java.lang.String |  |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String |  |

