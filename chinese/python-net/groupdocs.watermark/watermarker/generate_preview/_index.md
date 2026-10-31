---
title: "generate_preview 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "为文档生成预览图像。"
type: docs
url: /zh/python-net/groupdocs.watermark/watermarker/generate_preview/
is_root: false
weight: 1040
---


## generate_preview {#preview_options}

为文档生成预览图像。

```python
def generate_preview(self, preview_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| preview_options | `PreviewOptions` | 生成预览图像时使用的其他选项。 |

### 示例

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

### 另请参见
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
