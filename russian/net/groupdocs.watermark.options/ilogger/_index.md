---
title: ILogger
second_title: Справочник по API GroupDocs.Watermark для .NET
description: Определяет интерфейс регистратора который используется для регистрации событий и ошибок во время водяных знаков.
type: docs
weight: 1730
url: /ru/net/groupdocs.watermark.options/ilogger/
---
## ILogger interface

Определяет интерфейс регистратора, который используется для регистрации событий и ошибок во время водяных знаков.

```csharp
public interface ILogger
```

## Методы

| Имя | Описание |
| --- | --- |
| [Error](../../groupdocs.watermark.options/ilogger/error)(string, Exception) | Регистрирует ошибку, возникшую во время добавления водяных знаков. |
| [Trace](../../groupdocs.watermark.options/ilogger/trace)(string) | Регистрирует событие, произошедшее во время нанесения водяных знаков. |
| [Warning](../../groupdocs.watermark.options/ilogger/warning)(string) | Записывает предупреждение, возникшее во время нанесения водяных знаков. |

### Смотрите также

* пространство имен [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* сборка [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
