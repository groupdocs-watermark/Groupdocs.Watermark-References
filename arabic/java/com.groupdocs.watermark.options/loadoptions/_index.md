---
title: "LoadOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل خيارات تحميل المستند عند تحميل مستند."
type: docs
weight: 24
url: /ar/java/com.groupdocs.watermark.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

يمثل خيارات تحميل المستند عند تحميل مستند.

**Learn more:**

* [Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents)
* [Load from local disk](../https://docs.groupdocs.com/display/watermarkjava/Load+from+local+disk)
* [Load from stream](../https://docs.groupdocs.com/display/watermarkjava/Load+from+stream)
* [Load document of specific format](../https://docs.groupdocs.com/display/watermarkjava/Load+document+of+specific+format)
* [Load password-protected document](../https://docs.groupdocs.com/display/watermarkjava/Load+password-protected+document)

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | ينشئ مثيلاً جديداً من الفئة `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)`. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | ينشئ مثيلاً جديداً من الفئة `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` مع كلمة مرور محددة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPassword()](#getPassword--) | يحصل على كلمة المرور لفتح مستند مشفر. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يضبط كلمة المرور لفتح مستند مشفر. |
|
|  | [getFormatFamily()](#getFormatFamily--) | احصل على عائلة تنسيق المستند، التي تشير إلى نوعه (مثل Image، Pdf، Spreadsheet، إلخ). |
|
|  | [setFormatFamily(int formatFamily)](#setFormatFamily-int-) | اضبط عائلة تنسيق المستند، التي تشير إلى نوعه (مثل Image، Pdf، Spreadsheet، إلخ). |
|
|  | [getFileType()](#getFileType--) | احصل على نوع الملف، الذي يشير إلى صيغته (مثل docx، pdf، xlsx، إلخ). |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.watermark.common.FileType-) | اضبط نوع الملف، الذي يشير إلى صيغته (مثل docx، pdf، xlsx، إلخ). |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


ينشئ مثيلاً جديداً من الفئة `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)`.


### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


ينشئ مثيلاً جديداً من الفئة `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` مع كلمة مرور محددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | كلمة المرور | java.lang.String | كلمة المرور لفتح محتوى مشفر. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


يحصل على كلمة المرور لفتح مستند مشفر.


**Returns:**
java.lang.String - كلمة المرور لفتح مستند مشفر.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يضبط كلمة المرور لفتح مستند مشفر.

يجب أن تكون كلمة المرور null أو سلسلة فارغة. القيمة الافتراضية هي null.
إذا لم يكن المحتوى مشفراً، اجعل هذه القيمة null أو سلسلة فارغة.

المثال التالي يوضح كيفية تحميل مستند محمي بكلمة مرور.
>
> ````
> ```
>
>    LoadOptions loadOptions = new LoadOptions();
>    loadOptions.setPassword("pwd123");
>  
>    Watermarker watermarker = new Watermarker("D:\\doc.vsdx", loadOptions);
>    // ...
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | كلمة المرور لفتح مستند مشفر. |
|

### getFormatFamily() {#getFormatFamily--}
```
public int getFormatFamily()
```


احصل على عائلة تنسيق المستند، التي تشير إلى نوعه (مثل Image، Pdf، Spreadsheet، إلخ).


**Returns:**
int - formatFamily نوع الملف.

### setFormatFamily(int formatFamily) {#setFormatFamily-int-}
```
public void setFormatFamily(int formatFamily)
```


اضبط عائلة تنسيق المستند، التي تشير إلى نوعه (مثل Image، Pdf، Spreadsheet، إلخ).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | formatFamily | int | نوع الملف. |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


احصل على نوع الملف، الذي يشير إلى صيغته (مثل docx، pdf، xlsx، إلخ).


**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype) - fileType The file type.

### setFileType(FileType fileType) {#setFileType-com.groupdocs.watermark.common.FileType-}
```
public void setFileType(FileType fileType)
```


اضبط نوع الملف، الذي يشير إلى صيغته (مثل docx، pdf، xlsx، إلخ).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.watermark.common/filetype) | نوع الملف. |
|

