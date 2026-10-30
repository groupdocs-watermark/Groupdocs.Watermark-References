---
title: "Metered"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Предоставляет методы лицензирования компонента с измеряемой лицензией."
type: docs
weight: 1690
url: /ru/net/groupdocs.watermark/metered/
---
## Metered class

Предоставляет методы лицензирования компонента с измеряемой лицензией.

```csharp
public class Metered
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Metered](metered)() | Инициализирует новый экземпляр класса [`Metered`](../metered). |

## Методы

| Имя | Описание |
| --- | --- |
| [SetMeteredKey](../../groupdocs.watermark/metered/setmeteredkey)(string, string) | Активирует продукт с ключами Metered. |
| static [GetConsumptionCredit](../../groupdocs.watermark/metered/getconsumptioncredit)() | Возвращает количество использованных кредитов. |
| static [GetConsumptionQuantity](../../groupdocs.watermark/metered/getconsumptionquantity)() | Возвращает объём обработанных мегабайт. |

### Примечания

**Learn more**

* More about Metered licensing: [Metered Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing/metered)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### Примеры

Следующий пример демонстрирует, как активировать продукт с помощью Metered keys.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### См. также

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
