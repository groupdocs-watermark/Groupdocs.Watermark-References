---
title: save method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark/watermarker/save/
is_root: false
weight: 1130
---


## save

Saves the document data to the underlying stream.

Learn more about saving the documents.

```python
def save(self):
    ...
```

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.search.searchcriteria as gws_sc

with gw.Watermarker("document.pdf") as watermarker:
    criteria = gws_sc.TextSearchCriteria("test", False)
    possible = watermarker.search(criteria)
    for wm in possible:
        try:
            wm.text = "passed"
        except Exception:
            pass
    watermarker.save("document.pdf")
```

## save {#file_path}

Saves the document to the specified file location.

Learn more about saving the documents at https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The file path to save the document data to. |

### Example

```python
    import groupdocs.watermark as gw

    with gw.Watermarker("input.pdf") as watermarker:
        watermark = gw.TextWatermark("top secret", gw.Font("Arial", 36))
        watermarker.add(watermark)
        watermarker.save("output.pdf")
    ```

## save {#document}

Saves the document to the specified stream.

Learn more about saving the documents at https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, document):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The stream to save the document data to. |

## save {#options}

Saves the document data to the underlying stream using save options.

Learn more about saving the documents.

```python
def save(self, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | `SaveOptions` | Additional options to use when saving a document. |

### Example

```python
import groupdocs.watermark as gw
from groupdocs.watermark import TextWatermark, Font

with gw.Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    # Save the document with default options
    watermarker.save("output.pdf")
```

## save {#file_path-options}

Saves the document to the specified file location using save options.

Learn more about saving the documents.

```python
def save(self, file_path, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The file path to save the document data to. |
| options | `SaveOptions` | Additional options to use when saving a document. |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.search.searchcriteria as gws_sc

with gw.Watermarker("document.pdf") as watermarker:
    criteria = gws_sc.TextSearchCriteria("test", False)
    for wm in watermarker.search(criteria):
        try:
            wm.text = "passed"
        except Exception:
            pass
    watermarker.save("document.pdf")
```

## save {#document-options}

Saves the document to the specified stream using save options.

Learn more about saving the documents at the GroupDocs documentation.

```python
def save(self, document, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The stream to save the document data to. |
| options | `SaveOptions` | Additional options to use when saving a document. |

### Example

```python
import groupdocs.watermark as gw
from io import BytesIO
from groupdocs.watermark.options import SaveOptions

with gw.Watermarker("input.pdf") as watermarker:
    watermark = gw.TextWatermark("top secret", gw.Font("Arial", 36))
    watermarker.add(watermark)
    stream = BytesIO()
    watermarker.save(stream, SaveOptions())
    # stream now contains the saved document
```

### See Also
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
