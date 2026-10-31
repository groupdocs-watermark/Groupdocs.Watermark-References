---
title: "طريقة set_license"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "تطبيق ترخيص على العملية الحالية."
type: docs
url: /ar/python-net/groupdocs.watermark/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

تطبيق ترخيص على العملية الحالية.

```python
def set_license(self, license_source):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| license_source |  | إما مسار سلسلة إلى ملف ``.lic`` أو كائن شبيه بالملف قابل للقراءة يُعيد بايتات الترخيص. يتم كتابة المدخلات الشبيهة بالملف إلى ملف مؤقت قبل تمريره إلى الجسر. |

| يطرح | الوصف |
| :- | :- |
| `TypeError` | إذا لم يكن ``license_source`` مسار سلسلة ولا كائن شبيه بالملف قابل للقراءة. |

### انظر أيضًا
* class [`License`](/watermark/python-net/groupdocs.watermark/license/)
