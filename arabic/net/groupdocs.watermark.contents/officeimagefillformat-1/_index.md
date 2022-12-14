---
title: OfficeImageFillFormatTWatermarkableImage
second_title: GroupDocs.Watermark لـ .NET API Reference
description: يمثل إعدادات تنسيق تعبئة الصورة في أي محتوى مكتب مدعوم.
type: docs
weight: 470
url: /ar/net/groupdocs.watermark.contents/officeimagefillformat-1/
---
## OfficeImageFillFormat&lt;TWatermarkableImage&gt; class

يمثل إعدادات تنسيق تعبئة الصورة في أي محتوى مكتب مدعوم.

```csharp
public abstract class OfficeImageFillFormat<TWatermarkableImage>
    where TWatermarkableImage : WatermarkableImage
```

| معامل | وصف |
| --- | --- |
| TWatermarkableImage | النوع الدقيق للصورة القابلة للعلامة المائية المستخدمة كخلفية. |

## الخصائص

| اسم | وصف |
| --- | --- |
| abstract [BackgroundImage](../../groupdocs.watermark.contents/officeimagefillformat-1/backgroundimage) { get; set; } | الحصول على صورة الخلفية أو تعيينها . |
| abstract [TileAsTexture](../../groupdocs.watermark.contents/officeimagefillformat-1/tileastexture) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة مقسمة عبر الخلفية. |
| abstract [Transparency](../../groupdocs.watermark.contents/officeimagefillformat-1/transparency) { get; set; } | الحصول على شفافية صورة الخلفية أو تعيينها كقيمة من 0.0 (معتم) إلى 1.0 (شفافة بالكامل). |

### أنظر أيضا

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* مساحة الاسم [GroupDocs.Watermark.Contents](../../groupdocs.watermark.contents)
* المجسم [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
