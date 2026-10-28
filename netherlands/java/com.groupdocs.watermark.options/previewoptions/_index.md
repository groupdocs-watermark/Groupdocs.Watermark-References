---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Biedt opties om vereisten en streamdelegates in te stellen voor het genereren van een voorbeeld."
type: docs
weight: 47
url: /nl/java/com.groupdocs.watermark.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Biedt opties om vereisten en streamdelegates in te stellen voor het genereren van een voorbeeld.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PreviewOptions(ICreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initialiseert een nieuw exemplaar van de `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` klasse waardoor de uitvoerstroom wordt gesloten. |
|
|  | [PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initialiseert een nieuw exemplaar van de `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` klasse waardoor de uitvoerstroom wordt teruggegeven aan de client voor verder gebruik. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getWidth()](#getWidth--) | Haalt de breedte van de paginavoorvertoning op. |
|
|  | [setWidth(int value)](#setWidth-int-) | Stelt de breedte van de paginavoorvertoning in. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte van de paginavoorvertoning op. |
|
|  | [setHeight(int value)](#setHeight-int-) | Stelt de hoogte van de paginavoorvertoning in. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Haalt een array met paginanummers op om voorvertoningen te genereren. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Stelt een array met paginanummers in om voorvertoningen te genereren. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Haalt het formaat van de voorvertoningsafbeelding op. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Stelt het formaat van de voorvertoningsafbeelding in. |
|
|  | [getCreatePageStream()](#getCreatePageStream--) | Haalt een instantie van de paginastroomcreatieklasse op. |
|
|  | [setCreatePageStream(ICreatePageStream value)](#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-) | Stelt een instantie van de paginastroomcreatieklasse in. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Haalt een instantie van de paginavoorvertoningsvoltooiingsklasse op. |
|
|  | [setReleasePageStream(IReleasePageStream value)](#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Stelt een instantie van de paginavoorvertoningsvoltooiingsklasse in. |
|
### PreviewOptions(ICreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream)
```


Initialiseert een nieuw exemplaar van de `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` klasse waardoor de uitvoerstroom wordt gesloten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Maakt een stream voor een specifieke paginavoorbeeld. |
|

### PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initialiseert een nieuw exemplaar van de `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` klasse waardoor de uitvoerstroom wordt teruggegeven aan de client voor verder gebruik.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Maakt een stream voor een specifieke paginavoorbeeld. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Meldt dat de generatie van het paginavoorbeeld voltooid is en haalt de uitvoerstroom op. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Haalt de breedte van de paginavoorvertoning op.


**Returns:**
int - De breedte van de paginavoorvertoning.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Stelt de breedte van de paginavoorvertoning in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De breedte van de paginavoorvertoning. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Haalt de hoogte van de paginavoorvertoning op.


**Returns:**
int - De hoogte van de paginavoorvertoning.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Stelt de hoogte van de paginavoorvertoning in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De hoogte van de paginavoorvertoning. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Haalt een array met paginanummers op om voorvertoningen te genereren.


**Returns:**
int[] - De array met paginanummers om voorvertoningen te genereren.

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Stelt een array met paginanummers in om voorvertoningen te genereren.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int[] | De array met paginanummers om voorvertoningen te genereren. |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Haalt het formaat van de voorvertoningsafbeelding op.


**Returns:**
int - Het formaat van de voorvertoningsafbeelding.

### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Stelt het formaat van de voorvertoningsafbeelding in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | Het formaat van de voorvertoningsafbeelding. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public final ICreatePageStream getCreatePageStream()
```


Haalt een instantie van de paginastroomcreatieklasse op.


**Returns:**
[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) - The instance of the page stream creation class.

### setCreatePageStream(ICreatePageStream value) {#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-}
```
public final void setCreatePageStream(ICreatePageStream value)
```


Stelt een instantie van de paginastroomcreatieklasse in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | De instantie van de paginastroomcreatieklasse. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public final IReleasePageStream getReleasePageStream()
```


Haalt een instantie van de paginavoorvertoningsvoltooiingsklasse op.


**Returns:**
[IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) - The instance of the page preview completion delegate.

### setReleasePageStream(IReleasePageStream value) {#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public final void setReleasePageStream(IReleasePageStream value)
```


Stelt een instantie van de paginavoorvertoningsvoltooiingsklasse in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | De instantie van de paginavoorbeeldvoltooiingsdelegate. |
|

