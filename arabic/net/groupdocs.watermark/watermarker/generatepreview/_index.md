---
title: GeneratePreview
second_title: GroupDocs.Watermark لـ .NET API Reference
description: يولد معاينة الصور للوثيقة .
type: docs
weight: 50
url: /ar/net/groupdocs.watermark/watermarker/generatepreview/
---
## Watermarker.GeneratePreview method

يولد معاينة الصور للوثيقة .

```csharp
public void GeneratePreview(PreviewOptions previewOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| previewOptions | PreviewOptions | خيارات إضافية لاستخدامها عند إنشاء صور المعاينة. |

### أمثلة

إنشاء صورة معاينة للصفحة الأولى من مستند Word .

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

### أنظر أيضا

* class [PreviewOptions](../../../groupdocs.watermark.options/previewoptions)
* class [Watermarker](../../watermarker)
* مساحة الاسم [GroupDocs.Watermark](../../watermarker)
* المجسم [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->