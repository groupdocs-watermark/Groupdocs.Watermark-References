---
title: "RemoveOnlyListBaseT"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Предоставляет абстрактный базовый класс для строго типизированного списка только для удаления."
type: docs
weight: 130
url: /ru/net/groupdocs.watermark.common/removeonlylistbase-1/
---
## RemoveOnlyListBase&lt;T&gt; class

Предоставляет абстрактный базовый класс для строго типизированного списка только для удаления.

```csharp
public abstract class RemoveOnlyListBase<T> : ReadOnlyListBase<T>
```

| Параметр | Описание |
| --- | --- |
| T | Тип элемента. |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Получает количество элементов, содержащихся в коллекции. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Возвращает значение, указывающее, является ли коллекция только для чтения. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Получает элемент по указанному индексу в коллекции. |

## Методы

| Имя | Описание |
| --- | --- |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() | Удаляет все элементы из коллекции. |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(T) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(T) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(T) | Удаляет первое вхождение указанного объекта из коллекции. |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) | Удаляет элемент по указанному индексу. |

### См. также

* class [ReadOnlyListBase&lt;T&gt;](../readonlylistbase-1)
* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
