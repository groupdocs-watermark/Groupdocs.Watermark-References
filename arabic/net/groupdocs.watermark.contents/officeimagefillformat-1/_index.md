---
title: "OfficeImageFillFormatTWatermarkableImage"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل إعدادات تنسيق تعبئة الصورة في أي محتوى مكتبي مدعوم."
type: docs
weight: 520
url: /ar/net/groupdocs.watermark.contents/officeimagefillformat-1/
---
## OfficeImageFillFormat&lt;TWatermarkableImage&gt; class

يمثل إعدادات تنسيق تعبئة الصورة في أي محتوى مكتبي مدعوم.

```csharp
public abstract class OfficeImageFillFormat<TWatermarkableImage>
    where TWatermarkableImage : WatermarkableImage
```

| معامل | الوصف |
| --- | --- |
| TWatermarkableImage | النوع الدقيق للصورة القابلة للعلامة المائية المستخدمة كخلفية. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| abstract [BackgroundImage](../../groupdocs.watermark.contents/officeimagefillformat-1/backgroundimage) { get; set; } | يحصل أو يعيّن صورة الخلفية. |
| abstract [TileAsTexture](../../groupdocs.watermark.contents/officeimagefillformat-1/tileastexture) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الصورة مكررة عبر الخلفية. |
| abstract [Transparency](../../groupdocs.watermark.contents/officeimagefillformat-1/transparency) { get; set; } | يحصل أو يعيّن شفافية صورة الخلفية كقيمة من 0.0 (معتمة) إلى 1.0 (شفافة تمامًا). |

### انظر أيضاً

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* namespace [GroupDocs.Watermark.Contents](../../groupdocs.watermark.contents)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
