---
title: "PagesSelector"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: 
type: docs
weight: 10
url: /hi/java/com.groupdocs.watermark/pagesselector/
---
**Inheritance:**
java.lang.Object
```
public class PagesSelector
```

<br />


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
| [PagesSelector()](#PagesSelector--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--) | निर्दिष्ट सेटअप के आधार पर पृष्ठों की सूची प्राप्त करता है। |
|
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-) | निर्दिष्ट मानदंडों के आधार पर चयनित पृष्ठों की सूची प्राप्त करता है। |
|
### PagesSelector() {#PagesSelector--}
```
public PagesSelector()
```


### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)
```


निर्दिष्ट सेटअप के आधार पर पृष्ठों की सूची प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | allPages | boolean | सभी पृष्ठों को शामिल करना है या नहीं। |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | पृष्ठ सेटअप कॉन्फ़िगरेशन। |
|
|  | totalPages | int | पृष्ठों की कुल संख्या। |
|
|  | pageIndex | com.aspose.ms.System.Nullable<java.lang.Integer> | विशिष्ट पृष्ठ सूचकांक (0 से शुरू)। |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - निर्दिष्ट सेटअप के आधार पर पृष्ठों की सूची।

### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)
```


निर्दिष्ट मानदंडों के आधार पर चयनित पृष्ठों की सूची प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | allPages | boolean | एक फ़्लैग जो दर्शाता है कि सभी पृष्ठ शामिल किए जाएँ या नहीं। |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | पृष्ठों के लिए सेटअप कॉन्फ़िगरेशन। |
|
|  | totalPages | int | दस्तावेज़ में पृष्ठों की कुल संख्या। |
|
|  | pageNumbers | int[] | शामिल करने के लिए विशिष्ट पृष्ठ संख्याओं का एक ऐरे। |
|
| fromOne | boolean |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - चयनित पृष्ठ संख्याओं की क्रमबद्ध और विशिष्ट सूची।

