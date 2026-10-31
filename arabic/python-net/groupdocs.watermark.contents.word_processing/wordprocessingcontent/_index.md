---
title: "فئة WordProcessingContent"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل مستند Word (doc، docx، إلخ) حيث يمكن وضع علامة مائية."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/
is_root: false
weight: 10
---


## WordProcessingContent class

يمثل مستند Word (doc، docx، إلخ) حيث يمكن وضع علامة مائية.

اعرف المزيد:
- Add watermarks to word processing documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents
- Existing objects in word processing document: https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+word+processing+document
- Locking watermark in word processing document: https://docs.groupdocs.com/display/watermarknet/Locking+watermark+in+word+processing+document
- Protecting word processing documents: https://docs.groupdocs.com/display/watermarknet/Protecting+word+processing+documents
- Watermarks in word processing document: https://docs.groupdocs.com/display/watermarknet/Watermarks+in+word+processing+document

نوع WordProcessingContent يعرض الأعضاء التالية:

### الطرق
| طريقة | الوصف |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/decrypt/) | يفك تشفير المستند. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt/#password) | يشفر المستند. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt_string/) |  |
| [protect](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/#protection_type-password) | يحمي المستند من التغييرات ويحدد كلمة مرور الحماية. |
| [protect_file](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_file/) |  |
| [protect_string](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_string/) |  |
| [protect_word_processing_protection_type](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_word_processing_protection_type/) |  |
| [unprotect](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/) | يزيل الحماية من المستند بغض النظر عن كلمة المرور. |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | يتخلص من المثيل الحالي. (موروث من [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | يبحث عن الصور وفقًا لمعايير البحث المحددة. يتم البحث في الكائنات المحددة في [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | يبحث عن العلامات المائية المحتملة وفقًا لمعايير البحث المحددة. يتم البحث على الكائنات المدرجة في [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [page_count](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/page_count/) | عدد الصفحات في المستند. |
| [sections](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/sections/) | مجموعة جميع أقسام هذا [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/). |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
with Watermarker("input.docx", load_options) as watermarker:
    # أضف علامة مائية إلى قسم معين أو جميع الأقسام هنا إذا لزم الأمر.
    watermarker.save("output.docx")
```

### انظر أيضًا
* module [`groupdocs.watermark.contents.word_processing`](/watermark/python-net/groupdocs.watermark.contents.word_processing/)
