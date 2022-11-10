---
title: IDocumentInfo
second_title: GroupDocs.Watermark for Java API Reference
description: Defines the methods that are required for getting the basic document information.
type: docs
weight: 20
url: /java/com.groupdocs.watermark.common/idocumentinfo/
---```
public interface IDocumentInfo
```

Defines the methods that are required for getting the basic document information.

**Learn more**

 *  [Get document info][]

The following example demonstrates how to retrieve the general document information using `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)`.

> ```
> ```
> 
>    Watermarker watermarker = new Watermarker("D:\\input.pdf");
>    IDocumentInfo docInfo = watermarker.getDocumentInfo();
>    System.out.println("File type: " + docInfo.getFileType());
>    System.out.println("Number of pages: " + docInfo.getPageCount());
>    System.out.println("Document size: " + docInfo.getSize() + " bytes");
>    watermarker.close();
>  
> ```
> ```


[Get document info]: https://docs.groupdocs.com/display/watermarkjava/Get+document+info
## Methods

| Method | Description |
| --- | --- |
| [getFileType()](#getFileType--) | Gets the file format description. |
| [getPageCount()](#getPageCount--) | Gets the total page count. |
| [getPages()](#getPages--) | Gets the collection of document pages descriptions. |
| [getSize()](#getSize--) | Gets the document size in bytes. |
| [isEncrypted()](#isEncrypted--) | Gets a value indicating whether the document is encrypted and requires a password to open. |
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


Gets the file format description.

**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype) - The file format description.
### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


Gets the total page count.

**Returns:**
int - The total page count.
### getPages() {#getPages--}
```
public abstract System.Collections.Generic.IGenericList<PageInfo> getPages()
```


Gets the collection of document pages descriptions.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.groupdocs.watermark.common.PageInfo> - The collection of document pages descriptions.
### getSize() {#getSize--}
```
public abstract long getSize()
```


Gets the document size in bytes.

**Returns:**
long - The document size in bytes.
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


Gets a value indicating whether the document is encrypted and requires a password to open.

**Returns:**
boolean - True if the document is encrypted and requires a password to open; otherwise, false.
