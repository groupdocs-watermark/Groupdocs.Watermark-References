---
title: "حفظ"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يحفظ بيانات المستند إلى الدفق الأساسي."
type: docs
weight: 100
url: /ar/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

يحفظ بيانات المستند إلى الدفق الأساسي.

```csharp
public WatermarkResult Save()
```

### ملاحظات

تعرف على المزيد حول حفظ المستندات [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### أمثلة

إزالة مقاطع النص المحددة من جسم/موضوع رسالة البريد الإلكتروني وحفظ الرسالة.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // ملاحظة، يتم إجراء البحث فقط إذا قمت بتمرير كائن TextSearchCriteria إلى طريقة Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // إزالة مقاطع النص المكتشفة
    watermarker.Remove(watermarks);
    // حفظ التغييرات
    watermarker.Save();
}
```

### انظر أيضاً

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

يحفظ المستند إلى موقع الملف المحدد.

```csharp
public WatermarkResult Save(string filePath)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف لحفظ بيانات المستند إليه. |

### ملاحظات

تعرف على المزيد حول حفظ المستندات [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

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

### انظر أيضاً

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

يحفظ المستند إلى الدفق المحدد.

```csharp
public WatermarkResult Save(Stream document)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| مستند | Stream | الدفق لحفظ بيانات المستند إليه. |

### ملاحظات

تعرف على المزيد حول حفظ المستندات [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### أمثلة

أضف العلامة المائية واحفظ المستند في دفق الذاكرة.

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

### انظر أيضاً

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

يحفظ بيانات المستند إلى الدفق الأساسي باستخدام خيارات الحفظ.

```csharp
public WatermarkResult Save(SaveOptions options)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| options | SaveOptions | خيارات إضافية للاستخدام عند حفظ المستند. |

### ملاحظات

تعرف على المزيد حول حفظ المستندات [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### أمثلة

أضف علامة مائية واحفظ المستند باستخدام الإعدادات الافتراضية لـ [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### انظر أيضاً

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

يحفظ المستند في موقع الملف المحدد باستخدام خيارات الحفظ.

```csharp
public WatermarkResult Save(string filePath, SaveOptions options)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف لحفظ بيانات المستند إليه. |
| options | SaveOptions | خيارات إضافية للاستخدام عند حفظ المستند. |

### ملاحظات

تعرف على المزيد حول حفظ المستندات [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### أمثلة

أضف العلامة المائية واحفظ المستند إلى ملف آخر باستخدام الإعدادات الافتراضية لـ [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### انظر أيضاً

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

يحفظ المستند إلى الدفق المحدد باستخدام خيارات الحفظ.

```csharp
public WatermarkResult Save(Stream document, SaveOptions options)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| مستند | Stream | الدفق لحفظ بيانات المستند إليه. |
| options | SaveOptions | خيارات إضافية للاستخدام عند حفظ المستند. |

### ملاحظات

تعرف على المزيد حول حفظ المستندات [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### أمثلة

أضف علامة مائية واحفظ المستند إلى تدفق الذاكرة باستخدام الإعدادات الافتراضية لـ [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

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

### انظر أيضاً

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
