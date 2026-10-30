---
title: "GeneratePreview"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Создаёт предварительные изображения для документа."
type: docs
weight: 50
url: /ru/net/groupdocs.watermark/watermarker/generatepreview/
---
## Watermarker.GeneratePreview method

Создаёт предварительные изображения для документа.

```csharp
public void GeneratePreview(PreviewOptions previewOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| previewOptions | PreviewOptions | Дополнительные параметры, используемые при создании изображений предварительного просмотра. |

### Примеры

Создать изображение предварительного просмотра первой страницы документа Word.

```csharp
CreatePageStream createPageStreamDelegate = delegate(int number)
                                            {
                                                string previewImageFileName = string.Format("page{0}.png", number);
                                                return File.OpenWrite(previewImageFileName);
                                            };
ReleasePageStream releasePageStreamDelegate = delegate(int number, Stream stream)
                                              {
                                                  stream.Close();
                                              };
PreviewOptions previewOptions = new PreviewOptions(createPageStreamDelegate, releasePageStreamDelegate)
                                {
                                    PreviewFormat = PreviewOptions.PreviewFormats.PNG,
                                    PageNumbers = new []{1}
                                };

using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.docx"))
{
    watermarker.GeneratePreview(previewOptions);
}
```

### См. также

* class [PreviewOptions](../../../groupdocs.watermark.options/previewoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
