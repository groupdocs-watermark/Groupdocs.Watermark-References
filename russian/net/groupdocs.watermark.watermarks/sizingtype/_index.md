---
title: "SizingType"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Указывает, как следует рассчитывать размер водяного знака."
type: docs
weight: 3300
url: /ru/net/groupdocs.watermark.watermarks/sizingtype/
---
## SizingType enumeration

Указывает, как следует рассчитывать размер водяного знака.

```csharp
public enum SizingType
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Auto | `0` | Водяной знак должен автоматически масштабироваться в соответствии с его содержимым. |
| Absolute | `1` | Водяной знак должен быть задан точными [`Width`](../../groupdocs.watermark/watermark/width) и [`Height`](../../groupdocs.watermark/watermark/height). |
| ScaleToParentDimensions | `2` | Водяной знак должен масштабироваться относительно размеров родителя, используя указанный [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor). |
| ScaleToParentArea | `3` | Водяной знак должен масштабироваться относительно площади родителя, используя указанный [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor). |

### См. также

* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
