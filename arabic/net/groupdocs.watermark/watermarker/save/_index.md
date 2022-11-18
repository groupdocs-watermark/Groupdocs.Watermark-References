---
title: Save
second_title: GroupDocs.Watermark لـ .NET API Reference
description: يحفظ بيانات المستند في التدفق الأساسي.
type: docs
weight: 100
url: /ar/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

يحفظ بيانات المستند في التدفق الأساسي.

```csharp
public void Save()
```

### ملاحظات

تعرف على المزيد حول حفظ المستندات [حفظ المستندات](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### أمثلة

قم بإزالة أجزاء نصية معينة من نص / موضوع رسالة البريد الإلكتروني وحفظ رسالة البريد الإلكتروني.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // ملاحظة ، يتم إجراء البحث فقط إذا قمت بتمرير مثيل TextSearchCriteria إلى طريقة البحث
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // إزالة أجزاء النص التي تم العثور عليها
    watermarker.Remove(watermarks);
    // حفظ التغييرات
    watermarker.Save();
}
```

### أنظر أيضا

* class [Watermarker](../../watermarker)
* مساحة الاسم [GroupDocs.Watermark](../../watermarker)
* المجسم [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

يحفظ المستند في موقع الملف المحدد.

```csharp
public void Save(string filePath)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف الذي سيتم حفظ بيانات المستند فيه. |

### ملاحظات

تعرف على المزيد حول حفظ المستندات [حفظ المستندات](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### أمثلة

أضف العلامة المائية واحفظ المستند في ملف آخر.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### أنظر أيضا

* class [Watermarker](../../watermarker)
* مساحة الاسم [GroupDocs.Watermark](../../watermarker)
* المجسم [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

يحفظ المستند في التدفق المحدد .

```csharp
public void Save(Stream document)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Stream | الدفق لحفظ بيانات المستند إليه. |

### ملاحظات

تعرف على المزيد حول حفظ المستندات [حفظ المستندات](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### أمثلة

أضف علامة مائية واحفظ المستند في تيار الذاكرة.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream);
        // ...
    }
}
```

### أنظر أيضا

* class [Watermarker](../../watermarker)
* مساحة الاسم [GroupDocs.Watermark](../../watermarker)
* المجسم [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

يحفظ بيانات المستند إلى التدفق الأساسي باستخدام خيارات الحفظ.

```csharp
public void Save(SaveOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| options | SaveOptions | خيارات إضافية لاستخدامها عند حفظ مستند. |

### ملاحظات

تعرف على المزيد حول حفظ المستندات [حفظ المستندات](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### أمثلة

أضف علامة مائية واحفظ المستند افتراضيًا[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### أنظر أيضا

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* مساحة الاسم [GroupDocs.Watermark](../../watermarker)
* المجسم [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

يحفظ المستند في موقع الملف المحدد باستخدام خيارات الحفظ.

```csharp
public void Save(string filePath, SaveOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف الذي سيتم حفظ بيانات المستند فيه. |
| options | SaveOptions | خيارات إضافية لاستخدامها عند حفظ مستند. |

### ملاحظات

تعرف على المزيد حول حفظ المستندات [حفظ المستندات](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### أمثلة

أضف العلامة المائية واحفظ المستند في ملف آخر افتراضيًا[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### أنظر أيضا

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* مساحة الاسم [GroupDocs.Watermark](../../watermarker)
* المجسم [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

يحفظ المستند في التدفق المحدد باستخدام خيارات الحفظ.

```csharp
public void Save(Stream document, SaveOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Stream | الدفق لحفظ بيانات المستند إليه. |
| options | SaveOptions | خيارات إضافية لاستخدامها عند حفظ مستند. |

### ملاحظات

تعرف على المزيد حول حفظ المستندات [حفظ المستندات](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### أمثلة

أضف علامة مائية واحفظ المستند في تيار الذاكرة افتراضيًا[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream, new SaveOptions());
        // ...
    }
}
```

### أنظر أيضا

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* مساحة الاسم [GroupDocs.Watermark](../../watermarker)
* المجسم [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
