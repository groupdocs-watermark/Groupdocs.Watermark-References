---
title: "GeneratePreview"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Menghasilkan gambar pratinjau untuk dokumen."
type: docs
weight: 50
url: /id/net/groupdocs.watermark/watermarker/generatepreview/
---
## Watermarker.GeneratePreview method

Menghasilkan gambar pratinjau untuk dokumen.

```csharp
public void GeneratePreview(PreviewOptions previewOptions)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| previewOptions | PreviewOptions | Opsi tambahan untuk digunakan saat menghasilkan gambar pratinjau. |

### Contoh

Hasilkan gambar pratinjau untuk halaman pertama dokumen Word.

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

### Lihat Juga

* class [PreviewOptions](../../../groupdocs.watermark.options/previewoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
