---
title: "FromExtension"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Отображает расширение файла на тип файла."
type: docs
weight: 590
url: /ru/net/groupdocs.watermark.common/filetype/fromextension/
---
## FileType.FromExtension method

Отображает расширение файла на тип файла.

```csharp
public static FileType FromExtension(string extension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| расширение | String | Расширение файла (включая точку "."). |

### Возвращаемое значение

Если тип файла поддерживается, возвращает его, в противном случае возвращает тип файла по умолчанию [`Unknown`](../unknown).

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *extension* равно null или пустой строке. |

### См. также

* class [FileType](../../filetype)
* namespace [GroupDocs.Watermark.Common](../../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
