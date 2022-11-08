---
title: WordProcessingShapeSettings
second_title: GroupDocs.Watermark for Java API Reference
description: Represents settings that can be applied to a shape watermark for a Word document.
type: docs
weight: 71
url: /java/com.groupdocs.watermark.options/wordprocessingshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class WordProcessingShapeSettings extends OfficeShapeSettings
```

Represents settings that can be applied to a shape watermark for a Word document.
## Constructors

| Constructor | Description |
| --- | --- |
| [WordProcessingShapeSettings()](#WordProcessingShapeSettings--) | Initializes a new instance of the `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)` class. |
## Methods

| Method | Description |
| --- | --- |
| [isLocked()](#isLocked--) | Gets a value indicating whether an editing of the shape in Word is forbidden. |
| [setLocked(boolean value)](#setLocked-boolean-) | Sets a value indicating whether an editing of the shape in Word is forbidden. |
| [getLockType()](#getLockType--) | Gets the watermark lock type. |
| [setLockType(int value)](#setLockType-int-) | Sets the watermark lock type. |
| [getPassword()](#getPassword--) | Gets a password used to lock the watermark. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Sets a password used to lock the watermark. |
| [getPageNumbers()](#getPageNumbers--) | Gets the page numbers to add the watermark. |
| [setPageNumbers(int[] value)](#setPageNumbers-int---) | Sets the page numbers to add the watermark. |
### WordProcessingShapeSettings() {#WordProcessingShapeSettings--}
```
public WordProcessingShapeSettings()
```


Initializes a new instance of the `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)` class.

### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Gets a value indicating whether an editing of the shape in Word is forbidden.

**Returns:**
boolean - If the value is  true , shape editing will be forbidden. By default, the value is  false , the shape can be edited in Word.
### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Sets a value indicating whether an editing of the shape in Word is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | If the value is  true , shape editing will be forbidden. By default, the value is  false , the shape can be edited in Word. |

### getLockType() {#getLockType--}
```
public final int getLockType()
```


Gets the watermark lock type.

**Returns:**
int - The watermark lock type of `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`.
### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


Sets the watermark lock type.

Value `[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` can not be used with an object of type `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The watermark lock type of `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`. |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Gets a password used to lock the watermark.

**Returns:**
java.lang.String - A password used to lock the watermark.
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Sets a password used to lock the watermark.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A password used to lock the watermark. |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Gets the page numbers to add the watermark.

**Returns:**
int[] - The page numbers to add the watermark.

--------------------

All numbers must be greater than or equal to 1. This property is only used when adding the watermark to a document. If this value is  null , the watermark is added to all pages.
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Sets the page numbers to add the watermark.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The page numbers to add the watermark.

--------------------

All numbers must be greater than or equal to 1. This property is only used when adding the watermark to a document. If this value is  null , the watermark is added to all pages. |

