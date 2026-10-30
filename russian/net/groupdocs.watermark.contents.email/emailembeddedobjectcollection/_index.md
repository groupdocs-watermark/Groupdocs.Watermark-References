---
title: "EmailEmbeddedObjectCollection"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет коллекцию встроенных объектов в электронном письме."
type: docs
weight: 380
url: /ru/net/groupdocs.watermark.contents.email/emailembeddedobjectcollection/
---
## EmailEmbeddedObjectCollection class

Представляет коллекцию встроенных объектов в электронном письме.

```csharp
public class EmailEmbeddedObjectCollection : RemoveOnlyListBase<EmailEmbeddedObject>
```

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Получает количество элементов, содержащихся в коллекции. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Возвращает значение, указывающее, является ли коллекция только для чтения. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Получает элемент по указанному индексу в коллекции. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.email/emailembeddedobjectcollection/add)(byte[], string) | Добавляет встроенный ресурс к [`EmailContent`](../emailcontent). |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(EmailEmbeddedObject) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(EmailEmbeddedObject) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(EmailEmbeddedObject) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Примечания

Эта коллекция содержит элементы типа [`EmailEmbeddedObject`](../emailembeddedobject).

### См. также

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [EmailEmbeddedObject](../emailembeddedobject)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
