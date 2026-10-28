---
title: "SpreadsheetShapeSettings"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "एक्सेल दस्तावेज़ के लिए आकार वॉटरमार्क पर लागू किए जा सकने वाले सेटिंग्स का प्रतिनिधित्व करता है।"
type: docs
weight: 54
url: /hi/java/com.groupdocs.watermark.options/spreadsheetshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class SpreadsheetShapeSettings extends OfficeShapeSettings
```

एक्सेल दस्तावेज़ के लिए आकार वॉटरमार्क पर लागू किए जा सकने वाले सेटिंग्स का प्रतिनिधित्व करता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [SpreadsheetShapeSettings()](#SpreadsheetShapeSettings--) | `[SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings)` क्लास का नया उदाहरण प्रारंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [isLocked()](#isLocked--) | Excel में आकार (shape) के संपादन को प्रतिबंधित करने का संकेत देने वाला मान प्राप्त करता है। |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Excel में आकार के संपादन को प्रतिबंधित करने का संकेत देने वाला मान सेट करता है। |
|
### SpreadsheetShapeSettings() {#SpreadsheetShapeSettings--}
```
public SpreadsheetShapeSettings()
```


`[SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings)` क्लास का नया उदाहरण प्रारंभ करता है।


### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Excel में आकार (shape) के संपादन को प्रतिबंधित करने का संकेत देने वाला मान प्राप्त करता है।


**Returns:**
boolean - यदि मान true है, तो आकार का संपादन प्रतिबंधित होगा। डिफ़ॉल्ट रूप से, मान false है, आकार को Excel में संपादित किया जा सकता है।

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Excel में आकार के संपादन को प्रतिबंधित करने का संकेत देने वाला मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | यदि मान true है, तो आकार का संपादन प्रतिबंधित होगा। डिफ़ॉल्ट रूप से, मान false है, आकार को Excel में संपादित किया जा सकता है। |
|

