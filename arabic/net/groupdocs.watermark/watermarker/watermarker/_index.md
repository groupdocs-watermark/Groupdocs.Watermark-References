---
title: "Watermarker"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "ينشئ مثيلاً جديداً من الفئة Watermarkergroupdocs.watermark/watermarker بالمسار المحدد للمستند."
type: docs
weight: 10
url: /ar/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

ينشئ مثيلاً جديداً من الفئة [`Watermarker`](../../watermarker) بالمسار المحدد للمستند.

```csharp
public Watermarker(string filePath)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف لتحميل المستند منه. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | نوع المستند المقدم غير مدعوم. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | كلمة المرور المقدمة غير صحيحة. |

### ملاحظات

تعرف على المزيد حول تحميل المستندات: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### أمثلة

تحميل وحفظ محتوى بأي تنسيق مدعوم.

```csharp
// تحميل محتوى من ملف.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // استخدم أساليب فئة Watermarker لإضافة أو البحث أو إزالة العلامات المائية.

    // احفظ المستند.
    watermarker.Save("D:\\output.pdf");
}
```

### انظر أيضاً

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

ينشئ مثيلاً جديداً من الفئة [`Watermarker`](../../watermarker) بالمسار المحدد للمستند وخيارات التحميل.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف لتحميل المستند منه. |
| options | LoadOptions | خيارات إضافية لاستخدامها عند تحميل مستند. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | نوع المستند المقدم غير مدعوم. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | كلمة المرور المقدمة غير صحيحة. |

### ملاحظات

تعرف على المزيد حول تحميل المستندات: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### أمثلة

حمّل مستند PDF مشفر باستخدام كلمة المرور.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### انظر أيضاً

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

ينشئ مثيلاً جديداً من الفئة [`Watermarker`](../../watermarker) بالمسار المحدد للمستند والإعدادات.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف لتحميل المستند منه. |
| الإعدادات | WatermarkerSettings | إعدادات إضافية لاستخدامها عند العمل مع المستند المحمَّل. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | نوع المستند المقدم غير مدعوم. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | كلمة المرور المقدمة غير صحيحة. |

### ملاحظات

تعرف على المزيد حول تحميل المستندات: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### أمثلة

حدد الكائنات القابلة للبحث عالمياً (لكل المستندات التي ستحمّل لاحقاً).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (Watermarker watermarker = new Watermarker(file, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // الكود الخاص بالتعامل مع العلامات المائية المكتشفة يكتب هنا.
    }
}
```

### انظر أيضاً

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

ينشئ مثيلاً جديداً من الفئة [`Watermarker`](../../watermarker) بالمسار المحدد للمستند، خيارات التحميل والإعدادات.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف لتحميل المستند منه. |
| options | LoadOptions | خيارات إضافية لاستخدامها عند تحميل مستند. |
| الإعدادات | WatermarkerSettings | إعدادات إضافية لاستخدامها عند العمل مع المستند المحمَّل. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | نوع المستند المقدم غير مدعوم. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | كلمة المرور المقدمة غير صحيحة. |

### ملاحظات

تعرف على المزيد حول تحميل المستندات: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### أمثلة

ابحث عن مقاطع نصية معينة في جسم/موضوع رسالة البريد الإلكتروني.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.msg", loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // ملاحظة، يتم إجراء البحث فقط إذا قمت بتمرير كائن TextSearchCriteria إلى طريقة Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // إزالة مقاطع النص المكتشفة
    watermarks.Clear();
    // حفظ التغييرات
    watermarker.Save();
}
```

### انظر أيضاً

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

ينشئ مثيلاً جديداً من الفئة [`Watermarker`](../../watermarker) باستخدام الدفق المحدد.

```csharp
public Watermarker(Stream document)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| مستند | Stream | الدفق لتحميل المستند منه. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | نوع المستند المقدم غير مدعوم. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | كلمة المرور المقدمة غير صحيحة. |

### ملاحظات

تعرف على المزيد حول تحميل المستندات [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### أمثلة

تحميل وحفظ مستند بأي تنسيق مدعوم.

```csharp
// تحميل محتوى من دفق.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // استخدم أساليب فئة Watermarker لإضافة أو البحث أو إزالة العلامات المائية.

    // احفظ التغييرات.
    watermarker.Save(outputStream);
}
```

### انظر أيضاً

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

ينشئ مثيلاً جديداً من الفئة [`Watermarker`](../../watermarker) باستخدام الدفق المحدد وخيارات التحميل.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| مستند | Stream | الدفق لتحميل المستند منه. |
| options | LoadOptions | خيارات إضافية لاستخدامها عند تحميل مستند. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | نوع المستند المقدم غير مدعوم. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | كلمة المرور المقدمة غير صحيحة. |

### ملاحظات

تعرف على المزيد حول تحميل المستندات [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### أمثلة

تحميل مستند PDF مشفر باستخدام كلمة المرور

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### انظر أيضاً

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

ينشئ مثيلاً جديداً من الفئة [`Watermarker`](../../watermarker) باستخدام الدفق المحدد والإعدادات.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| مستند | Stream | الدفق لتحميل المستند منه. |
| الإعدادات | WatermarkerSettings | إعدادات إضافية لاستخدامها عند العمل مع المستند المحمَّل. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | نوع المستند المقدم غير مدعوم. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | كلمة المرور المقدمة غير صحيحة. |

### ملاحظات

تعرف على المزيد حول تحميل المستندات [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### أمثلة

حدد الكائنات القابلة للبحث عالمياً (لكل المستندات التي ستحمّل لاحقاً).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (FileStream fileStream = File.Open(file, FileMode.Open))
    using (Watermarker watermarker = new Watermarker(fileStream, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // الكود الخاص بالتعامل مع العلامات المائية المكتشفة يكتب هنا.
    }
}
```

### انظر أيضاً

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

ينشئ مثيلاً جديداً من الفئة [`Watermarker`](../../watermarker) باستخدام الدفق المحدد، خيارات التحميل والإعدادات.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| مستند | Stream | الدفق لتحميل المستند منه. |
| options | LoadOptions | خيارات إضافية لاستخدامها عند تحميل مستند. |
| الإعدادات | WatermarkerSettings | إعدادات إضافية لاستخدامها عند العمل مع المستند المحمَّل. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | نوع المستند المقدم غير مدعوم. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | كلمة المرور المقدمة غير صحيحة. |

### ملاحظات

تعرف على المزيد حول تحميل المستندات [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### أمثلة

ابحث عن مقاطع نصية معينة في جسم/موضوع رسالة البريد الإلكتروني.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (FileStream fileStream = File.Open(@"D:\test.msg", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // ملاحظة، يتم إجراء البحث فقط إذا قمت بتمرير كائن TextSearchCriteria إلى طريقة Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // إزالة مقاطع النص المكتشفة
    watermarks.Clear();
    // حفظ التغييرات
    watermarker.Save();
}
```

### انظر أيضاً

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
