---
title: Watermarker
second_title: GroupDocs.Watermark لـ .NET API Reference
description: يقوم بتهيئة مثيل جديد لملفWatermarkergroupdocs.watermark/watermarker فئة بمسار المستند المحدد.
type: docs
weight: 10
url: /ar/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

يقوم بتهيئة مثيل جديد لملف[`Watermarker`](../../watermarker) فئة بمسار المستند المحدد.

```csharp
public Watermarker(string filePath)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف لتحميل المستند منه. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | نوع المستند المرفق غير مدعوم. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | كلمة المرور المقدمة غير صحيحة. |

### ملاحظات

تعرف على المزيد حول تحميل المستندات: [تحميل المستندات](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### أمثلة

تحميل وحفظ محتوى بأي تنسيق مدعوم.

```csharp
// تحميل محتوى من ملف.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // استخدم طرق فئة Watermarker لإضافة العلامات المائية أو البحث عنها أو إزالتها.

    // احفظ المستند.
    watermarker.Save("D:\\output.pdf");
}
```

### أنظر أيضا

* class [Watermarker](../../watermarker)
* مساحة الاسم [GroupDocs.Watermark](../../watermarker)
* المجسم [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

يقوم بتهيئة مثيل جديد لملف[`Watermarker`](../../watermarker)فئة بمسار المستند المحدد وخيارات التحميل.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف لتحميل المستند منه. |
| options | LoadOptions | خيارات إضافية لاستخدامها عند تحميل مستند. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | نوع المستند المرفق غير مدعوم. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | كلمة المرور المقدمة غير صحيحة. |

### ملاحظات

تعرف على المزيد حول تحميل المستندات: [تحميل المستندات](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### أمثلة

تحميل مستند PDF مشفر باستخدام كلمة المرور.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### أنظر أيضا

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* مساحة الاسم [GroupDocs.Watermark](../../watermarker)
* المجسم [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

يقوم بتهيئة مثيل جديد لملف[`Watermarker`](../../watermarker) فئة مع محدد مسار المستند والإعدادات .

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف لتحميل المستند منه. |
| settings | WatermarkerSettings | إعدادات إضافية لاستخدامها عند العمل مع المستند الذي تم تحميله. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | نوع المستند المرفق غير مدعوم. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | كلمة المرور المقدمة غير صحيحة. |

### ملاحظات

تعرف على المزيد حول تحميل المستندات: [تحميل المستندات](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### أمثلة

تعيين كائنات قابلة للبحث بشكل عام (لجميع المستندات التي سيتم تحميلها بعد ذلك) .

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

        // رمز العمل مع العلامات المائية الموجودة هنا.
    }
}
```

### أنظر أيضا

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* مساحة الاسم [GroupDocs.Watermark](../../watermarker)
* المجسم [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

يقوم بتهيئة مثيل جديد لملف[`Watermarker`](../../watermarker) فئة مع مسار المستند المحدد ، تحميل الخيارات والإعدادات .

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف لتحميل المستند منه. |
| options | LoadOptions | خيارات إضافية لاستخدامها عند تحميل مستند. |
| settings | WatermarkerSettings | إعدادات إضافية لاستخدامها عند العمل مع المستند الذي تم تحميله. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | نوع المستند المرفق غير مدعوم. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | كلمة المرور المقدمة غير صحيحة. |

### ملاحظات

تعرف على المزيد حول تحميل المستندات: [تحميل المستندات](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### أمثلة

البحث عن أجزاء نصية معينة في نص / موضوع رسالة البريد الإلكتروني.

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
    // ملاحظة ، يتم إجراء البحث فقط إذا قمت بتمرير مثيل TextSearchCriteria إلى طريقة البحث
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // إزالة أجزاء النص التي تم العثور عليها
    watermarks.Clear();
    // حفظ التغييرات
    watermarker.Save();
}
```

### أنظر أيضا

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* مساحة الاسم [GroupDocs.Watermark](../../watermarker)
* المجسم [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`Watermarker`](../../watermarker) فئة مع الدفق المحدد.

```csharp
public Watermarker(Stream document)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Stream | الدفق لتحميل المستند منه. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | نوع المستند المرفق غير مدعوم. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | كلمة المرور المقدمة غير صحيحة. |

### ملاحظات

تعرف على المزيد حول تحميل المستندات [تحميل المستندات](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### أمثلة

قم بتحميل وحفظ مستند بأي تنسيق مدعوم.

```csharp
// تحميل محتوى من دفق.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // استخدم طرق فئة Watermarker لإضافة العلامات المائية أو البحث عنها أو إزالتها.

    // حفظ التغييرات.
    watermarker.Save(outputStream);
}
```

### أنظر أيضا

* class [Watermarker](../../watermarker)
* مساحة الاسم [GroupDocs.Watermark](../../watermarker)
* المجسم [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`Watermarker`](../../watermarker) فئة مع Stream المحدد وخيارات التحميل.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Stream | الدفق لتحميل المستند منه. |
| options | LoadOptions | خيارات إضافية لاستخدامها عند تحميل مستند. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | نوع المستند المرفق غير مدعوم. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | كلمة المرور المقدمة غير صحيحة. |

### ملاحظات

تعرف على المزيد حول تحميل المستندات [تحميل المستندات](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### أمثلة

تحميل مستند PDF مشفر باستخدام password

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### أنظر أيضا

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* مساحة الاسم [GroupDocs.Watermark](../../watermarker)
* المجسم [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`Watermarker`](../../watermarker) فئة مع stream والإعدادات المحددة.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Stream | الدفق لتحميل المستند منه. |
| settings | WatermarkerSettings | إعدادات إضافية لاستخدامها عند العمل مع المستند الذي تم تحميله. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | نوع المستند المرفق غير مدعوم. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | كلمة المرور المقدمة غير صحيحة. |

### ملاحظات

تعرف على المزيد حول تحميل المستندات [تحميل المستندات](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### أمثلة

تعيين كائنات قابلة للبحث بشكل عام (لجميع المستندات التي سيتم تحميلها بعد ذلك) .

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

        // رمز العمل مع العلامات المائية الموجودة هنا.
    }
}
```

### أنظر أيضا

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* مساحة الاسم [GroupDocs.Watermark](../../watermarker)
* المجسم [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`Watermarker`](../../watermarker) فئة مع الدفق المحدد ، تحميل الخيارات والإعدادات .

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Stream | الدفق لتحميل المستند منه. |
| options | LoadOptions | خيارات إضافية لاستخدامها عند تحميل مستند. |
| settings | WatermarkerSettings | إعدادات إضافية لاستخدامها عند العمل مع المستند الذي تم تحميله. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | نوع المستند المرفق غير مدعوم. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | كلمة المرور المقدمة غير صحيحة. |

### ملاحظات

تعرف على المزيد حول تحميل المستندات [تحميل المستندات](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### أمثلة

البحث عن أجزاء نصية معينة في نص / موضوع رسالة البريد الإلكتروني.

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
    // ملاحظة ، يتم إجراء البحث فقط إذا قمت بتمرير مثيل TextSearchCriteria إلى طريقة البحث
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // إزالة أجزاء النص التي تم العثور عليها
    watermarks.Clear();
    // حفظ التغييرات
    watermarker.Save();
}
```

### أنظر أيضا

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* مساحة الاسم [GroupDocs.Watermark](../../watermarker)
* المجسم [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
