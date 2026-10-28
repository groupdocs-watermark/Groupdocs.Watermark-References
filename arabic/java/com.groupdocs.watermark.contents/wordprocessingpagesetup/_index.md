---
title: "WordProcessingPageSetup"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل خصائص طباعة الصفحة لقسم من مستند Word."
type: docs
weight: 134
url: /ar/java/com.groupdocs.watermark.contents/wordprocessingpagesetup/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingPageSetup
```

يمثل خصائص طباعة الصفحة لقسم من مستند Word.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWidth()](#getWidth--) | يحصل على عرض صفحة الطباعة بالنقاط. |
|
|  | [getHeight()](#getHeight--) | يحصل على ارتفاع صفحة الطباعة بالنقاط. |
|
|  | [getLeftMargin()](#getLeftMargin--) | يحصل على حجم الهامش الأيسر بالنقاط. |
|
|  | [getTopMargin()](#getTopMargin--) | يحصل على حجم الهامش العلوي بالنقاط. |
|
|  | [getRightMargin()](#getRightMargin--) | يحصل على حجم الهامش الأيمن بالنقاط. |
|
|  | [getBottomMargin()](#getBottomMargin--) | يحصل على حجم الهامش السفلي بالنقاط. |
|
|  | [getDifferentFirstPageHeaderFooter()](#getDifferentFirstPageHeaderFooter--) | يحصل على قيمة تشير إلى ما إذا كان يتم استخدام رأس/تذييل مختلف للصفحة الأولى. |
|
|  | [setDifferentFirstPageHeaderFooter(boolean value)](#setDifferentFirstPageHeaderFooter-boolean-) | يضبط قيمة تشير إلى ما إذا كان يتم استخدام رأس/تذييل مختلف للصفحة الأولى. |
|
|  | [getOddAndEvenPagesHeaderFooter()](#getOddAndEvenPagesHeaderFooter--) | يحصل على قيمة تشير إلى ما إذا كانت رؤوس/تذييلات مختلفة تُستخدم للصفحات ذات الأرقام الفردية والزوجية |
الصفحات.
|
|  | [setOddAndEvenPagesHeaderFooter(boolean value)](#setOddAndEvenPagesHeaderFooter-boolean-) | يضبط قيمة تشير إلى ما إذا كانت رؤوس/تذييلات مختلفة تُستخدم للصفحات ذات الأرقام الفردية والزوجية |
الصفحات.
|
### getWidth() {#getWidth--}
```
public final double getWidth()
```


يحصل على عرض صفحة الطباعة بالنقاط.


**Returns:**
double - عرض صفحة الطباعة بالنقاط.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


يحصل على ارتفاع صفحة الطباعة بالنقاط.


**Returns:**
double - ارتفاع صفحة الطباعة بالنقاط.

### getLeftMargin() {#getLeftMargin--}
```
public final double getLeftMargin()
```


يحصل على حجم الهامش الأيسر بالنقاط.


**Returns:**
double - حجم الهامش الأيسر بالنقاط.

### getTopMargin() {#getTopMargin--}
```
public final double getTopMargin()
```


يحصل على حجم الهامش العلوي بالنقاط.


**Returns:**
double - حجم الهامش العلوي بالنقاط.

### getRightMargin() {#getRightMargin--}
```
public final double getRightMargin()
```


يحصل على حجم الهامش الأيمن بالنقاط.


**Returns:**
double - حجم الهامش الأيمن بالنقاط.

### getBottomMargin() {#getBottomMargin--}
```
public final double getBottomMargin()
```


يحصل على حجم الهامش السفلي بالنقاط.


**Returns:**
double - حجم الهامش السفلي بالنقاط.

### getDifferentFirstPageHeaderFooter() {#getDifferentFirstPageHeaderFooter--}
```
public final boolean getDifferentFirstPageHeaderFooter()
```


يحصل على قيمة تشير إلى ما إذا كان يتم استخدام رأس/تذييل مختلف للصفحة الأولى.


**Returns:**
boolean - True إذا تم استخدام رأس/تذييل مختلف للصفحة الأولى؛ وإلا false.

### setDifferentFirstPageHeaderFooter(boolean value) {#setDifferentFirstPageHeaderFooter-boolean-}
```
public final void setDifferentFirstPageHeaderFooter(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان يتم استخدام رأس/تذييل مختلف للصفحة الأولى.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | True إذا تم استخدام رأس/تذييل مختلف للصفحة الأولى؛ وإلا false. |
|

### getOddAndEvenPagesHeaderFooter() {#getOddAndEvenPagesHeaderFooter--}
```
public final boolean getOddAndEvenPagesHeaderFooter()
```


يحصل على قيمة تشير إلى ما إذا كانت رؤوس/تذييلات مختلفة تُستخدم للصفحات ذات الأرقام الفردية والزوجية
الصفحات.
ملاحظة، تغيير هذه الخاصية يؤثر على جميع الأقسام في المحتوى.


**Returns:**
boolean - True إذا تم استخدام رؤوس/تذييلات مختلفة للصفحات ذات الأرقام الفردية والزوجية؛ وإلا false.

### setOddAndEvenPagesHeaderFooter(boolean value) {#setOddAndEvenPagesHeaderFooter-boolean-}
```
public final void setOddAndEvenPagesHeaderFooter(boolean value)
```


يضبط قيمة تشير إلى ما إذا كانت رؤوس/تذييلات مختلفة تُستخدم للصفحات ذات الأرقام الفردية والزوجية
الصفحات.
ملاحظة، تغيير هذه الخاصية يؤثر على جميع الأقسام في المحتوى.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | True إذا تم استخدام رؤوس/تذييلات مختلفة للصفحات ذات الأرقام الفردية والزوجية؛ وإلا false. |
|

