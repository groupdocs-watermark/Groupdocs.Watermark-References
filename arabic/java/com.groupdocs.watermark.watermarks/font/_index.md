---
title: "Font"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "فئة تمثل خطًا."
type: docs
weight: 11
url: /ar/java/com.groupdocs.watermark.watermarks/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

فئة تمثل خطًا.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | ينشئ نسخة جديدة من الفئة `[Font](../../com.groupdocs.watermark.watermarks/font)` مع اسم عائلة الخط المحدد وحجم. |
|
|  | [Font(String fontFamilyName, float size, int style)](#Font-java.lang.String-float-int-) | ينشئ نسخة جديدة من الفئة `[Font](../../com.groupdocs.watermark.watermarks/font)` مع اسم عائلة الخط المحدد، وحجم، ونمط. |
|
| [Font(String fontFamilyName, String folderPath, float size)](#Font-java.lang.String-java.lang.String-float-) |  |
| [Font(String fontFamilyName, String folderPath, float size, FontStyle style)](#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFolderPath()](#getFolderPath--) |  |
| [setFolderPath(String folderPath)](#setFolderPath-java.lang.String-) |  |
|  | [getFamilyName()](#getFamilyName--) | يحصل على اسم العائلة لهذا `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getSize()](#getSize--) | يحصل على حجم هذا `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getStyle()](#getStyle--) | يحصل على `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` لهذا `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getBold()](#getBold--) | يحصل على قيمة تشير إلى ما إذا كان الخط غامقًا. |
|
|  | [getItalic()](#getItalic--) | يحصل على قيمة تشير إلى ما إذا كان الخط مائلًا. |
|
|  | [getStrikeout()](#getStrikeout--) | يحصل على قيمة تشير إلى ما إذا كان الخط يحدد خطًا أفقيًا عبره. |
|
|  | [getUnderline()](#getUnderline--) | يحصل على قيمة تشير إلى ما إذا كان الخط مسطرًا. |
|
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


ينشئ نسخة جديدة من الفئة `[Font](../../com.groupdocs.watermark.watermarks/font)` مع اسم عائلة الخط المحدد وحجم.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | اسم عائلة الخط. |
|
|  | size | float | حجم الخط الجديد. |
|

### Font(String fontFamilyName, float size, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontFamilyName, float size, int style)
```


ينشئ نسخة جديدة من الفئة `[Font](../../com.groupdocs.watermark.watermarks/font)` مع اسم عائلة الخط المحدد، وحجم، ونمط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | اسم عائلة الخط. |
|
|  | size | float | حجم الخط الجديد. |
|
|  | style | int | نمط `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` للخط الجديد. |
|

### Font(String fontFamilyName, String folderPath, float size) {#Font-java.lang.String-java.lang.String-float-}
```
public Font(String fontFamilyName, String folderPath, float size)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |

### Font(String fontFamilyName, String folderPath, float size, FontStyle style) {#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-}
```
public Font(String fontFamilyName, String folderPath, float size, FontStyle style)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |
| style | [FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle) |  |

### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```




**Returns:**
java.lang.String
### setFolderPath(String folderPath) {#setFolderPath-java.lang.String-}
```
public void setFolderPath(String folderPath)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| folderPath | java.lang.String |  |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


يحصل على اسم العائلة لهذا `[Font](../../com.groupdocs.watermark.watermarks/font)`.


**Returns:**
java.lang.String - اسم العائلة لهذا `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getSize() {#getSize--}
```
public final float getSize()
```


يحصل على حجم هذا `[Font](../../com.groupdocs.watermark.watermarks/font)`.


**Returns:**
float - حجم هذا `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getStyle() {#getStyle--}
```
public final int getStyle()
```


يحصل على `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` لهذا `[Font](../../com.groupdocs.watermark.watermarks/font)`.

القيمة الافتراضية هي `[FontStyle.Regular](../../com.groupdocs.watermark.watermarks/fontstyle#Regular)` (نص عادي).


**Returns:**
int - الـ`[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` لهذا `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getBold() {#getBold--}
```
public final boolean getBold()
```


يحصل على قيمة تشير إلى ما إذا كان الخط غامقًا.


**Returns:**
boolean - صحيح إذا كان هذا الخط غامقًا؛ وإلا false.

### getItalic() {#getItalic--}
```
public final boolean getItalic()
```


يحصل على قيمة تشير إلى ما إذا كان الخط مائلًا.


**Returns:**
boolean - صحيح إذا كان هذا الخط مائلًا؛ وإلا false.

### getStrikeout() {#getStrikeout--}
```
public final boolean getStrikeout()
```


يحصل على قيمة تشير إلى ما إذا كان الخط يحدد خطًا أفقيًا عبره.


**Returns:**
boolean - صحيح إذا كان هذا الخط يحدد خطًا أفقيًا عبره؛ وإلا false.

### getUnderline() {#getUnderline--}
```
public final boolean getUnderline()
```


يحصل على قيمة تشير إلى ما إذا كان الخط مسطرًا.


**Returns:**
boolean - صحيح إذا كان هذا الخط مسطرًا؛ وإلا false.

