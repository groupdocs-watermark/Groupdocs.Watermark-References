---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يُنشئ مثيلاً جديدًا من ImageDctHashSearchCriteria بمسار ملف محدد."
type: docs
url: /ar/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

يُنشئ مثيلاً جديدًا من ImageDctHashSearchCriteria بمسار ملف محدد.

```python
def __init__(self, file_path):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار الملف لتحميل الصورة منه. |

### مثال

```python
    from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

    criteria = ImageDctHashSearchCriteria("./logo.png")
    ```

## __init__ {#stream}

يُنشئ مثيلاً جديدًا من ImageDctHashSearchCriteria باستخدام تدفق الصورة المقدم.

```python
def __init__(self, stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream | `io.RawIOBase` | الدفق لتحميل الصورة منه. |

### انظر أيضًا
* class [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)
