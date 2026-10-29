---
title: "Metered"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يوفر طرقًا لترخيص المكوّن باستخدام ترخيص مقنن."
type: docs
weight: 1690
url: /ar/net/groupdocs.watermark/metered/
---
## Metered class

يوفر طرقًا لترخيص المكوّن باستخدام ترخيص مقنن.

```csharp
public class Metered
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Metered](metered)() | يقوم بتهيئة نسخة جديدة من الفئة [`Metered`](../metered). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SetMeteredKey](../../groupdocs.watermark/metered/setmeteredkey)(string, string) | يفعل المنتج باستخدام مفاتيح Metered. |
| static [GetConsumptionCredit](../../groupdocs.watermark/metered/getconsumptioncredit)() | يسترجع عدد الأرصدة المستهلكة. |
| static [GetConsumptionQuantity](../../groupdocs.watermark/metered/getconsumptionquantity)() | يسترجع كمية الميجابايتات المعالجة. |

### ملاحظات

**Learn more**

* More about Metered licensing: [Metered Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing/metered)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### أمثلة

المثال التالي يوضح كيفية تنشيط المنتج باستخدام المفاتيح المقنَّعة.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### انظر أيضاً

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
