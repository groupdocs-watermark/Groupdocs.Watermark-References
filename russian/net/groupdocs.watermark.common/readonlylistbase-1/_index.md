---
title: "ReadOnlyListBaseT"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Предоставляет абстрактный базовый класс для строго типизированного списка только для чтения."
type: docs
weight: 110
url: /ru/net/groupdocs.watermark.common/readonlylistbase-1/
---
## ReadOnlyListBase&lt;T&gt; class

Предоставляет абстрактный базовый класс для строго типизированного списка только для чтения.

```csharp
public abstract class ReadOnlyListBase<T> : IList, IList<T>
```

| Параметр | Описание |
| --- | --- |
| T | Тип элемента. |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Получает количество элементов, содержащихся в коллекции. |
| virtual [IsReadOnly](../../groupdocs.watermark.common/readonlylistbase-1/isreadonly) { get; } | Возвращает значение, указывающее, является ли коллекция только для чтения. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Получает элемент по указанному индексу в коллекции. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(T) | Определяет, содержит ли коллекция конкретный элемент. |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() | Возвращает перечислитель, который перебирает элементы коллекции. |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(T) | Определяет индекс конкретного элемента в коллекции. |

### См. также

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
