---
title: GeneratePreview
second_title: .NET API Başvurusu için GroupDocs.Watermark
description: Belge için önizleme görüntüleri oluşturur.
type: docs
weight: 50
url: /tr/net/groupdocs.watermark/watermarker/generatepreview/
---
## Watermarker.GeneratePreview method

Belge için önizleme görüntüleri oluşturur.

```csharp
public void GeneratePreview(PreviewOptions previewOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| previewOptions | PreviewOptions | Önizleme görüntüleri oluştururken kullanılacak ek seçenekler. |

### Örnekler

Word belgesinin ilk sayfası için önizleme görüntüsü oluşturun.

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

### Ayrıca bakınız

* class [PreviewOptions](../../../groupdocs.watermark.options/previewoptions)
* class [Watermarker](../../watermarker)
* ad alanı [GroupDocs.Watermark](../../watermarker)
* toplantı [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->