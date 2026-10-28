---
title: "PresentationShapeSettings"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "PowerPoint दस्तावेज़ के लिए आकार वॉटरमार्क पर लागू की जा सकने वाली सेटिंग्स का प्रतिनिधित्व करता है।"
type: docs
weight: 95
url: /hi/java/com.groupdocs.watermark.contents/presentationshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class PresentationShapeSettings extends OfficeShapeSettings
```

PowerPoint दस्तावेज़ के लिए आकार वॉटरमार्क पर लागू की जा सकने वाली सेटिंग्स का प्रतिनिधित्व करता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [PresentationShapeSettings()](#PresentationShapeSettings--) | एक नया उदाहरण `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)` क्लास का आरंभ करता है। |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [UnreadableCharacter](#UnreadableCharacter) | <br /> |

|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [isLocked()](#isLocked--) | एक मान प्राप्त करता है जो दर्शाता है कि PowerPoint में आकार का संपादन प्रतिबंधित है या नहीं। |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | एक मान सेट करता है जो दर्शाता है कि PowerPoint में आकार का संपादन प्रतिबंधित है या नहीं। |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | एक मान प्राप्त करता है जो दर्शाता है कि टेक्स्ट वॉटरमार्क अक्षर अपठनीय अक्षरों के साथ मिश्रित हैं या नहीं। |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | एक मान सेट करता है जो दर्शाता है कि टेक्स्ट वॉटरमार्क अक्षर अपठनीय अक्षरों के साथ मिश्रित हैं या नहीं। |
|
### PresentationShapeSettings() {#PresentationShapeSettings--}
```
public PresentationShapeSettings()
```


एक नया उदाहरण `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)` क्लास का आरंभ करता है।


### UnreadableCharacter {#UnreadableCharacter}
```
public static final char UnreadableCharacter
```


<br />



### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


एक मान प्राप्त करता है जो दर्शाता है कि PowerPoint में आकार का संपादन प्रतिबंधित है या नहीं।


**Returns:**
बूलियन - `true` यदि आकार संपादन प्रतिबंधित है, `false` यदि आकार को PowerPoint में संपादित किया जा सकता है।

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि PowerPoint में आकार का संपादन प्रतिबंधित है या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | `true` यदि आकार संपादन प्रतिबंधित होना चाहिए, `false` यदि आकार को PowerPoint में संपादित किया जा सकता है। |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


एक मान प्राप्त करता है जो दर्शाता है कि टेक्स्ट वॉटरमार्क अक्षर अपठनीय अक्षरों के साथ मिश्रित हैं या नहीं।

यह सुरक्षा केवल तब लागू होती है जब `#isLocked().isLocked()` `true` लौटाता है।


**Returns:**
boolean - एक मान जो दर्शाता है कि टेक्स्ट वॉटरमार्क अक्षर अपठनीय अक्षरों के साथ मिश्रित हैं या नहीं।

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि टेक्स्ट वॉटरमार्क अक्षर अपठनीय अक्षरों के साथ मिश्रित हैं या नहीं।

यह सुरक्षा केवल तब लागू होती है जब `#isLocked().isLocked()` `true` लौटाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | एक मान जो दर्शाता है कि टेक्स्ट वॉटरमार्क अक्षर अपठनीय अक्षरों के साथ मिश्रित हैं। |
|

