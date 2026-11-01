---
title: "generate_preview メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "ドキュメントのプレビュー画像を生成します。"
type: docs
url: /ja/python-net/groupdocs.watermark/watermarker/generate_preview/
is_root: false
weight: 1040
---


## generate_preview {#preview_options}

ドキュメントのプレビュー画像を生成します。

```python
def generate_preview(self, preview_options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| preview_options | `PreviewOptions` | プレビュー画像を生成する際に使用する追加オプション。 |

### 例

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.options import PreviewOptions, PreviewFormats

    def generate_preview():
        # 各ページをレンダリングするための書き込み可能なファイルストリームを提供します
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

### 関連項目
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
