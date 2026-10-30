---
title: "FileType"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет тип файла."
type: docs
weight: 40
url: /ru/net/groupdocs.watermark.common/filetype/
---
## FileType class

Представляет тип файла.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | Возвращает суффикс имени файла (включая точку "."), например, ".doc". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | Возвращает название типа файла, например, "Microsoft Word Document". |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | Возвращает семейство формата. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | Отображает расширение файла на тип файла. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | Определяет, является ли текущий [`FileType`](../filetype) тем же, что и указанный объект [`FileType`](../filetype). |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | Определяет, является ли текущий [`FileType`](../filetype) тем же объектом, что и указанный объект. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | Возвращает хеш-код для текущего объекта [`FileType`](../filetype). |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | Возвращает строку, представляющую текущий объект. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | Получает поддерживаемые типы файлов. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | Определяет, являются ли два объекта [`FileType`](../filetype) одинаковыми. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | Определяет, не являются ли два объекта [`FileType`](../filetype) одинаковыми. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | Файлы с расширением .BMP представляют собой файлы растровых изображений, используемые для хранения цифровых битовых карт. Эти изображения независимы от графического адаптера и также называются форматом device independent bitmap (DIB). Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/bmp/). |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | Файлы с расширением .doc представляют документы, созданные Microsoft Word или другими текстовыми процессорами, в бинарном формате файла. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/word-processing/doc/). |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | Файлы DOCM — это документы, созданные Microsoft Word 2007 или более поздних версий, с возможностью выполнения макросов. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/word-processing/docm/). |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX — известный формат документов Microsoft Word. Появился в 2007 году вместе с выпуском Microsoft Office 2007; структура этого нового формата документа была изменена с простого бинарного формата на комбинацию XML и бинарных файлов. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/word-processing/docx/). |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | Файлы с расширением .DOT являются шаблонными файлами, созданными Microsoft Word, содержащими предварительно отформатированные настройки для создания последующих файлов DOC или DOCX. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/word-processing/dot/). |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | Файл с расширением DOTM представляет собой шаблонный файл, созданный в Microsoft Word 2007 или более поздних версиях. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/word-processing/dotm/). |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | Файлы с расширением .DOTX являются шаблонными файлами, созданными Microsoft Word, содержащими предварительно отформатированные настройки для создания последующих файлов DOCX. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/word-processing/dotx/). |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | Формат файла EML представляет электронные сообщения, сохранённые с помощью Outlook и других соответствующих приложений. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/email/eml/). |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | Формат файла EMLX реализован и разрабатывается компанией Apple. Приложение Apple Mail использует формат EMLX для экспорта электронных писем. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/email/emlx/). |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML хранится в плоском XML‑файле вместо ZIP‑пакета (.xml). Узнайте больше о этом формате файла [здесь](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML Macro-Enabled Document хранится в плоском XML‑файле вместо ZIP‑пакета (.xml). Узнайте больше о этом формате файла [здесь](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Office Open XML WordprocessingML Template (без макросов) хранится в плоском XML‑файле вместо ZIP‑пакета (.xml). Узнайте больше о этом формате файла [здесь](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Office Open XML WordprocessingML Macro-Enabled Template хранится в плоском XML‑файле вместо ZIP‑пакета (.xml). Узнайте больше о этом формате файла [здесь](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | GIF (Graphics Interchange Format) — тип сильно сжатого изображения. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/gif/). |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | JPEG — тип формата изображения, сохраняемый с помощью метода сжатия с потерями. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF) — система кодирования изображений и передовой стандарт сжатия изображений. С использованием вейвлет‑технологии JPEG 2000 может кодировать контент без потерь в любой требуемой качестве. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | JPEG — тип формата изображения, сохраняемый с помощью метода сжатия с потерями. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM) — это система кодирования изображений и передовой стандарт сжатия изображений. Благодаря использованию вейвлет‑технологии JPEG 2000 может кодировать контент без потерь в любом качестве сразу. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX) — это система кодирования изображений и передовой стандарт сжатия изображений. Благодаря использованию вейвлет‑технологии JPEG 2000 может кодировать контент без потерь в любом качестве сразу. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/image/jp2/). |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG — это файловый формат, используемый Microsoft Outlook и Exchange для хранения электронных сообщений, контактов, встреч или других задач. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/email/msg/). |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | Файлы ODT — это тип документов, создаваемых с помощью текстовых процессоров, основанных на формате OpenDocument Text. Они создаются в приложениях, таких как бесплатный OpenOffice Writer, и могут содержать текст, изображения, объекты и стили. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/odt/). |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | Файлы с расширением .OFT представляют собой шаблоны сообщений, созданные с помощью Microsoft Outlook. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/email/oft/). |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Файл Office Open XML (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Portable Document Format (PDF) — это тип документа, созданный Adobe в 1990‑х годах. Цель этого формата файлов заключалась в введении стандарта представления документов и других справочных материалов в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/view/pdf/). |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG, Portable Network Graphics, относится к типу растрового графического формата, использующего без потерь сжатие. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/image/png/). |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | Файлы с расширением POTM — это шаблоны Microsoft PowerPoint с поддержкой макросов. Файлы POTM создаются в PowerPoint 2007 и новее и содержат настройки по умолчанию, которые можно использовать для создания последующих презентаций. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/presentation/potm/). |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | Файлы с расширением .POTX представляют собой шаблоны презентаций Microsoft PowerPoint, созданные в Microsoft PowerPoint 2007 и новее. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/presentation/potx/). |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS, PowerPoint Slide Show, файлы создаются с помощью Microsoft PowerPoint для показа слайдов. Чтение и создание файлов PPS поддерживается Microsoft PowerPoint 97‑2003. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/presentation/pps/). |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | Файлы с расширением PPSM представляют собой формат слайд‑шоу с поддержкой макросов, созданный в Microsoft PowerPoint 2007 и новее. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/presentation/ppsm/). |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX, Power Point Slide Show, файлы создаются с помощью Microsoft PowerPoint 2007 и новее для показа слайдов. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/presentation/ppsx/). |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | Файл с расширением PPT представляет собой файл PowerPoint, содержащий набор слайдов для отображения в виде слайд‑шоу. Он определяет двоичный формат файлов, используемый Microsoft PowerPoint 97‑2003. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/presentation/ppt/). |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | Файлы с расширением PPTM — это презентации с поддержкой макросов, созданные в Microsoft PowerPoint 2007 и более новых версиях. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/presentation/pptm/). |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | Файлы с расширением PPTX — это презентации, созданные популярным приложением Microsoft PowerPoint. В отличие от предыдущей версии формата презентаций PPT, который был бинарным, формат PPTX основан на открытом XML‑формате презентаций Microsoft PowerPoint. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/presentation/pptx/). |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Введённый и задокументированный Microsoft формат Rich Text Format (RTF) представляет метод кодирования отформатированного текста и графики для использования в приложениях. Формат облегчает кроссплатформенный обмен документами с другими продуктами Microsoft, тем самым служит цели совместимости. Узнайте больше об этом файловом формате [здесь](https://wiki.fileformat.com/word-processing/rtf/). |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF или TIF, Tagged Image File Format, представляет растровые изображения, предназначенные для использования на различных устройствах, соответствующих этому стандарту файлового формата. Узнайте больше об этом файловом формате [здесь](https://wiki.fileformat.com/image/tiff/). |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF или TIF, Tagged Image File Format, представляет растровые изображения, предназначенные для использования на различных устройствах, соответствующих этому стандарту файлового формата. Узнайте больше об этом файловом формате [здесь](https://wiki.fileformat.com/image/tiff/). |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | Представляет неизвестный тип файла. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW — это формат файлов Visio Graphics Service, который определяет потоки и хранилища, необходимые для рендеринга веб‑рисунка. Узнайте больше об этом файловом формате [здесь](https://wiki.fileformat.com/web/vdw/). |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Любой рисунок или диаграмма, созданные в Microsoft Visio, но сохранённые в формате XML, имеют расширение .VDX. Узнайте больше об этом файловом формате [здесь](https://wiki.fileformat.com/image/vdx/). |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | Файлы VSD — это рисунки, созданные с помощью приложения Microsoft Visio для представления разнообразных графических объектов и их взаимосвязей. Узнайте больше об этом файловом формате [здесь](https://wiki.fileformat.com/image/vsd/). |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | Файлы с расширением VSDM — это файлы рисунков, созданные в приложении Microsoft Visio и поддерживающие макросы. Узнайте больше об этом файловом формате [здесь](https://wiki.fileformat.com/image/vsdm/). |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | Файлы с расширением .VSDX представляют формат файлов Microsoft Visio, введённый, начиная с Microsoft Office 2013. Узнайте больше об этом файловом формате [здесь](https://wiki.fileformat.com/image/vsdx/). |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS — это файлы шаблонов, созданные в Microsoft Visio 2007 и более ранних версиях. Файлы шаблонов предоставляют объекты рисунков, которые могут быть включены в рисунок .VSD Visio. Узнайте больше об этом файловом формате [здесь](https://wiki.fileformat.com/image/vss/). |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | Файлы с расширением .VSSM — это файлы шаблонов Microsoft Visio, которые поддерживают макросы. Узнайте больше об этом файловом формате [здесь](https://wiki.fileformat.com/image/vssm/). |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | Файлы с расширением .VSSX — это шаблоны рисунков, созданные в Microsoft Visio 2013 и более новых версиях. Узнайте больше об этом файловом формате [здесь](https://wiki.fileformat.com/image/vssx/). |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | Файлы с расширением VST — это векторные изображения, созданные в Microsoft Visio и служащие шаблонами для создания последующих файлов. Узнайте больше об этом файловом формате [здесь](https://wiki.fileformat.com/image/vst/). |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | Файлы с расширением VSTM — это файлы шаблонов, созданные в Microsoft Visio и поддерживающие макросы. Узнайте больше об этом файловом формате [здесь](https://wiki.fileformat.com/image/vstm/). |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | Файлы с расширением VSTX — это файлы шаблонов рисунков, созданные в Microsoft Visio 2013 и более новых версиях. Узнайте больше об этом файловом формате [здесь](https://wiki.fileformat.com/image/vstx/). |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | Файлы с расширением .VSX относятся к шаблонам, состоящим из рисунков и фигур, используемых для создания диаграмм в Microsoft Visio. Узнайте больше об этом файловом формате [здесь](https://wiki.fileformat.com/image/vsx/). |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | Файл с расширением VTX — это шаблон рисунка Microsoft Visio, сохранённый на диск в формате XML. Узнайте больше об этом файловом формате [здесь](https://wiki.fileformat.com/image/vtx/). |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP, представленный Google, — это современный растровый веб‑формат изображений, основанный на без потерь и с потерями сжатии. Он обеспечивает то же качество изображения, значительно уменьшая размер файла. Узнайте больше об этом файловом формате [здесь](https://wiki.fileformat.com/image/webp/). |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | Файлы с расширением XLS представляют формат Excel Binary File Format. Такие файлы могут быть созданы Microsoft Excel, а также другими аналогичными программами для работы с таблицами, такими как OpenOffice Calc или Apple Numbers. Узнайте больше об этом файловом формате [здесь](https://wiki.fileformat.com/specification/spreadsheet/xls/). |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | Формат файла XLSB определяет Excel Binary File Format, который представляет собой набор записей и структур, описывающих содержимое рабочей книги Excel. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/specification/spreadsheet/xlsb/). |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | Файлы с расширением XLSM представляют собой тип файлов электронных таблиц, поддерживающих макросы. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/specification/spreadsheet/xlsm/). |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX — известный формат документов Microsoft Excel, который был представлен компанией Microsoft вместе с выпуском Microsoft Office 2007. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/specification/spreadsheet/xlsx/). |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | Файлы с расширением .XLT являются шаблонными файлами, созданными в Microsoft Excel — приложении для работы с электронными таблицами, входящем в состав пакета Microsoft Office. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/specification/spreadsheet/xlt/). |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | Расширение файла XLTM обозначает файлы, генерируемые Microsoft Excel как шаблоны с поддержкой макросов. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/specification/spreadsheet/xltm/). |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | Файлы с расширением XLTX представляют собой шаблоны Microsoft Excel, основанные на спецификациях формата Office OpenXML. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/specification/spreadsheet/xltx/). |

### Примечания

Этот класс предоставляет методы для получения списка всех типов файлов, поддерживаемых **GroupDocs.Watermark**.**Узнать больше**

* [Supported Document Formats](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Get supported file formats](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### См. также

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
