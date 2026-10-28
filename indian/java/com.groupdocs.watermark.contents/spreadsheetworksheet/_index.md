---
title: "SpreadsheetWorksheet"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "एक Excel दस्तावेज़ वर्कशीट का प्रतिनिधित्व करता है।"
type: docs
weight: 124
url: /hi/java/com.groupdocs.watermark.contents/spreadsheetworksheet/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class SpreadsheetWorksheet extends ContentPart
```

एक Excel दस्तावेज़ वर्कशीट का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getSpreadsheetDataSizeInPoints()](#getSpreadsheetDataSizeInPoints--) |  |
|  | [getPageSetup()](#getPageSetup--) | इस `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` के लिए प्रिंटिंग पेज सेटअप प्राप्त करता है। |
|
|  | [getContentAreaWidth()](#getContentAreaWidth--) | सामग्री क्षेत्र की चौड़ाई पॉइंट्स में प्राप्त करता है। |
|
|  | [getContentAreaWidthPx()](#getContentAreaWidthPx--) | पिक्सेल में कंटेंट एरिया की चौड़ाई प्राप्त करता है। |
|
|  | [getContentAreaHeight()](#getContentAreaHeight--) | पॉइंट में कंटेंट एरिया की ऊँचाई प्राप्त करता है। |
|
|  | [getContentAreaHeightPx()](#getContentAreaHeightPx--) | पिक्सेल में कंटेंट एरिया की ऊँचाई प्राप्त करता है। |
|
|  | [getShapes()](#getShapes--) | इस `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` की सभी शैलियों का संग्रह प्राप्त करता है। |
|
|  | [getAttachments()](#getAttachments--) | इस `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` के सभी अटैचमेंट्स का संग्रह प्राप्त करता है। |
|
|  | [getCharts()](#getCharts--) | इस `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` के सभी चार्ट्स का संग्रह प्राप्त करता है। |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | इस `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` की बैकग्राउंड इमेज प्राप्त करता है। |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | इस `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` की बैकग्राउंड इमेज सेट करता है। |
|
|  | [getHeadersFooters()](#getHeadersFooters--) | वर्कशीट हेडर और फुटर का संग्रह प्राप्त करता है। |
|
|  | [getAsposeCellsWorksheet()](#getAsposeCellsWorksheet--) | <br /> |

|
|  | [getColumnWidth(int column)](#getColumnWidth-int-) | निर्दिष्ट कॉलम की पॉइंट में चौड़ाई प्राप्त करता है। |
|
|  | [getColumnWidthPx(int column)](#getColumnWidthPx-int-) | निर्दिष्ट कॉलम की पिक्सेल में चौड़ाई प्राप्त करता है। |
|
|  | [getRowHeight(int row)](#getRowHeight-int-) | निर्दिष्ट पंक्ति की पॉइंट में ऊँचाई प्राप्त करता है। |
|
|  | [getRowHeightPx(int row)](#getRowHeightPx-int-) | निर्दिष्ट पंक्ति की पिक्सेल में ऊँचाई प्राप्त करता है। |
|
|  | [addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | <br /> |

|
|  | [addWatermarkAsBackground(Watermark watermark, int backgroundWidth, int backgroundHeight)](#addWatermarkAsBackground-com.groupdocs.watermark.Watermark-int-int-) | <br /> |

|
|  | [addWatermarkIntoHeaderFooter(Watermark watermark)](#addWatermarkIntoHeaderFooter-com.groupdocs.watermark.Watermark-) | <br /> |

|
|  | [addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings)](#addModernWordArtWatermark-com.groupdocs.watermark.watermarks.TextWatermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-) | <br /> |

|
|  | [addWordArtWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)](#addWordArtWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | <br /> |

|
|  | [getRowY(int rowIndex)](#getRowY-int-) | <br /> |

|
|  | [getColumnX(int columnIndex)](#getColumnX-int-) | <br /> |

|
|  | [getRowRangeHeight(int startRow, int endRow)](#getRowRangeHeight-int-int-) | <br /> |

|
|  | [getColumnRangeWidth(int startColumn, int endColumn)](#getColumnRangeWidth-int-int-) | <br /> |

|
|  | [resetBackgroundImageReference()](#resetBackgroundImageReference--) | <br /> |

|
### getSpreadsheetDataSizeInPoints() {#getSpreadsheetDataSizeInPoints--}
```
public Size getSpreadsheetDataSizeInPoints()
```




**Returns:**
[Size](../../com.groupdocs.watermark.internal/size)
### getPageSetup() {#getPageSetup--}
```
public final SpreadsheetPageSetup getPageSetup()
```


इस `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` के लिए प्रिंटिंग पेज सेटअप प्राप्त करता है।


**Returns:**
[SpreadsheetPageSetup](../../com.groupdocs.watermark.contents/spreadsheetpagesetup) - The printing page setup for this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getContentAreaWidth() {#getContentAreaWidth--}
```
public final double getContentAreaWidth()
```


सामग्री क्षेत्र की चौड़ाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - कंटेंट एरिया की पॉइंट में चौड़ाई।

### getContentAreaWidthPx() {#getContentAreaWidthPx--}
```
public final int getContentAreaWidthPx()
```


पिक्सेल में कंटेंट एरिया की चौड़ाई प्राप्त करता है।


**Returns:**
int - कंटेंट एरिया की पिक्सेल में चौड़ाई।

### getContentAreaHeight() {#getContentAreaHeight--}
```
public final double getContentAreaHeight()
```


पॉइंट में कंटेंट एरिया की ऊँचाई प्राप्त करता है।


**Returns:**
double - कंटेंट एरिया की पॉइंट में ऊँचाई।

### getContentAreaHeightPx() {#getContentAreaHeightPx--}
```
public final int getContentAreaHeightPx()
```


पिक्सेल में कंटेंट एरिया की ऊँचाई प्राप्त करता है।


**Returns:**
int - कंटेंट एरिया की पिक्सेल में ऊँचाई।

### getShapes() {#getShapes--}
```
public final SpreadsheetShapeCollection getShapes()
```


इस `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` की सभी शैलियों का संग्रह प्राप्त करता है।


**Returns:**
[SpreadsheetShapeCollection](../../com.groupdocs.watermark.contents/spreadsheetshapecollection) - The collection of all shapes of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getAttachments() {#getAttachments--}
```
public final SpreadsheetAttachmentCollection getAttachments()
```


इस `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` के सभी अटैचमेंट्स का संग्रह प्राप्त करता है।


**Returns:**
[SpreadsheetAttachmentCollection](../../com.groupdocs.watermark.contents/spreadsheetattachmentcollection) - The collection of all attachments of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getCharts() {#getCharts--}
```
public final SpreadsheetChartCollection getCharts()
```


इस `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` के सभी चार्ट्स का संग्रह प्राप्त करता है।


**Returns:**
[SpreadsheetChartCollection](../../com.groupdocs.watermark.contents/spreadsheetchartcollection) - The collection of all charts of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getBackgroundImage() {#getBackgroundImage--}
```
public final SpreadsheetWatermarkableImage getBackgroundImage()
```


इस `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` की बैकग्राउंड इमेज प्राप्त करता है।


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` or `null` if the worksheet has no background image.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


इस `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` की बैकग्राउंड इमेज सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | इस `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` की बैकग्राउंड इमेज या `null` यदि बैकग्राउंड इमेज हटानी हो। |
|

### getHeadersFooters() {#getHeadersFooters--}
```
public final SpreadsheetHeaderFooterCollection getHeadersFooters()
```


वर्कशीट हेडर और फुटर का संग्रह प्राप्त करता है।


**Returns:**
[SpreadsheetHeaderFooterCollection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootercollection) - The collection of headers and footers.

### getAsposeCellsWorksheet() {#getAsposeCellsWorksheet--}
```
public final Worksheet getAsposeCellsWorksheet()
```


<br />



**Returns:**
com.aspose.cells.Worksheet
### getColumnWidth(int column) {#getColumnWidth-int-}
```
public final double getColumnWidth(int column)
```


निर्दिष्ट कॉलम की पॉइंट में चौड़ाई प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | कॉलम | int | कॉलम इंडेक्स। |
|

**Returns:**
double - कॉलम की पॉइंट में चौड़ाई।

### getColumnWidthPx(int column) {#getColumnWidthPx-int-}
```
public final int getColumnWidthPx(int column)
```


निर्दिष्ट कॉलम की पिक्सेल में चौड़ाई प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | कॉलम | int | कॉलम इंडेक्स। |
|

**Returns:**
int - कॉलम की पिक्सेल में चौड़ाई।

### getRowHeight(int row) {#getRowHeight-int-}
```
public final double getRowHeight(int row)
```


निर्दिष्ट पंक्ति की पॉइंट में ऊँचाई प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | पंक्ति | int | पंक्ति इंडेक्स। |
|

**Returns:**
double - पंक्ति की ऊँचाई बिंदुओं में।

### getRowHeightPx(int row) {#getRowHeightPx-int-}
```
public final int getRowHeightPx(int row)
```


निर्दिष्ट पंक्ति की पिक्सेल में ऊँचाई प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | पंक्ति | int | पंक्ति इंडेक्स। |
|

**Returns:**
int - पंक्ति की ऊँचाई पिक्सेल में।

### addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings) |  |
| effects | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) |  |

### addWatermarkAsBackground(Watermark watermark, int backgroundWidth, int backgroundHeight) {#addWatermarkAsBackground-com.groupdocs.watermark.Watermark-int-int-}
```
public final void addWatermarkAsBackground(Watermark watermark, int backgroundWidth, int backgroundHeight)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| backgroundWidth | int |  |
| backgroundHeight | int |  |

### addWatermarkIntoHeaderFooter(Watermark watermark) {#addWatermarkIntoHeaderFooter-com.groupdocs.watermark.Watermark-}
```
public final void addWatermarkIntoHeaderFooter(Watermark watermark)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings) {#addModernWordArtWatermark-com.groupdocs.watermark.watermarks.TextWatermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-}
```
public final void addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark) |  |
| shapeSettings | [SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings) |  |

### addWordArtWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects) {#addWordArtWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void addWordArtWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings) |  |
| effects | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) |  |

### getRowY(int rowIndex) {#getRowY-int-}
```
public final double getRowY(int rowIndex)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rowIndex | int |  |

**Returns:**
double
### getColumnX(int columnIndex) {#getColumnX-int-}
```
public final double getColumnX(int columnIndex)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | int |  |

**Returns:**
double
### getRowRangeHeight(int startRow, int endRow) {#getRowRangeHeight-int-int-}
```
public final double getRowRangeHeight(int startRow, int endRow)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startRow | int |  |
| endRow | int |  |

**Returns:**
double
### getColumnRangeWidth(int startColumn, int endColumn) {#getColumnRangeWidth-int-int-}
```
public final double getColumnRangeWidth(int startColumn, int endColumn)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startColumn | int |  |
| endColumn | int |  |

**Returns:**
double
### resetBackgroundImageReference() {#resetBackgroundImageReference--}
```
public final void resetBackgroundImageReference()
```


<br />



