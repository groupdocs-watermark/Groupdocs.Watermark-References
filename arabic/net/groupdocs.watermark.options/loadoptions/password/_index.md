---
title: "كلمة المرور"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يحصل أو يضبط كلمة المرور لفتح مستند مشفر."
type: docs
weight: 50
url: /ar/net/groupdocs.watermark.options/loadoptions/password/
---
## LoadOptions.Password property

يحصل أو يضبط كلمة المرور لفتح مستند مشفر.

```csharp
public string Password { get; set; }
```

### Property Value

كلمة المرور لفتح مستند مشفر.

### ملاحظات

يجب أن تكون كلمة المرور فارغة أو سلسلة نصية خالية. القيمة الافتراضية هي null. إذا لم يكن المحتوى مشفرًا، اضبطها على null أو سلسلة نصية خالية.

### أمثلة

حمّل محتوىً محميًا بكلمة مرور.

```csharp
LoadOptions loadOptions = new LoadOptions
{
    Password = "pwd123"
};
using (Watermarker watermarker = new Watermarker(@"D:\doc.vsdx", loadOptions))
{
    // ...
}
```

### انظر أيضاً

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
