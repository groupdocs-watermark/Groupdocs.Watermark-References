---
title: "WordProcessingWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل الخيارات عند إضافة العلامة المائية إلى رأس/تذييل قسم Word."
type: docs
weight: 74
url: /ar/java/com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkHeaderFooterOptions extends WordProcessingWatermarkBaseOptions
```

يمثل الخيارات عند إضافة العلامة المائية إلى رأس/تذييل قسم Word.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WordProcessingWatermarkHeaderFooterOptions()](#WordProcessingWatermarkHeaderFooterOptions--) | ينشئ مثيلاً جديداً من الفئة `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | يحصل على فهرس القسم لإضافة العلامة المائية إليه. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | يضبط فهرس القسم لإضافة العلامة المائية إليه. |
|
|  | [getHeaderFooterType()](#getHeaderFooterType--) | يحصل على القيمة التي تحدد نوع الرأس أو التذييل لإضافة العلامة المائية إليه. |
|
|  | [setHeaderFooterType(int value)](#setHeaderFooterType-int-) | يضبط القيمة التي تحدد نوع الرأس أو التذييل لإضافة العلامة المائية إليه. |
|
### WordProcessingWatermarkHeaderFooterOptions() {#WordProcessingWatermarkHeaderFooterOptions--}
```
public WordProcessingWatermarkHeaderFooterOptions()
```


ينشئ مثيلاً جديداً من الفئة `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)`.


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


يحصل على فهرس القسم لإضافة العلامة المائية إليه.


**Returns:**
int - الفهرس لقسم لإضافة العلامة المائية إليه.

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


يضبط فهرس القسم لإضافة العلامة المائية إليه.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | الفهرس لقسم لإضافة العلامة المائية إليه. |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


يحصل على القيمة التي تحدد نوع الرأس أو التذييل لإضافة العلامة المائية إليه.


**Returns:**
int - القيمة من النوع `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` التي تحدد نوع الرأس أو التذييل لإضافة العلامة المائية إليه.

### setHeaderFooterType(int value) {#setHeaderFooterType-int-}
```
public final void setHeaderFooterType(int value)
```


يضبط القيمة التي تحدد نوع الرأس أو التذييل لإضافة العلامة المائية إليه.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | القيمة من النوع `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` التي تحدد نوع الرأس أو التذييل لإضافة العلامة المائية إليه. |
|

