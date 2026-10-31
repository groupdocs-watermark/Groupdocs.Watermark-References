---
title: "文档预览"
linkTitle: "Document preview"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "使用 GroupDocs.Watermark for Python via .NET 为文档页面生成预览图像（PNG/JPG/BMP）。"
type: docs
url: /zh/python-net/guides/preview/
is_root: false
weight: 110
---


GroupDocs.Watermark 可以将文档页面渲染为图像，从而在不完全打开文档查看器的情况下显示页面缩略图。您可以使用 `create_page_stream` 回调来驱动渲染，该回调为每页提供可写的文件流——库会将页面图像写入该流并为您关闭它。

## Generate a document preview

使用带有 `create_page_stream` 回调的 [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)，选择 `preview_format`，并列出要渲染的 `page_numbers`。

{{< tabs "code-example-preview">}}
{{< tab "generate_preview.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # 为每个要渲染的页面提供可写文件流
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` 是本示例使用的两页示例文件。点击 [此处](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/preview/sample.pdf) 下载它。

{{< /tab >}}
{{< tab "generate-preview-outputs.zip" >}}
```text
output-page-1.png (600 KB)
output-page-2.png (94 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/preview/generate_preview/generate-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

页面图像会写入当前目录——每个请求的页面生成一个 PNG。对于其他格式，请使用 `PreviewFormats.JPEG` 或 `PreviewFormats.BMP`，并设置 `options.width` / `options.height` 以控制渲染尺寸。

库会在页面写入后关闭 `create_page_stream` 返回的每个文件。若要在页面准备好后立即处理它，请传入第二个回调：`PreviewOptions(create_page_stream, release_page_stream)` 会在整个图像写入后调用 `release_page_stream(page_number, stream)`，并将该页面返回的 `create_page_stream` 对象作为参数。也可以使用单参数 `release_page_stream(page_number)`。`create_page_stream` 还可以返回一个 `io.BytesIO`：它保持打开状态，并在 `release_page_stream` 获取时仍保存页面图像。

**Use case:** Generate page previews to display in a web app, dashboard, or document-management system without requiring users to download the full file.
