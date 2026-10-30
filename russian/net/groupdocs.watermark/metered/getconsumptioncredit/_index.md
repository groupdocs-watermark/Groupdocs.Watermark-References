---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Возвращает количество использованных кредитов."
type: docs
weight: 30
url: /ru/net/groupdocs.watermark/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Возвращает количество использованных кредитов.

```csharp
public static long GetConsumptionCredit()
```

### Возвращаемое значение

Количество использованных кредитов.

### Примеры

Следующий пример демонстрирует, как получить количество использованных кредитов.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### См. также

* class [Metered](../../metered)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
