---
title: "IReleasePageStream"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "एक विधि का प्रतिनिधित्व करता है जो ऑब्जेक्ट द्वारा बनाई गई स्ट्रीम को रिलीज़ करती है।"
type: docs
weight: 81
url: /hi/java/com.groupdocs.watermark.options/ireleasepagestream/
---```
public interface IReleasePageStream
```

Represents a method which releases the stream created by `[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream)` object.

## Methods

| Method | Description |
| --- | --- |
| [releasePageStream(int pageNumber, OutputStream pageStream)](#releasePageStream-int-java.io.OutputStream-) | Releases the stream created by `[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream)` object.
 |
### releasePageStream(int pageNumber, OutputStream pageStream) {#releasePageStream-int-java.io.OutputStream-}
```
public abstract void releasePageStream(int pageNumber, OutputStream pageStream)
```


Releases the stream created by `[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream)` object.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The page number of a generated page preview.
 |
| pageStream | java.io.OutputStream | The stream containing the generated page preview.
 |

