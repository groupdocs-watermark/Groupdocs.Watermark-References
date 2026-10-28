---
title: "FormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل مجموعة قابلة للتغيير من أجزاء النص المنسق."
type: docs
weight: 27
url: /ar/java/com.groupdocs.watermark.search/formattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class FormattedTextFragmentCollection extends RemoveOnlyListBase<FormattedTextFragment>
```

يمثل مجموعة قابلة للتغيير من أجزاء النص المنسق.

تحتوي هذه المجموعة على عناصر من النوع الأساسي `[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)`.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FormattedTextFragmentCollection(int collectionType)](#FormattedTextFragmentCollection-int-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getCollectionType()](#getCollectionType--) | يحصل على نوع مجموعة القطع المنسقة. |
|
| [getDefaultFont()](#getDefaultFont--) |  |
| [getDefaultForegroundColor()](#getDefaultForegroundColor--) |  |
| [getDefaultBackgroundColor()](#getDefaultBackgroundColor--) |  |
| [getText()](#getText--) |  |
|  | [add(String text)](#add-java.lang.String-) | يضيف قطعة نص منسقة إلى المجموعة. |
|
|  | [add(String text, Font font)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | يضيف قطعة نص منسقة إلى المجموعة. |
|
|  | [add(String text, Font font, Color foregroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | يضيف قطعة نص منسقة إلى المجموعة. |
|
|  | [add(String text, Font font, Color foregroundColor, Color backgroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | يضيف قطعة نص منسقة إلى المجموعة. |
|
|  | [insert(int index, String text)](#insert-int-java.lang.String-) | يدرج قطعة نص منسقة في المجموعة عند فهرس معين. |
|
|  | [insert(int index, String text, Font font)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | يدرج قطعة نص منسقة في المجموعة عند فهرس معين. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | يدرج قطعة نص منسقة في المجموعة عند فهرس معين. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | يدرج قطعة نص منسقة في المجموعة عند فهرس معين. |
|
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
| [setText(String text)](#setText-java.lang.String-) |  |
### FormattedTextFragmentCollection(int collectionType) {#FormattedTextFragmentCollection-int-}
```
public FormattedTextFragmentCollection(int collectionType)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| collectionType | int |  |

### getCollectionType() {#getCollectionType--}
```
public final int getCollectionType()
```


يحصل على نوع مجموعة القطع المنسقة.


**Returns:**
int - نوع مجموعة القطع المنسقة.

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


يضيف قطعة نص منسقة إلى المجموعة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | نص القطعة. |
|

### add(String text, Font font) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void add(String text, Font font)
```


يضيف قطعة نص منسقة إلى المجموعة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | نص القطعة. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | خط النص. |
|

### add(String text, Font font, Color foregroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor)
```


يضيف قطعة نص منسقة إلى المجموعة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | نص القطعة. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | خط النص. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | لون المقدمة للنص. |
|

### add(String text, Font font, Color foregroundColor, Color backgroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor, Color backgroundColor)
```


يضيف قطعة نص منسقة إلى المجموعة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | نص القطعة. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | خط النص. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | لون المقدمة للنص. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | لون الخلفية للنص. |
|

### insert(int index, String text) {#insert-int-java.lang.String-}
```
public final void insert(int index, String text)
```


يدرج قطعة نص منسقة في المجموعة عند فهرس معين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | index | int | الفهرس الصفري الذي يجب إدراج قطعة النص المنسقة فيه. |
|
|  | نص | java.lang.String | نص القطعة. |
|

### insert(int index, String text, Font font) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void insert(int index, String text, Font font)
```


يدرج قطعة نص منسقة في المجموعة عند فهرس معين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | index | int | الفهرس الصفري الذي يجب إدراج قطعة النص المنسقة فيه. |
|
|  | نص | java.lang.String | نص القطعة. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | خط النص. |
|

### insert(int index, String text, Font font, Color foregroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor)
```


يدرج قطعة نص منسقة في المجموعة عند فهرس معين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | index | int | الفهرس الصفري الذي يجب إدراج قطعة النص المنسقة فيه. |
|
|  | نص | java.lang.String | نص القطعة. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | خط النص. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | لون المقدمة للنص. |
|

### insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


يدرج قطعة نص منسقة في المجموعة عند فهرس معين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | index | int | الفهرس الصفري الذي يجب إدراج قطعة النص المنسقة فيه. |
|
|  | نص | java.lang.String | نص القطعة. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | خط النص. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | لون المقدمة للنص. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | لون الخلفية للنص. |
|

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int |  |
| نص | java.lang.String |  |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| نص | java.lang.String |  |

