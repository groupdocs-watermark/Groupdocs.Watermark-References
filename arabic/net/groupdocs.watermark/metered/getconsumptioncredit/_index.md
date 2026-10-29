---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يسترجع عدد الأرصدة المستهلكة."
type: docs
weight: 30
url: /ar/net/groupdocs.watermark/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

يسترجع عدد الأرصدة المستهلكة.

```csharp
public static long GetConsumptionCredit()
```

### قيمة الإرجاع

عدد الاعتمادات المستهلكة.

### أمثلة

المثال التالي يوضح كيفية استرجاع عدد الاعتمادات المستهلكة.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### انظر أيضاً

* class [Metered](../../metered)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
