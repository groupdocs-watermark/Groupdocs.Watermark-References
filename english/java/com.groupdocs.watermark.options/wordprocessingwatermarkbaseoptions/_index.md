---
title: WordProcessingWatermarkBaseOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Base class for watermark adding options to a Word document.
type: docs
weight: 73
url: /java/com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions)
```
public abstract class WordProcessingWatermarkBaseOptions extends WordProcessingWatermarkOptions
```

Base class for watermark adding options to a Word document.
## Methods

| Method | Description |
| --- | --- |
| [isLocked()](#isLocked--) | Gets a value indicating whether an editing of the shape in Word is forbidden. |
| [setLocked(boolean value)](#setLocked-boolean-) | Sets a value indicating whether an editing of the shape in Word is forbidden. |
| [getLockType()](#getLockType--) | Gets the watermark lock type. |
| [setLockType(int value)](#setLockType-int-) | Sets the watermark lock type. |
| [getPassword()](#getPassword--) | Gets a password used to lock the watermark. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Sets a password used to lock the watermark. |
| [getName()](#getName--) | Gets the name a shape. |
| [setName(String value)](#setName-java.lang.String-) | Sets the name a shape. |
| [getAlternativeText()](#getAlternativeText--) | Gets the descriptive (alternative) text that will be associated with a shape. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Sets the descriptive (alternative) text that will be associated with a shape. |
| [getEffects()](#getEffects--) |  |
| [setEffects(IWordProcessingWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-) |  |
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
int - The watermark `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` lock type.
### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


Sets the watermark lock type.

The value `[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` can not be used with an object of type `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The watermark `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` lock type. |

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

### getName() {#getName--}
```
public final String getName()
```


Gets the name a shape.

**Returns:**
java.lang.String - The shape name.
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Sets the name a shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The shape name. |

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Gets the descriptive (alternative) text that will be associated with a shape.

**Returns:**
java.lang.String - The descriptive (alternative) text that will be associated with a shape.
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Sets the descriptive (alternative) text that will be associated with a shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The descriptive (alternative) text that will be associated with a shape. |

### getEffects() {#getEffects--}
```
public final IWordProcessingWatermarkEffects getEffects()
```




**Returns:**
[IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects)
### setEffects(IWordProcessingWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-}
```
public final void setEffects(IWordProcessingWatermarkEffects value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |

