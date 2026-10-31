---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "初始化 PresentationLoadOptions 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

初始化 [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/) 类的新实例。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

def remove_slide_background():
    with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.slides[0].image_fill_format.background_image = None
        watermarker.save("./output.pptx")
```

## __init__ {#password}

使用指定密码初始化 PresentationLoadOptions 类的新实例。

```python
def __init__(self, password):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| password | `str` | 用于打开加密内容的密码。 |

### 示例

```python
    import groupdocs.watermark as gw
    from groupdocs.watermark.options.presentation import PresentationLoadOptions

    load_options = PresentationLoadOptions()
    ```

### 另请参见
* class [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/)
