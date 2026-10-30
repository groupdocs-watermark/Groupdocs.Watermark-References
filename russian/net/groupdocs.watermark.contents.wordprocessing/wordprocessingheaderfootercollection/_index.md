---
title: "WordProcessingHeaderFooterCollection"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет коллекцию заголовков и нижних колонтитулов в документе Word."
type: docs
weight: 1370
url: /ru/net/groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/
---
## WordProcessingHeaderFooterCollection class

Представляет коллекцию заголовков и нижних колонтитулов в документе Word.

```csharp
public class WordProcessingHeaderFooterCollection : ReadOnlyListBase<WordProcessingHeaderFooter>
```

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Получает количество элементов, содержащихся в коллекции. |
| virtual [IsReadOnly](../../groupdocs.watermark.common/readonlylistbase-1/isreadonly) { get; } | Возвращает значение, указывающее, является ли коллекция только для чтения. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Получает элемент по указанному индексу в коллекции. |
| [Item](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/item) { get; } | Получает заголовок или нижний колонтитул указанного типа. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(WordProcessingHeaderFooter) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(WordProcessingHeaderFooter) |  |
| [LinkToPrevious](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/linktoprevious)(bool) | Связывает или разрывает связь всех колонтитулов с соответствующими колонтитулами в предыдущем разделе. |

### Примечания

Эта коллекция содержит элементы типа [`WordProcessingHeaderFooter`](../wordprocessingheaderfooter).

### См. также

* class [ReadOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/readonlylistbase-1)
* class [WordProcessingHeaderFooter](../wordprocessingheaderfooter)
* namespace [GroupDocs.Watermark.Contents.WordProcessing](../../groupdocs.watermark.contents.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
