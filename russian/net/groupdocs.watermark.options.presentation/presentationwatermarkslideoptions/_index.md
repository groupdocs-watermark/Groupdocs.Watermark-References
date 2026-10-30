---
title: "PresentationWatermarkSlideOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет параметры при добавлении водяного знака в слайд документа Presentation."
type: docs
weight: 2130
url: /ru/net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/
---
## PresentationWatermarkSlideOptions class

Представляет параметры при добавлении водяного знака в слайд документа Presentation.

```csharp
public sealed class PresentationWatermarkSlideOptions : PresentationWatermarkBaseSlideOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PresentationWatermarkSlideOptions](presentationwatermarkslideoptions)() | Инициализирует новый экземпляр класса [`PresentationWatermarkSlideOptions`](../presentationwatermarkslideoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternativetext) { get; set; } | Получает или задает описательный (альтернативный) текст, который будет связан с фигурой. |
| [Effects](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects) { get; set; } | Получает или задает значение [`PresentationImageEffects`](../presentationimageeffects) или [`PresentationTextEffects`](../presentationtexteffects) для эффектов, которые должны быть применены к водяному знаку. |
| [IsLocked](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/islocked) { get; set; } | Получает или задает значение, указывающее, запрещено ли редактирование фигуры в PowerPoint. |
| [Name](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name) { get; set; } | Получает или задает имя фигуры. |
| [ProtectWithUnreadableCharacters](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protectwithunreadablecharacters) { get; set; } | Получает или задает значение, указывающее, смешаны ли символы текстового водяного знака с нечитаемыми символами. |
| [SlideIndex](../../groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/slideindex) { get; set; } | Получает или задает индекс слайда, к которому будет добавлен водяной знак. |

### Примечания

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

### Примеры

Добавить водяной знак к определённому слайду презентации PowerPoint.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.ppt", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
    watermark.HorizontalAlignment = HorizontalAlignment.Center;
    watermark.VerticalAlignment = VerticalAlignment.Center;

    PresentationWatermarkSlideOptions options = new PresentationWatermarkSlideOptions();
    options.SlideIndex = 0;
    options.IsLocked = false; // default
    options.ProtectWithUnreadableCharacters = false; // default
    options.Name = null; // default
    options.AlternativeText = null; // default

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### См. также

* class [PresentationWatermarkBaseSlideOptions](../presentationwatermarkbaseslideoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
