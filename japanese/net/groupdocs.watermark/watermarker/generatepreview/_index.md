---
title: "GeneratePreview"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "ドキュメントのプレビュー画像を生成します。"
type: docs
weight: 50
url: /ja/net/groupdocs.watermark/watermarker/generatepreview/
---
## Watermarker.GeneratePreview method

ドキュメントのプレビュー画像を生成します。

```csharp
public void GeneratePreview(PreviewOptions previewOptions)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| previewOptions | PreviewOptions | プレビュー画像を生成する際に使用する追加オプションです。 |

### 例

Word ドキュメントの最初のページのプレビュー画像を生成します。

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

### 関連項目

* class [PreviewOptions](../../../groupdocs.watermark.options/previewoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
