---
title: "WordProcessingLockType"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Указывает тип блокировки водяного знака в документе Word."
type: docs
weight: 2350
url: /ru/net/groupdocs.watermark.options.wordprocessing/wordprocessinglocktype/
---
## WordProcessingLockType enumeration

Указывает тип блокировки водяного знака в документе Word.

```csharp
public enum WordProcessingLockType
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| AllowOnlyRevisions | `0` | Пользователь может только добавлять метки правок в документ. |
| AllowOnlyComments | `1` | Пользователь может только изменять комментарии в документе. |
| AllowOnlyFormFields | `2` | Пользователь может только вводить данные в поля формы в документе. |
| ReadOnly | `3` | Весь документ доступен только для чтения. |
| ReadOnlyWithEditableContent | `4` | Документ доступен только для чтения, но всё содержимое, кроме водяного знака, помечено как редактируемое. |
| NoLock | `-1` | Отключить любые блокировки водяного знака и документа. |

### См. также

* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
