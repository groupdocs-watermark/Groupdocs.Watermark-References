---
title: IPresentationHyperlinkContainer
second_title: GroupDocs.Watermark for Java API Reference
description: Represents PowerPoint document object that contains a hyperlink.
type: docs
weight: 152
url: /java/com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer/
---```
public interface IPresentationHyperlinkContainer
```

Represents PowerPoint document object that contains a hyperlink.
## Methods

| Method | Description |
| --- | --- |
| [getHyperlink(int actionType)](#getHyperlink-int-) | Gets the hyperlink associated with this `[IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)`. |
| [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Sets the hyperlink associated with this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
### getHyperlink(int actionType) {#getHyperlink-int-}
```
public abstract String getHyperlink(int actionType)
```


Gets the hyperlink associated with this `[IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| actionType | int | The action that activates the hyperlink. |

**Returns:**
java.lang.String - The url of the hyperlink that is activated on specified action.
### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public abstract void setHyperlink(int actionType, String url)
```


Sets the hyperlink associated with this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| actionType | int | The action that activates the hyperlink. |
| url | java.lang.String | The hyperlink url. |

