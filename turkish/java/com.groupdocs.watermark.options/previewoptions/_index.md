---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Ön izleme oluşturma için gereksinimleri ve akış delegelerini ayarlama seçenekleri sağlar."
type: docs
weight: 47
url: /tr/java/com.groupdocs.watermark.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Ön izleme oluşturma için gereksinimleri ve akış delegelerini ayarlama seçenekleri sağlar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PreviewOptions(ICreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Yeni bir `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` sınıfının örneğini başlatır ve çıktı akışını kapatır. |
|
|  | [PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Yeni bir `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` sınıfının örneğini başlatır ve çıktı akışını daha sonraki kullanım için istemciye geri döndürür. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getWidth()](#getWidth--) | Sayfa önizleme genişliğini alır. |
|
|  | [setWidth(int value)](#setWidth-int-) | Sayfa önizleme genişliğini ayarlar. |
|
|  | [getHeight()](#getHeight--) | Sayfa önizleme yüksekliğini alır. |
|
|  | [setHeight(int value)](#setHeight-int-) | Sayfa önizleme yüksekliğini ayarlar. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Önizlemeler oluşturulacak sayfa numaralarının bir dizisini alır. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Önizlemeler oluşturulacak sayfa numaralarının bir dizisini ayarlar. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Önizleme görüntü formatını alır. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Önizleme görüntü formatını ayarlar. |
|
|  | [getCreatePageStream()](#getCreatePageStream--) | Sayfa akışı oluşturma sınıfının bir örneğini alır. |
|
|  | [setCreatePageStream(ICreatePageStream value)](#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-) | Sayfa akışı oluşturma sınıfının bir örneğini ayarlar. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Sayfa önizleme tamamlama sınıfının bir örneğini alır. |
|
|  | [setReleasePageStream(IReleasePageStream value)](#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Sayfa önizleme tamamlama sınıfının bir örneğini ayarlar. |
|
### PreviewOptions(ICreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream)
```


Yeni bir `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` sınıfının örneğini başlatır ve çıktı akışını kapatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Belirli bir sayfa önizlemesi için bir akış oluşturur. |
|

### PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Yeni bir `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` sınıfının örneğini başlatır ve çıktı akışını daha sonraki kullanım için istemciye geri döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Belirli bir sayfa önizlemesi için bir akış oluşturur. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Sayfa önizlemesi oluşturmanın tamamlandığını bildirir ve çıktı akışını alır. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Sayfa önizleme genişliğini alır.


**Returns:**
int - Sayfa önizleme genişliği.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Sayfa önizleme genişliğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Sayfa önizleme genişliği. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Sayfa önizleme yüksekliğini alır.


**Returns:**
int - Sayfa önizleme yüksekliği.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Sayfa önizleme yüksekliğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Sayfa önizleme yüksekliği. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Önizlemeler oluşturulacak sayfa numaralarının bir dizisini alır.


**Returns:**
int[] - Önizlemeler oluşturulacak sayfa numaralarının dizisi.

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Önizlemeler oluşturulacak sayfa numaralarının bir dizisini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int[] | Önizlemeler oluşturulacak sayfa numaralarının dizisi. |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Önizleme görüntü formatını alır.


**Returns:**
int - Önizleme görüntü formatı.

### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Önizleme görüntü formatını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Ön izleme görüntü biçimi. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public final ICreatePageStream getCreatePageStream()
```


Sayfa akışı oluşturma sınıfının bir örneğini alır.


**Returns:**
[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) - The instance of the page stream creation class.

### setCreatePageStream(ICreatePageStream value) {#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-}
```
public final void setCreatePageStream(ICreatePageStream value)
```


Sayfa akışı oluşturma sınıfının bir örneğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Sayfa akışı oluşturma sınıfının örneği. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public final IReleasePageStream getReleasePageStream()
```


Sayfa önizleme tamamlama sınıfının bir örneğini alır.


**Returns:**
[IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) - The instance of the page preview completion delegate.

### setReleasePageStream(IReleasePageStream value) {#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public final void setReleasePageStream(IReleasePageStream value)
```


Sayfa önizleme tamamlama sınıfının bir örneğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Sayfa ön izleme tamamlama temsilcisinin örneği. |
|

