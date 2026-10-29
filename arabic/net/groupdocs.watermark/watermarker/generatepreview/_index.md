---
title: "GeneratePreview"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "ينشئ صورًا معاينة للمستند."
type: docs
weight: 50
url: /ar/net/groupdocs.watermark/watermarker/generatepreview/
---
## Watermarker.GeneratePreview method

ينشئ صورًا معاينة للمستند.

```csharp
public void GeneratePreview(PreviewOptions previewOptions)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| previewOptions | PreviewOptions | خيارات إضافية للاستخدام عند إنشاء صور المعاينة. |

### أمثلة

إنشاء صورة معاينة للصفحة الأولى من مستند Word.

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

### انظر أيضاً

* class [PreviewOptions](../../../groupdocs.watermark.options/previewoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
