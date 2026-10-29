---
title: "GeneratePreview"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "为文档生成预览图像。"
type: docs
weight: 50
url: /zh/net/groupdocs.watermark/watermarker/generatepreview/
---
## Watermarker.GeneratePreview method

为文档生成预览图像。

```csharp
public void GeneratePreview(PreviewOptions previewOptions)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| previewOptions | PreviewOptions | 生成预览图像时使用的其他选项。 |

### 示例

为 Word 文档的第一页生成预览图像。

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

### 另请参阅

* class [PreviewOptions](../../../groupdocs.watermark.options/previewoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
