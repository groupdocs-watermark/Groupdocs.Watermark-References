---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Возвращает объём обработанных мегабайт."
type: docs
weight: 40
url: /ru/net/groupdocs.watermark/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Возвращает объём обработанных мегабайт.

```csharp
public static decimal GetConsumptionQuantity()
```

### Возвращаемое значение

Количество обработанных мегабайт.

### Примеры

Следующий пример демонстрирует, как получить количество обработанных мегабайт.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### См. также

* class [Metered](../../metered)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
