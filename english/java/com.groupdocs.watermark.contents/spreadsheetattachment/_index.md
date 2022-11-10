---
title: SpreadsheetAttachment
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a file attached to an Excel document.
type: docs
weight: 101
url: /java/com.groupdocs.watermark.contents/spreadsheetattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject)
```
public class SpreadsheetAttachment extends Attachment implements ITwoDObject
```

Represents a file attached to an Excel document.
## Methods

| Method | Description |
| --- | --- |
| [getContent()](#getContent--) | Gets the attached file content. |
| [setContent(byte[] value)](#setContent-byte---) | Sets the attached file content. |
| [getPreviewImageContent()](#getPreviewImageContent--) | Gets the attached file preview image as a byte array. |
| [setPreviewImageContent(byte[] value)](#setPreviewImageContent-byte---) | Sets the attached file preview image as a byte array. |
| [isLink()](#isLink--) | Gets a value indicating whether the content contains only a link to the file. |
| [getSourceFullName()](#getSourceFullName--) | Gets the full name of the attached file. |
| [getAlternativeText()](#getAlternativeText--) | Gets the descriptive (alternative) text associated with the attached file. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Sets the descriptive (alternative) text associated with the attached file. |
| [getAsposeOleObject()](#getAsposeOleObject--) |  |
| [getX()](#getX--) | Gets the horizontal offset of the attachment frame from worksheet left border in points. |
| [setX(double value)](#setX-double-) | Sets the horizontal offset of the attachment frame from worksheet left border in points. |
| [getY()](#getY--) | Gets the vertical offset of the attachment frame from worksheet top border in points. |
| [setY(double value)](#setY-double-) | Sets the vertical offset of the attachment frame from worksheet top border in points. |
| [getWidth()](#getWidth--) | Gets the width of the attachment frame in points. |
| [setWidth(double value)](#setWidth-double-) | Sets the width of the attachment frame in points. |
| [getHeight()](#getHeight--) | Gets the height of the attachment frame in points. |
| [setHeight(double value)](#setHeight-double-) | Sets the height of the attachment frame in points. |
| [checkImageType()](#checkImageType--) |  |
### getContent() {#getContent--}
```
public byte[] getContent()
```


Gets the attached file content.

**Returns:**
byte[] - The attached file content.
### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Sets the attached file content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] | The attached file content. |

### getPreviewImageContent() {#getPreviewImageContent--}
```
public final byte[] getPreviewImageContent()
```


Gets the attached file preview image as a byte array.

**Returns:**
byte[] - The attached file preview image as a byte array.
### setPreviewImageContent(byte[] value) {#setPreviewImageContent-byte---}
```
public final void setPreviewImageContent(byte[] value)
```


Sets the attached file preview image as a byte array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] | The attached file preview image as a byte array. |

### isLink() {#isLink--}
```
public final boolean isLink()
```


Gets a value indicating whether the content contains only a link to the file.

**Returns:**
boolean - True if the attached file is referenced by a link (the content does not contain attached file content); otherwise, false.
### getSourceFullName() {#getSourceFullName--}
```
public final String getSourceFullName()
```


Gets the full name of the attached file.

**Returns:**
java.lang.String - The full name of the attached file.

--------------------

The extension is used to determine appropriate application to open the file.
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Gets the descriptive (alternative) text associated with the attached file.

**Returns:**
java.lang.String - The descriptive (alternative) text associated with the attached file.
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Sets the descriptive (alternative) text associated with the attached file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The descriptive (alternative) text associated with the attached file. |

### getAsposeOleObject() {#getAsposeOleObject--}
```
public final OleObject getAsposeOleObject()
```




**Returns:**
com.aspose.cells.OleObject
### getX() {#getX--}
```
public final double getX()
```


Gets the horizontal offset of the attachment frame from worksheet left border in points.

**Returns:**
double - The x-coordinate of the attachment frame.
### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Sets the horizontal offset of the attachment frame from worksheet left border in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The x-coordinate of the attachment frame. |

### getY() {#getY--}
```
public final double getY()
```


Gets the vertical offset of the attachment frame from worksheet top border in points.

**Returns:**
double - The y-coordinate of the attachment frame.
### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Sets the vertical offset of the attachment frame from worksheet top border in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The y-coordinate of the attachment frame. |

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Gets the width of the attachment frame in points.

**Returns:**
double - The width of the attachment frame in points.
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Sets the width of the attachment frame in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The width of the attachment frame in points. |

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Gets the height of the attachment frame in points.

**Returns:**
double - The height of the attachment frame in points.
### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Sets the height of the attachment frame in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The height of the attachment frame in points. |

### checkImageType() {#checkImageType--}
```
public final void checkImageType()
```




