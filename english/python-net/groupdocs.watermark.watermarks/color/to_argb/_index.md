---
title: to_argb method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.watermarks/color/to_argb/
is_root: false
weight: 1100
---


## to_argb

Returns the 32-bit ARGB value of this Color structure.

```python
def to_argb(self):
    ...
```

**Returns:** The 32-bit ARGB value of this Color structure.

### Example

```python
    import groupdocs.watermark as gw
    import groupdocs.watermark.contents.diagram as gwc_vsdx

    load_options = gw.DiagramLoadOptions()
    with gw.Watermarker("diagram.vsdx", load_options) as watermarker:
        content = watermarker.get_content(gwc_vsdx.DiagramContent)
        argb = content.header_footer.text_color.to_argb()
        print(argb)
    ```

### See Also
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
