---
title: "Watermarker"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل فئة لإدارة العلامات المائية في مستند."
type: docs
weight: 3140
url: /ar/net/groupdocs.watermark/watermarker/
---
## Watermarker class

يمثل فئة لإدارة العلامات المائية في مستند.

```csharp
public class Watermarker : IDisposable
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | يُنشئ مثيلًا جديدًا من الفئة [`Watermarker`](../watermarker) باستخدام الدفق المحدد. |
| [Watermarker](watermarker#constructor_4)(string) | يُنشئ مثيلًا جديدًا من الفئة [`Watermarker`](../watermarker) باستخدام مسار المستند المحدد. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | يُنشئ مثيلًا جديدًا من الفئة [`Watermarker`](../watermarker) باستخدام الدفق المحدد وخيارات التحميل. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | يُنشئ مثيلًا جديدًا من الفئة [`Watermarker`](../watermarker) باستخدام الدفق المحدد والإعدادات. |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | يُنشئ مثيلًا جديدًا من الفئة [`Watermarker`](../watermarker) باستخدام مسار المستند المحدد وخيارات التحميل. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | يُنشئ مثيلًا جديدًا من الفئة [`Watermarker`](../watermarker) باستخدام مسار المستند المحدد والإعدادات. |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | يُنشئ مثيلًا جديدًا من الفئة [`Watermarker`](../watermarker) باستخدام الدفق المحدد، خيارات التحميل والإعدادات. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | يُنشئ مثيلًا جديدًا من الفئة [`Watermarker`](../watermarker) باستخدام مسار المستند المحدد، خيارات التحميل والإعدادات. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | يحصل أو يضبط كائنات المحتوى التي سيتم تضمينها في بحث العلامة المائية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | يضيف علامة مائية إلى المستند المحمَّل. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | يضيف علامة مائية إلى المستند المحمَّل باستخدام خيارات العلامة المائية. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | يتخلص من النسخة الحالية. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | ينشئ صورًا معاينة للمستند. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | يعيد كائن [`Content`](../../groupdocs.watermark.contents/content) للمستند المحمَّل. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | يحصل على المعلومات حول تنسيق المستند المحمَّل. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | يجد جميع الصور في المستند. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | يجد الصور وفقًا لمعايير البحث المحددة. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | يزيل العلامة المائية من المستند. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | يزيل جميع العلامات المائية في المجموعة من المستند. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | يحفظ بيانات المستند إلى الدفق الأساسي. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | يحفظ بيانات المستند إلى الدفق الأساسي باستخدام خيارات الحفظ. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | يحفظ المستند إلى الدفق المحدد. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | يحفظ المستند إلى موقع الملف المحدد. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | يحفظ المستند إلى الدفق المحدد باستخدام خيارات الحفظ. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | يحفظ المستند في موقع الملف المحدد باستخدام خيارات الحفظ. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | يبحث عن جميع العلامات المائية الممكنة في المستند. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | يبحث عن العلامات المائية الممكنة وفقًا لمعايير البحث المحددة. |

### أمثلة

تحميل وحفظ محتوى بأي تنسيق مدعوم.

```csharp
// تحميل محتوى من ملف.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // استخدم أساليب فئة Watermarker لإضافة أو البحث أو إزالة العلامات المائية.

    // احفظ التغييرات.
    watermarker.Save("D:\\output.pdf");
}
```

### انظر أيضاً

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
