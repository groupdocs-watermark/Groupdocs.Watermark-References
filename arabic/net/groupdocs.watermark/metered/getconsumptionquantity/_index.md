---
title: GetConsumptionQuantity
second_title: GroupDocs.Watermark لـ .NET API Reference
description: استرداد كمية الميغابايت التي تمت معالجتها .
type: docs
weight: 40
url: /ar/net/groupdocs.watermark/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

استرداد كمية الميغابايت التي تمت معالجتها .

```csharp
public static decimal GetConsumptionQuantity()
```

### قيمة الإرجاع

كمية الميغابايت التي تمت معالجتها.

### أمثلة

المثال التالي يوضح كيفية استرداد كمية الميغابايت التي تمت معالجتها.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### أنظر أيضا

* class [Metered](../../metered)
* مساحة الاسم [GroupDocs.Watermark](../../metered)
* المجسم [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->