---
title: "License"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Предоставляет методы лицензирования компонента."
type: docs
weight: 1680
url: /ru/net/groupdocs.watermark/license/
---
## License class

Предоставляет методы лицензирования компонента.

```csharp
public sealed class License
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [License](license)() | Инициализирует новый экземпляр класса [`License`](../license). |

## Методы

| Имя | Описание |
| --- | --- |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense)(Stream) | Лицензирует компонент. |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense_1)(string) | Лицензирует компонент. |

### Примечания

* More about licensing: [GroupDocs Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### Примеры

Этот пример демонстрирует, как настроить лицензию из локального файла.

```csharp
// Инициализировать класс License.
License license = new License();

// Установите путь к файлу .lic.
license.SetLicense("C:\\GroupDocs.Watermark.lic");
```

### См. также

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
