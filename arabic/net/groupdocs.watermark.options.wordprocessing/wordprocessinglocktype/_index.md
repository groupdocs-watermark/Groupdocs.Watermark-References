---
title: "WordProcessingLockType"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يحدد نوع قفل العلامة المائية في وثيقة Word."
type: docs
weight: 2350
url: /ar/net/groupdocs.watermark.options.wordprocessing/wordprocessinglocktype/
---
## WordProcessingLockType enumeration

يحدد نوع قفل العلامة المائية في وثيقة Word.

```csharp
public enum WordProcessingLockType
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| AllowOnlyRevisions | `0` | يمكن للمستخدم فقط إضافة علامات المراجعة إلى المستند. |
| AllowOnlyComments | `1` | يمكن للمستخدم فقط تعديل التعليقات في المستند. |
| AllowOnlyFormFields | `2` | يمكن للمستخدم فقط إدخال البيانات في حقول النموذج داخل المستند. |
| ReadOnly | `3` | المستند بالكامل للقراءة فقط. |
| ReadOnlyWithEditableContent | `4` | المستند للقراءة فقط، لكن جميع المحتوى باستثناء العلامة المائية مُعلَّم كقابل للتحرير. |
| NoLock | `-1` | تعطيل أي قفل على العلامة المائية والمستند. |

### انظر أيضاً

* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
