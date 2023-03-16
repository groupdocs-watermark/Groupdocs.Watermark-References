---
title: SpreadsheetAttachment
second_title: .NET API Başvurusu için GroupDocs.Watermark
description: Bir Excel belgesine eklenmiş bir dosyayı temsil eder.
type: docs
weight: 1030
url: /tr/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/
---
## SpreadsheetAttachment class

Bir Excel belgesine eklenmiş bir dosyayı temsil eder.

```csharp
public class SpreadsheetAttachment : Attachment, ITwoDObject
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/alternativetext) { get; set; } | Ekli dosyayla ilişkili açıklayıcı (alternatif) metni alır veya ayarlar. |
| override [Content](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/content) { get; set; } | Ekli dosya içeriğini alır veya ayarlar. |
| [Height](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/height) { get; set; } | Bağlantı çerçevesinin yüksekliğini puan cinsinden alır veya ayarlar. |
| [IsLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/islink) { get; } | İçeriğin yalnızca dosyaya bir bağlantı içerip içermediğini gösteren bir değer alır. |
| [PreviewImageContent](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/previewimagecontent) { get; set; } | Ekli dosya önizleme görüntüsünü bir bayt dizisi olarak alır veya ayarlar. |
| [SourceFullName](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/sourcefullname) { get; } | Ekli dosyanın tam adını alır. |
| [Width](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/width) { get; set; } | Ek çerçevenin genişliğini noktalar olarak alır veya ayarlar. |
| [X](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/x) { get; set; } | Çalışma sayfasının sol sınırından ek çerçevesinin yatay uzaklığını noktalar olarak alır veya ayarlar. |
| [Y](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/y) { get; set; } | Çalışma sayfası üst sınırından ek çerçevesinin dikey uzaklığını noktalar olarak alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | Ekli dosyadan bir içerik yükler. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | Belirtilen yükleme seçenekleriyle ekli dosyadan bir içerik yükler. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | Belirtilen yükleme seçenekleri ve ayarlarla ekli dosyadan bir içerik yükler. |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | Ekli dosyada saklanan bir belge hakkında bilgi alır. |

### Ayrıca bakınız

* class [Attachment](../../groupdocs.watermark.common/attachment)
* interface [ITwoDObject](../../groupdocs.watermark.search/itwodobject)
* ad alanı [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* toplantı [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->