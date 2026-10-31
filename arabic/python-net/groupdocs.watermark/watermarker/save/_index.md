---
title: "طريقة save"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يحفظ بيانات المستند إلى الدفق الأساسي."
type: docs
url: /ar/python-net/groupdocs.watermark/watermarker/save/
is_root: false
weight: 1130
---


## save

يحفظ بيانات المستند إلى الدفق الأساسي.

تعرف على المزيد حول حفظ المستندات: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self):
    ...
```

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker(r"D:\\test.msg") as watermarker:
    criteria = TextSearchCriteria("test", False)
    watermarks = watermarker.search(criteria)
    watermarker.remove(watermarks)
    watermarker.save()
```

## save {#file_path}

يحفظ المستند إلى موقع الملف المحدد.

تعرف على المزيد حول حفظ المستندات: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار الملف لحفظ بيانات المستند إليه. |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

def add_and_save():
    with Watermarker("input.pdf") as watermarker:
        watermark = TextWatermark("top secret", Font("Arial", 36))
        watermarker.add(watermark)
        watermarker.save("output.pdf")
```

## save {#document}

يحفظ المستند إلى الدفق المحدد.

تعرف على المزيد حول حفظ المستندات على https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, document):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| document | `io.RawIOBase` | الدفق لحفظ بيانات المستند إليه. |

### مثال

```python
from io import BytesIO
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    stream = BytesIO()
    watermarker.save(stream)
    # `stream` الآن يحتوي على بايتات PDF المحفوظة
```

## save {#options}

يحفظ بيانات المستند إلى الدفق الأساسي باستخدام خيارات الحفظ.

تعرف على المزيد حول حفظ المستندات.

```python
def save(self, options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | `SaveOptions` | خيارات إضافية لاستخدامها عند حفظ المستند. |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import SaveOptions
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    watermarker.save(SaveOptions())
```

## save {#file_path-options}

يحفظ المستند إلى موقع الملف المحدد باستخدام خيارات الحفظ.

تعرف على المزيد حول حفظ المستندات: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path, options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار الملف لحفظ بيانات المستند إليه. |
| options | `SaveOptions` | خيارات إضافية لاستخدامها عند حفظ المستند. |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font
from groupdocs.watermark.options import SaveOptions

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    watermarker.save("output.pdf", SaveOptions())
```

## save {#document-options}

يحفظ المستند إلى الدفق المحدد باستخدام خيارات الحفظ.

تعرف على المزيد حول حفظ المستندات في وثائق GroupDocs.

```python
def save(self, document, options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| document | `io.RawIOBase` | الدفق لحفظ بيانات المستند إليه. |
| options | `SaveOptions` | خيارات إضافية لاستخدامها عند حفظ المستند. |

### مثال

```python
from io import BytesIO
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import SaveOptions
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

def add_watermark_and_save():
    with Watermarker("input.pdf") as watermarker:
        watermark = TextWatermark("top secret", Font("Arial", 36))
        watermarker.add(watermark)

        stream = BytesIO()
        watermarker.save(stream, SaveOptions())
        # stream الآن يحتوي على بيانات PDF المحفوظة
        # مثلاً، اكتب إلى ملف
        with open("output.pdf", "wb") as f:
            f.write(stream.getvalue())

if __name__ == "__main__":
    add_watermark_and_save()
```

### انظر أيضًا
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
