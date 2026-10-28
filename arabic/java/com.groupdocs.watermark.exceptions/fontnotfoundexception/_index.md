---
title: "FontNotFoundException"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "الاستثناء الذي يُرمى عندما لا يتم العثور على الخط المطلوب."
type: docs
weight: 12
url: /ar/java/com.groupdocs.watermark.exceptions/fontnotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, [com.groupdocs.watermark.exceptions.WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception)
```
public class FontNotFoundException extends WatermarkException
```

الاستثناء الذي يُرمى عندما لا يتم العثور على الخط المطلوب.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [FontNotFoundException()](#FontNotFoundException--) | يُنشئ مثيلاً جديدًا للفئة `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)`. |
|
|  | [FontNotFoundException(String fontName)](#FontNotFoundException-java.lang.String-) | يُنشئ مثيلاً جديدًا للفئة `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` باسم خط محدد. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFontName()](#getFontName--) | يحصل على اسم الخط المطلوب. |
|
### FontNotFoundException() {#FontNotFoundException--}
```
public FontNotFoundException()
```


يُنشئ مثيلاً جديدًا للفئة `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)`.


### FontNotFoundException(String fontName) {#FontNotFoundException-java.lang.String-}
```
public FontNotFoundException(String fontName)
```


يُنشئ مثيلاً جديدًا للفئة `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` باسم خط محدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fontName | java.lang.String | اسم الخط المطلوب. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


يحصل على اسم الخط المطلوب.


**Returns:**
java.lang.String - اسم الخط المطلوب.

