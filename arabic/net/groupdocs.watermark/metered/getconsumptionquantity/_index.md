---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يسترجع كمية الميجابايتات المعالجة."
type: docs
weight: 40
url: /ar/net/groupdocs.watermark/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

يسترجع كمية الميجابايتات المعالجة.

```csharp
public static decimal GetConsumptionQuantity()
```

### قيمة الإرجاع

كمية الميجابايتات المعالجة.

### أمثلة

المثال التالي يوضح كيفية استرجاع كمية الميجابايتات المعالجة.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### انظر أيضاً

* class [Metered](../../metered)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
