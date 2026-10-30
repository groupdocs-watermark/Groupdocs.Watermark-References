---
title: "InpaintingMethod"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Указывает алгоритм, используемый для восстановления изображения."
type: docs
weight: 80
url: /ru/net/groupdocs.watermark.common/inpaintingmethod/
---
## InpaintingMethod enumeration

Указывает алгоритм, используемый для восстановления изображения.

```csharp
public enum InpaintingMethod
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| PatchBased | `0` | Заполнение на основе патчей (в стиле Криминиси). Находит похожие текстурные патчи в известной области и копирует их в маску. |
| Telea | `1` | Алгоритм Telea. Быстрый метод марша, который распространяет значения пикселей от границы области внутрь. |

### См. также

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
