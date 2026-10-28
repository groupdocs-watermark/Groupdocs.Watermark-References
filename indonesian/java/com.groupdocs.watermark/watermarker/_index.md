---
title: "Watermarker"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili kelas untuk manajemen watermark dalam dokumen."
type: docs
weight: 14
url: /id/java/com.groupdocs.watermark/watermarker/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Watermarker implements Closeable
```

Mewakili kelas untuk manajemen watermark dalam dokumen.

Contoh berikut menunjukkan cara memuat dan menyimpan konten dari format apa pun yang didukung.
>
> ````
> ```
>
>    // Load a content from a file.
>    Watermarker watermarker = new Watermarker("D:\\input.pdf");
>
>    // Use methods of Watermarker class to add, search or remove watermarks.
>
>    // Save changes.
>    watermarker.save("D:\\output.pdf");
>
>    // Free resources.
>    watermarker.close();
>  
> ```
> ````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Watermarker(String filePath)](#Watermarker-java.lang.String-) | Menginisialisasi instance baru dari kelas `[Watermarker](../../com.groupdocs.watermark/watermarker)` dengan jalur dokumen yang ditentukan. |
|
|  | [Watermarker(String filePath, LoadOptions options)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-) | Menginisialisasi instance baru dari kelas `[Watermarker](../../com.groupdocs.watermark/watermarker)` dengan jalur dokumen yang ditentukan dan opsi pemuatan. |
|
|  | [Watermarker(String filePath, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-) | Menginisialisasi instance baru dari kelas `[Watermarker](../../com.groupdocs.watermark/watermarker)` dengan jalur dokumen yang ditentukan dan pengaturan. |
|
|  | [Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Menginisialisasi instance baru dari kelas `[Watermarker](../../com.groupdocs.watermark/watermarker)` dengan jalur dokumen yang ditentukan, opsi pemuatan, dan pengaturan. |
|
|  | [Watermarker(InputStream document)](#Watermarker-java.io.InputStream-) | Menginisialisasi instance baru dari kelas `[Watermarker](../../com.groupdocs.watermark/watermarker)` dengan aliran yang ditentukan. |
|
|  | [Watermarker(InputStream document, LoadOptions options)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-) | Menginisialisasi instance baru dari kelas `[Watermarker](../../com.groupdocs.watermark/watermarker)` dengan aliran yang ditentukan dan opsi pemuatan. |
|
|  | [Watermarker(InputStream document, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-) | Menginisialisasi instance baru dari kelas `[Watermarker](../../com.groupdocs.watermark/watermarker)` dengan aliran yang ditentukan dan pengaturan. |
|
|  | [Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Menginisialisasi instance baru dari kelas dengan aliran, opsi pemuatan, dan pengaturan yang ditentukan. |
|
| [Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | Mendapatkan objek konten yang akan dimasukkan dalam pencarian watermark. |
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Menetapkan objek konten yang akan dimasukkan dalam pencarian watermark. |
|
| [dispose()](#dispose--) |  |
|  | [close()](#close--) | Membuang instance saat ini. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Mendapatkan informasi tentang format dokumen yang dimuat. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Menambahkan watermark ke dokumen yang dimuat. |
|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | Menambahkan watermark ke dokumen yang dimuat menggunakan opsi watermark. |
|
|  | [remove(PossibleWatermark possibleWatermark)](#remove-com.groupdocs.watermark.search.PossibleWatermark-) | Menghapus watermark dari dokumen. |
|
|  | [remove(PossibleWatermarkCollection possibleWatermarks)](#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-) | Menghapus semua watermark dalam koleksi dari dokumen. |
|
|  | [save(String filePath)](#save-java.lang.String-) | Menyimpan dokumen ke lokasi file yang ditentukan. |
|
|  | [save(OutputStream document)](#save-java.io.OutputStream-) | Menyimpan dokumen ke aliran yang ditentukan. |
|
|  | [save(String filePath, SaveOptions options)](#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | Menyimpan dokumen ke lokasi file yang ditentukan menggunakan opsi penyimpanan. |
|
|  | [save(OutputStream document, SaveOptions options)](#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | Menyimpan dokumen ke aliran yang ditentukan menggunakan opsi penyimpanan. |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | Membuat gambar pratinjau untuk dokumen. |
|
|  | [search()](#search--) | Mencari semua watermark yang mungkin dalam dokumen. |
|
|  | [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | Mencari watermark yang mungkin sesuai dengan kriteria pencarian yang ditentukan. |
|
|  | [getImages(ImageSearchCriteria searchCriteria)](#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | Menemukan gambar sesuai dengan kriteria pencarian yang ditentukan. |
|
|  | [getImages()](#getImages--) | Menemukan semua gambar dalam dokumen. |
|
|  | [<T>getContent(Class<T> contentType)](#-T-getContent-java.lang.Class-T--) | Mengembalikan objek `[Content](../../com.groupdocs.watermark.contents/content)` untuk dokumen yang dimuat. |
|
### Watermarker(String filePath) {#Watermarker-java.lang.String-}
```
public Watermarker(String filePath)
```


Menginisialisasi instance baru dari kelas `[Watermarker](../../com.groupdocs.watermark/watermarker)` dengan jalur dokumen yang ditentukan.

Pelajari lebih lanjut tentang memuat dokumen:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Contoh berikut menunjukkan cara memuat dan menyimpan konten dari format apa pun yang didukung.
>
> ````
> ```
>
>    // Load a content from a file.
>    Watermarker watermarker = new Watermarker("D:\\input.pdf");
>
>    // Use methods of Watermarker class to add, search or remove watermarks.
>
>    // Save changes.
>    watermarker.save("D:\\output.pdf");
>
>    // Free resources.
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur file untuk memuat dokumen. |
|

### Watermarker(String filePath, LoadOptions options) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(String filePath, LoadOptions options)
```


Menginisialisasi instance baru dari kelas `[Watermarker](../../com.groupdocs.watermark/watermarker)` dengan jalur dokumen yang ditentukan dan opsi pemuatan.

Pelajari lebih lanjut tentang memuat dokumen:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Contoh berikut menunjukkan cara memuat dokumen PDF terenkripsi menggunakan kata sandi.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    loadOptions.setPassword("123");
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.pdf", loadOptions);
>    // ...
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur file untuk memuat dokumen. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Opsi tambahan yang digunakan saat memuat dokumen. |
|

### Watermarker(String filePath, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, WatermarkerSettings settings)
```


Menginisialisasi instance baru dari kelas `[Watermarker](../../com.groupdocs.watermark/watermarker)` dengan jalur dokumen yang ditentukan dan pengaturan.

Pelajari lebih lanjut tentang memuat dokumen:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Contoh berikut menunjukkan cara mengatur objek yang dapat dicari secara global (untuk semua dokumen yang
akan dimuat setelah itu).
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setWordProcessingSearchableObjects(WordProcessingSearchableObjects.Hyperlinks
>                                                                     | WordProcessingSearchableObjects.Text);
>    settings.getSearchableObjects().setSpreadsheetSearchableObjects(SpreadsheetSearchableObjects.HeadersFooters);
>    settings.getSearchableObjects().setPresentationSearchableObjects(PresentationSearchableObjects.SlidesBackgrounds
>                                                                   | PresentationSearchableObjects.Shapes);
>    settings.getSearchableObjects().setDiagramSearchableObjects(DiagramSearchableObjects.None);
>    settings.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.All);
>
>    for (final File fileEntry : new File("D:\\files").listFiles())
>    {
>       if (fileEntry.isFile()) {
>           Watermarker watermarker = new Watermarker(fileEntry.getPath(), settings);
>           PossibleWatermarkCollection watermarks = watermarker.search();
>           // The code for working with found watermarks goes here.
>           watermarker.close();
>       }
>    }
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur file untuk memuat dokumen. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Pengaturan tambahan yang digunakan saat bekerja dengan dokumen yang dimuat. |
|

### Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)
```


Menginisialisasi instance baru dari kelas `[Watermarker](../../com.groupdocs.watermark/watermarker)` dengan jalur dokumen yang ditentukan, opsi pemuatan, dan pengaturan.

Pelajari lebih lanjut tentang memuat dokumen:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Contoh berikut menunjukkan cara menemukan fragmen teks tertentu dalam isi/subjek pesan email.
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setEmailSearchableObjects(EmailSearchableObjects.Subject
>                                                            | EmailSearchableObjects.HtmlBody
>                                                            | EmailSearchableObjects.PlainTextBody);
>    EmailLoadOptions loadOptions = new EmailLoadOptions(); 
>    Watermarker watermarker = new Watermarker("D:\\test.msg", loadOptions, settings);
>    SearchCriteria criteria = new TextSearchCriteria("test", false);
>    // Note, search is performed only if you pass TextSearchCriteria instance to search() method
>    PossibleWatermarkCollection watermarks = watermarker.search(criteria);
>    // Remove found text fragments
>    watermarks.clear();
>    // Save changes
>    watermarker.save("D:\\modified_test.msg");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur file untuk memuat dokumen. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Opsi tambahan yang digunakan saat memuat dokumen. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Pengaturan tambahan yang digunakan saat bekerja dengan dokumen yang dimuat. |
|

### Watermarker(InputStream document) {#Watermarker-java.io.InputStream-}
```
public Watermarker(InputStream document)
```


Menginisialisasi instance baru dari kelas `[Watermarker](../../com.groupdocs.watermark/watermarker)` dengan aliran yang ditentukan.

Pelajari lebih lanjut tentang memuat dokumen:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Contoh berikut menunjukkan cara memuat dan menyimpan dokumen dalam format apa pun yang didukung.
>
> ````
> ```
>
>    // Load a content from a stream.
>    FileInputStream inputStream = new FileInputStream("D:\\input.pdf");
>    FileOutputStream outputStream = new FileOutputStream("D:\\output.pdf");
>    Watermarker watermarker = new Watermarker(inputStream);
>    // Use methods of Watermarker class to add, search or remove watermarks.
>
>    // Save changes.
>    watermarker.save(outputStream);
>    watermarker.close();
>    outputStream.close();
>    inputStream.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.InputStream | Aliran untuk memuat dokumen dari. |
|

### Watermarker(InputStream document, LoadOptions options) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(InputStream document, LoadOptions options)
```


Menginisialisasi instance baru dari kelas `[Watermarker](../../com.groupdocs.watermark/watermarker)` dengan aliran yang ditentukan dan opsi pemuatan.

Pelajari lebih lanjut tentang memuat dokumen:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Contoh berikut menunjukkan cara memuat dokumen PDF terenkripsi menggunakan kata sandi
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    loadOptions.setPassword("123");
>    FileInputStream inputStream = new FileInputStream("D:\\input.pdf");
>    Watermarker watermarker = new Watermarker(inputStream, loadOptions);
>    // ...
>
>    watermarker.close();
>    inputStream.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.InputStream | Aliran untuk memuat dokumen dari. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Opsi tambahan yang digunakan saat memuat dokumen. |
|

### Watermarker(InputStream document, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, WatermarkerSettings settings)
```


Menginisialisasi instance baru dari kelas `[Watermarker](../../com.groupdocs.watermark/watermarker)` dengan aliran yang ditentukan dan pengaturan.

Pelajari lebih lanjut tentang memuat dokumen:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Contoh berikut menunjukkan cara mengatur objek yang dapat dicari secara global (untuk semua dokumen yang
akan dimuat setelah itu).
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setWordProcessingSearchableObjects(WordProcessingSearchableObjects.Hyperlinks
>                                                                     | WordProcessingSearchableObjects.Text);
>    settings.getSearchableObjects().setSpreadsheetSearchableObjects(SpreadsheetSearchableObjects.HeadersFooters);
>    settings.getSearchableObjects().setPresentationSearchableObjects(PresentationSearchableObjects.SlidesBackgrounds
>                                                                   | PresentationSearchableObjects.Shapes);
>    settings.getSearchableObjects().setDiagramSearchableObjects(DiagramSearchableObjects.None);
>    settings.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.All);
>
>    for (final File fileEntry : new File("D:\\files").listFiles())
>    {
>       if (fileEntry.isFile()) {
>           FileInputStream inputStream = new FileInputStream(fileEntry.getPath());
>           Watermarker watermarker = new Watermarker(inputStream, settings);
>           PossibleWatermarkCollection watermarks = watermarker.Search();
>           // The code for working with found watermarks goes here.
>           watermarker.close();
>           inputStream.close();
>       }
>    }
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.InputStream | Aliran untuk memuat dokumen dari. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Pengaturan tambahan yang digunakan saat bekerja dengan dokumen yang dimuat. |
|

### Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)
```


Menginisialisasi instance baru dari kelas dengan aliran, opsi pemuatan, dan pengaturan yang ditentukan.

Pelajari lebih lanjut tentang memuat dokumen:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Contoh berikut menunjukkan cara mengatur objek yang dapat dicari secara global (untuk semua dokumen yang
akan dimuat setelah itu).
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setEmailSearchableObjects(EmailSearchableObjects.Subject
>                                                            | EmailSearchableObjects.HtmlBody
>                                                            | EmailSearchableObjects.PlainTextBody);
>    FileInputStream inputStream = new FileInputStream("D:\\test.msg");
>    FileOutputStream outputStream = new FileOutputStream("D:\\modified_test.msg");
>    EmailLoadOptions loadOptions = new EmailLoadOptions(); 
>    Watermarker watermarker = new Watermarker(inputStream, loadOptions, settings);
>    SearchCriteria criteria = new TextSearchCriteria("test", false);
>    // Note, search is performed only if you pass TextSearchCriteria instance to search() method
>    PossibleWatermarkCollection watermarks = watermarker.search(criteria);
>    // Remove found text fragments
>    watermarks.clear();
>    // Save changes
>    watermarker.save(outputStream);
>    watermarker.close();
>    outputStream.close();
>    inputStream.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.InputStream | Aliran untuk memuat dokumen dari. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Opsi tambahan yang digunakan saat memuat dokumen. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Pengaturan tambahan yang digunakan saat bekerja dengan dokumen yang dimuat. |
|

### Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | com.aspose.ms.System.IO.Stream |  |
| options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) |  |
| settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Mendapatkan objek konten yang akan dimasukkan dalam pencarian watermark.

Metode ini juga menentukan objek konten yang digunakan dalam pencarian gambar.
Untuk informasi lebih lanjut lihat `#search(SearchCriteria).search(SearchCriteria)`
dan metode `#getImages().getImages()`.

Pelajari lebih lanjut tentang pencarian watermark:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Contoh berikut menunjukkan cara menghapus semua XObjects dan Artifacts dari dokumen pdf.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.pdf");
>    watermarker.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.XObjects
>                                                             | PdfSearchableObjects.Artifacts);
>    PossibleWatermarkCollection watermarks = watermarker.search();
>    // Remove all found objects.
>    watermarks.clear();
>    // Save changes.
>    watermarker.save("D:\\modified_test.pdf");
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The objects that are to be included in a watermark search.

### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


Menetapkan objek konten yang akan dimasukkan dalam pencarian watermark.

Metode ini juga menentukan objek konten yang digunakan dalam pencarian gambar.
Untuk informasi lebih lanjut lihat `#search(SearchCriteria).search(SearchCriteria)`
dan metode `#getImages().getImages()`.
Pelajari lebih lanjut tentang pencarian watermark:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Contoh berikut menunjukkan cara menghapus semua XObjects dan Artifacts dari dokumen pdf.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.pdf");
>    watermarker.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.XObjects
>                                                             | PdfSearchableObjects.Artifacts);
>    PossibleWatermarkCollection watermarks = watermarker.search();
>    // Remove all found objects.
>    watermarks.clear();
>    // Save changes.
>    watermarker.save("D:\\modified_test.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | Objek-objek yang akan dimasukkan dalam pencarian watermark. |
|

### dispose() {#dispose--}
```
public final void dispose()
```




### close() {#close--}
```
public final void close()
```


Membuang instance saat ini.


### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Mendapatkan informasi tentang format dokumen yang dimuat.

Pelajari lebih lanjut tentang mendapatkan informasi dokumen
[Get document info](../https://docs.groupdocs.com/display/watermarkjava/Get+document+info).

Contoh berikut menunjukkan cara mendapatkan informasi tentang dokumen dari jenis apa pun yang didukung.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.ppt");
>    IDocumentInfo info = watermarker.getDocumentInfo();
>    System.out.println("File type: " + info.getFileType());
>    System.out.println("Number of pages: " + info.getPageCount());
>    System.out.println("Document size: " + info.getSize() + " bytes");
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.

### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


Menambahkan watermark ke dokumen yang dimuat.

Pelajari lebih lanjut tentang menambahkan watermark:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

Contoh berikut menunjukkan cara menambahkan watermark gambar dan teks ke dokumen dari jenis apa pun yang didukung.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.pdf");
>
>    TextWatermark textWatermark = new TextWatermark("DRAFT", new Font("Arial", 19));
>    textWatermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    textWatermark.setVerticalAlignment(VerticalAlignment.Top);
>    textWatermark.setConsiderParentMargins(true);
>    textWatermark.setForegroundColor(Color.getRed());
>    textWatermark.setBackground(true);
>    textWatermark.setOpacity(0.5);
>    watermarker.add(textWatermark);
>  
>    ImageWatermark imageWatermark = new ImageWatermark("D:\\draft.png"));
>    imageWatermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    imageWatermark.setVerticalAlignment(VerticalAlignment.Bottom);
>    imageWatermark.setConsiderParentMargins(true);
>    imageWatermark.setBackground(true);
>    imageWatermark.setOpacity(0.5);
>    watermarker.add(imageWatermark);
>    imageWatermark.close();
>
>    watermarker.save("D:\\output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Watermark yang akan ditambahkan ke dokumen. |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public final void add(Watermark watermark, WatermarkOptions options)
```


Menambahkan watermark ke dokumen yang dimuat menggunakan opsi watermark.

Pelajari lebih lanjut tentang menambahkan watermark:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

Contoh berikut menunjukkan cara menambahkan watermark gambar ke halaman tertentu dari dokumen pdf.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\input.pdf", loadOptions);
>
>    ImageWatermark imageWatermark = new ImageWatermark("D:\\draft.png"));
>    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
>    options.setPageIndex(0);
>    watermarker.add(imageWatermark, options);
>    imageWatermark.close();
>
>    watermarker.save("D:\\output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Watermark yang akan ditambahkan ke dokumen. |
|
|  | options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) | Opsi tambahan yang digunakan saat menambahkan watermark. |
|

### remove(PossibleWatermark possibleWatermark) {#remove-com.groupdocs.watermark.search.PossibleWatermark-}
```
public final void remove(PossibleWatermark possibleWatermark)
```


Menghapus watermark dari dokumen.

Pelajari lebih lanjut tentang menghapus watermark:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

Contoh berikut menunjukkan cara menemukan dan menghapus watermark pertama yang mungkin berisi tertentu
teks atau gambar dari dokumen jenis apa pun yang didukung.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.doc");
>    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria("D:\\logo.png");
>    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(Pattern.compile("^Company\\sName$"));
>    PossibleWatermarkCollection watermarks = watermarker.search(textSearchCriteria.or(imageSearchCriteria));
>    if (watermarks.getCount() > 0)
>    {
>        watermarker.remove(watermarks.get_Item(0));
>    }
>
>    watermarker.save("D:\\output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | possibleWatermark | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) | Watermark yang akan dihapus. |
|

### remove(PossibleWatermarkCollection possibleWatermarks) {#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void remove(PossibleWatermarkCollection possibleWatermarks)
```


Menghapus semua watermark dalam koleksi dari dokumen.

Pelajari lebih lanjut tentang menghapus watermark:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

Contoh berikut menunjukkan cara menemukan dan menghapus semua watermark yang mungkin berisi tertentu
teks atau gambar dari dokumen jenis apa pun yang didukung.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.doc");
>    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria("D:\\logo.png");
>    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(Pattern.compile("^Company\\sName$"));
>    PossibleWatermarkCollection watermarks = watermarker.search(textSearchCriteria.or(imageSearchCriteria));
>    watermarker.remove(watermarks);
>    watermarker.save("D:\\output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | possibleWatermarks | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) | Koleksi watermark yang akan dihapus. |
|

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Menyimpan dokumen ke lokasi file yang ditentukan.

Pelajari lebih lanjut tentang menyimpan dokumen
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Contoh berikut menunjukkan cara menambahkan watermark dan menyimpan dokumen ke file lain.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    watermarker.save("output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur file untuk menyimpan data dokumen. |
|

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


Menyimpan dokumen ke aliran yang ditentukan.

Pelajari lebih lanjut tentang menyimpan dokumen
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Contoh berikut menunjukkan cara menambahkan watermark dan menyimpan dokumen ke aliran memori.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    ByteArrayOutputStream outputStream = new ByteArrayOutputStream();
>    watermarker.save(outputStream);
>    // ...
>    outputStream.close();
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.OutputStream | Aliran untuk menyimpan data dokumen. |
|

### save(String filePath, SaveOptions options) {#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(String filePath, SaveOptions options)
```


Menyimpan dokumen ke lokasi file yang ditentukan menggunakan opsi penyimpanan.

Pelajari lebih lanjut tentang menyimpan dokumen
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Contoh berikut menunjukkan cara menambahkan watermark dan menyimpan dokumen ke file lain
dengan default `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    watermarker.save("output.pdf", new SaveOptions());
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur file untuk menyimpan data dokumen. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Opsi tambahan untuk digunakan saat menyimpan dokumen. |
|

### save(OutputStream document, SaveOptions options) {#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(OutputStream document, SaveOptions options)
```


Menyimpan dokumen ke aliran yang ditentukan menggunakan opsi penyimpanan.

Pelajari lebih lanjut tentang menyimpan dokumen
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Contoh berikut menunjukkan cara menambahkan watermark dan menyimpan dokumen ke aliran memori
dengan default `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    ByteArrayOutputStream outputStream = new ByteArrayOutputStream();
>    watermarker.save(outputStream, new SaveOptions());
>    // ...
>    outputStream.close();
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.OutputStream | Aliran untuk menyimpan data dokumen. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Opsi tambahan untuk digunakan saat menyimpan dokumen. |
|

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Membuat gambar pratinjau untuk dokumen.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) | Opsi tambahan untuk digunakan saat menghasilkan gambar pratinjau. |
|

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


Mencari semua watermark yang mungkin dalam dokumen.

Pencarian dilakukan pada objek yang ditentukan dengan `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Pelajari lebih lanjut tentang pencarian watermark
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Contoh berikut menunjukkan cara menghitung watermark yang mungkin dalam dokumen dengan tipe apa pun yang didukung.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    PossibleWatermarkCollection watermarks = watermarker.search();
>    System.out.println(watermarks.getCount());
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### search(SearchCriteria searchCriteria) {#search-com.groupdocs.watermark.search.SearchCriteria-}
```
public final PossibleWatermarkCollection search(SearchCriteria searchCriteria)
```


Mencari watermark yang mungkin sesuai dengan kriteria pencarian yang ditentukan.

Pencarian dilakukan pada objek yang ditentukan dengan `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Pelajari lebih lanjut tentang pencarian watermark
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Contoh berikut menunjukkan cara menemukan dan menghapus semua watermark yang mungkin yang berisi teks tertentu
atau gambar dari dokumen dengan tipe apa pun yang didukung.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria("logo.png");
>    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(Pattern.compile("^Company\\sName$"));
>    PossibleWatermarkCollection watermarks = watermarker.search(textSearchCriteria.or(imageSearchCriteria));
>    watermarks.clear();
>    watermarker.save("output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Kriteria pencarian yang akan digunakan. |
|

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### getImages(ImageSearchCriteria searchCriteria) {#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-}
```
public final WatermarkableImageCollection getImages(ImageSearchCriteria searchCriteria)
```


Menemukan gambar sesuai dengan kriteria pencarian yang ditentukan.

Pencarian dilakukan pada objek yang ditentukan dengan `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Pelajari lebih lanjut tentang pencarian watermark
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Contoh berikut menunjukkan cara menghapus semua gambar yang mirip dengan referensi
dari dokumen dengan tipe apa pun yang didukung.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    ImageThumbnailSearchCriteria criteria = new ImageThumbnailSearchCriteria("reference.png");
>    WatermarkableImageCollection images = watermarker.getImages(criteria);
>    images.clear();
>    watermarker.save("output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | Kriteria pencarian yang akan digunakan. |
|

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection)
### getImages() {#getImages--}
```
public final WatermarkableImageCollection getImages()
```


Menemukan semua gambar dalam dokumen.

Pencarian dilakukan pada objek yang ditentukan dengan `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Pelajari lebih lanjut tentang pencarian watermark
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Contoh berikut menunjukkan cara menambahkan watermark ke semua gambar dalam dokumen dengan tipe apa pun yang didukung.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    // Initialize text or image watermark.
>    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));
>
>    // Find all images in the document.
>    WatermarkableImageCollection images = watermarker.getImages();
>
>    // Add watermark.
>    for (WatermarkableImage watermarkableImage : images)
>    {
>        watermarkableImage.addWatermark(watermark);
>    }
>
>    // Save changes.
>    watermarker.save("output.doc");
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection) - The collection of found images.

### <T>getContent(Class<T> contentType) {#-T-getContent-java.lang.Class-T--}
```
public final T <T>getContent(Class<T> contentType)
```


Mengembalikan objek `[Content](../../com.groupdocs.watermark.contents/content)` untuk dokumen yang dimuat.

Contoh berikut menunjukkan cara meraster halaman dokumen pdf dengan watermark yang ditambahkan.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("input.pdf", loadOptions);
>    ImageWatermark watermark = new ImageWatermark("watermark.png")
>    watermarker.add(watermark);
>    PdfContent content = watermarker.getContent(PdfContent.class);
>    content.rasterize(300, 300, PdfImageConversionFormat.Png);
>    watermarker.save("output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | contentType | java.lang.Class<T> | Tipe yang diminta dari objek `[Content](../../com.groupdocs.watermark.contents/content)`. |
|

**Returns:**
T - Objek `[Content](../../com.groupdocs.watermark.contents/content)` untuk dokumen yang dimuat.

