---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يوفر خيارات لتعيين المتطلبات ومندوبين التدفق لإنشاء المعاينة."
type: docs
weight: 47
url: /ar/java/com.groupdocs.watermark.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

يوفر خيارات لتعيين المتطلبات ومندوبين التدفق لإنشاء المعاينة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PreviewOptions(ICreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | يقوم بإنشاء نسخة جديدة من الفئة `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` مما يؤدي إلى إغلاق تدفق الإخراج. |
|
|  | [PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | يقوم بإنشاء نسخة جديدة من الفئة `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` مما يؤدي إلى إرجاع تدفق الإخراج إلى العميل للاستخدام لاحقًا. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWidth()](#getWidth--) | يحصل على عرض معاينة الصفحة. |
|
|  | [setWidth(int value)](#setWidth-int-) | يضبط عرض معاينة الصفحة. |
|
|  | [getHeight()](#getHeight--) | يحصل على ارتفاع معاينة الصفحة. |
|
|  | [setHeight(int value)](#setHeight-int-) | يضبط ارتفاع معاينة الصفحة. |
|
|  | [getPageNumbers()](#getPageNumbers--) | يحصل على مصفوفة أرقام الصفحات لتوليد المعاينات. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | يضبط مصفوفة أرقام الصفحات لتوليد المعاينات. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | يحصل على تنسيق صورة المعاينة. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | يضبط تنسيق صورة المعاينة. |
|
|  | [getCreatePageStream()](#getCreatePageStream--) | يحصل على نسخة من فئة إنشاء تدفق الصفحة. |
|
|  | [setCreatePageStream(ICreatePageStream value)](#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-) | يضبط نسخة من فئة إنشاء تدفق الصفحة. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | يحصل على نسخة من فئة إكمال معاينة الصفحة. |
|
|  | [setReleasePageStream(IReleasePageStream value)](#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | يضبط نسخة من فئة إكمال معاينة الصفحة. |
|
### PreviewOptions(ICreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream)
```


يقوم بإنشاء نسخة جديدة من الفئة `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` مما يؤدي إلى إغلاق تدفق الإخراج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | ينشئ تدفقًا لمعاينة صفحة محددة. |
|

### PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


يقوم بإنشاء نسخة جديدة من الفئة `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` مما يؤدي إلى إرجاع تدفق الإخراج إلى العميل للاستخدام لاحقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | ينشئ تدفقًا لمعاينة صفحة محددة. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | يُخطر بأن إنشاء معاينة الصفحة انتهى ويحصل على تدفق الإخراج. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


يحصل على عرض معاينة الصفحة.


**Returns:**
int - عرض معاينة الصفحة.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


يضبط عرض معاينة الصفحة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | عرض معاينة الصفحة. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


يحصل على ارتفاع معاينة الصفحة.


**Returns:**
int - ارتفاع معاينة الصفحة.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


يضبط ارتفاع معاينة الصفحة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | ارتفاع معاينة الصفحة. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


يحصل على مصفوفة أرقام الصفحات لتوليد المعاينات.


**Returns:**
int[] - مصفوفة أرقام الصفحات لتوليد المعاينات.

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


يضبط مصفوفة أرقام الصفحات لتوليد المعاينات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int[] | مصفوفة أرقام الصفحات لتوليد المعاينات. |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


يحصل على تنسيق صورة المعاينة.


**Returns:**
int - تنسيق صورة المعاينة.

### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


يضبط تنسيق صورة المعاينة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | تنسيق صورة المعاينة. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public final ICreatePageStream getCreatePageStream()
```


يحصل على نسخة من فئة إنشاء تدفق الصفحة.


**Returns:**
[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) - The instance of the page stream creation class.

### setCreatePageStream(ICreatePageStream value) {#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-}
```
public final void setCreatePageStream(ICreatePageStream value)
```


يضبط نسخة من فئة إنشاء تدفق الصفحة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | مثيل فئة إنشاء تدفق الصفحة. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public final IReleasePageStream getReleasePageStream()
```


يحصل على نسخة من فئة إكمال معاينة الصفحة.


**Returns:**
[IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) - The instance of the page preview completion delegate.

### setReleasePageStream(IReleasePageStream value) {#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public final void setReleasePageStream(IReleasePageStream value)
```


يضبط نسخة من فئة إكمال معاينة الصفحة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | مثيل مفوض إكمال معاينة الصفحة. |
|

