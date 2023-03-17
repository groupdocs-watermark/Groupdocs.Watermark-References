---
title: FileType
second_title: Справочник по API GroupDocs.Watermark для .NET
description: Представляет тип файла.
type: docs
weight: 40
url: /ru/net/groupdocs.watermark.common/filetype/
---
## FileType class

Представляет тип файла.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | Получает суффикс имени файла (включая точку "."), например, ".doc". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | Получает имя типа файла, например, "Документ Microsoft Word". |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | Получает семейство форматов. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | Сопоставляет расширение файла с типом файла. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | Определяет, является ли текущий[`FileType`](../filetype) совпадает с указанным[`FileType`](../filetype) объект. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | Определяет, является ли текущий[`FileType`](../filetype) совпадает с указанным объектом. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | Возвращает хеш-код для текущего[`FileType`](../filetype) объект. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | Возвращает строку, представляющую текущий объект. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | Извлекает поддерживаемые типы файлов. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | Определяет, являются ли два[`FileType`](../filetype) объекты одинаковые. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | Определяет, являются ли два[`FileType`](../filetype) объекты не одинаковы. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | Файлы с расширением .BMP представляют собой файлы растровых изображений, которые используются для хранения растровых цифровых изображений. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/image/bmp/) . |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | Файлы с расширением .doc представляют собой документы, сгенерированные Microsoft Word или другими текстовыми редакторами в двоичном формате. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/word-processing/doc/) . |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | Файлы DOCM представляют собой документы Microsoft Word 2007 или более поздней версии с возможностью запуска макросов. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/word-processing/docm/) . |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX — широко известный формат документов Microsoft Word. Представленный в 2007 году с выпуском Microsoft Office 2007, структура этого нового формата документа была изменена с простого двоичного на комбинацию XML и двоичных файлов. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/word-processing/docx/) . |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | Файлы с расширением .DOT представляют собой файлы шаблонов, созданные Microsoft Word для предварительного форматирования настроек для создания дополнительных файлов DOC или DOCX. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/word-processing/dot/) . |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | Файл с расширением DOTM представляет собой файл шаблона, созданный с помощью Microsoft Word 2007 или более поздней версии. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/dotm/) . |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | Файлы с расширением DOTX представляют собой файлы шаблонов, созданные Microsoft Word для предварительно отформатированных настроек для создания дополнительных файлов DOCX. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/word-processing/dotx/) . |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | Формат файла EML представляет собой сообщения электронной почты, сохраненные с помощью Outlook и других соответствующих приложений. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/email/eml/) . |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | Формат файла EMLX реализован и разработан Apple. Приложение Apple Mail использует формат файлов EMLX для экспорта электронных писем. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/email/emlx/) . |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML хранится в простом XML-файле, а не в ZIP-архиве (.xml). Подробнее об этом формате файла[здесь](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Документ Office Open XML WordprocessingML с поддержкой макросов хранится в плоском XML-файле, а не в ZIP-архиве (.xml). Подробнее об этом формате файла[здесь](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Шаблон Office Open XML WordprocessingML (без макросов), хранящийся в плоском XML-файле, а не в ZIP-архиве (.xml). Подробнее об этом формате файла[здесь](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Шаблон Office Open XML WordprocessingML с поддержкой макросов, хранящийся в простом XML-файле, а не в ZIP-архиве (.xml). Подробнее об этом формате файла[здесь](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | Формат GIF или Graphical Interchange Format представляет собой тип сильно сжатого изображения. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/image/gif/) . |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | JPEG — это тип формата изображения, который сохраняется с использованием метода сжатия с потерями. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF) — это система кодирования изображений и современный стандарт сжатия изображений. Разработанный, с использованием технологии вейвлетов JPEG 2000 может кодировать контент без потерь сразу в любом качестве. Узнайте больше о этом формате файла[здесь](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | JPEG — это тип формата изображения, который сохраняется с использованием метода сжатия с потерями. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM) — это система кодирования изображений и современный стандарт сжатия изображений. Разработанный, с использованием технологии вейвлетов JPEG 2000 может кодировать контент без потерь сразу в любом качестве. Узнайте больше о этом формате файла[здесь](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX) — это система кодирования изображений и современный стандарт сжатия изображений. Разработанный, с использованием технологии вейвлетов JPEG 2000 может кодировать контент без потерь сразу в любом качестве. Узнайте больше о этом формате файла[здесь](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG — это формат файла, используемый Microsoft Outlook и Exchange для хранения сообщений электронной почты, контактов, встреч или других задач. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/email/msg/) . |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | Файлы ODT представляют собой тип документов, созданных с помощью приложений для обработки текстов, основанных на формате текстового файла OpenDocument . Они создаются с помощью приложений текстового процессора, таких как бесплатный OpenOffice Writer, и могут содержать такое содержимое, как текст, изображения, объекты и стили. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/word-processing/odt/) . |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | Файлы с расширением .OFT представляют собой файлы шаблонов сообщений, созданные с помощью Microsoft Outlook. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/email/oft/) . |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Office открывает xml-файл (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Portable Document Format (PDF) — это тип документа, созданный Adobe еще в 1990-х годах. Цель этого формата файла заключалась в том, чтобы ввести стандарт для представления документов и других справочных материалов в формате , который не зависит от прикладного программного обеспечения, аппаратного обеспечения, а также операционной системы. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/view/pdf/) . |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG, переносимая сетевая графика, относится к типу формата файла растрового изображения, в котором используется сжатие без потерь. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/image/png/) . |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | Файлы с расширением POTM представляют собой файлы шаблонов Microsoft PowerPoint с поддержкой макросов. Файлы POTM создаются с помощью PowerPoint 2007 или более поздней версии и содержат настройки по умолчанию, которые можно использовать для создания дополнительных файлов презентаций. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/presentation/potm/) . |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | Файлы с расширением .POTX представляют шаблоны презентаций Microsoft PowerPoint, созданные с помощью Microsoft PowerPoint 2007 и более поздних версий. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/presentation/potx/) . |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS, слайд-шоу PowerPoint, файлы создаются с помощью Microsoft PowerPoint для целей слайд-шоу. Чтение и создание файлов PPS поддерживается Microsoft PowerPoint 97-2003. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/presentation/pps/) . |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | Файлы с расширением PPSM представляют собой формат файлов слайд-шоу с поддержкой макросов, созданный с помощью Microsoft PowerPoint 2007 или более поздней версии. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/presentation/ppsm/) . |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX, слайд-шоу Power Point, файл создается с использованием Microsoft PowerPoint 2007 и выше для целей слайд-шоу. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/presentation/ppsx/) . |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | Файл с расширением PPT представляет собой файл PowerPoint, состоящий из набора слайдов для , отображаемых в виде слайд-шоу. Он указывает формат двоичного файла, используемый Microsoft PowerPoint 97-2003. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/presentation/ppt/) . |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | Файлы с расширением PPTM представляют собой файлы презентаций с поддержкой макросов, созданные с помощью Microsoft PowerPoint 2007 или более поздних версий. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/presentation/pptm/) . |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | Файлы с расширением PPTX представляют собой файлы презентаций, созданные с помощью популярного приложения Microsoft PowerPoint. В отличие от предыдущей версии формата файлов презентаций PPT, которая была двоичной, формат PPTX основан на формате файлов презентаций Microsoft PowerPoint open XML. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/presentation/pptx/) . |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Представленный и задокументированный Microsoft формат Rich Text Format (RTF) представляет собой метод кодирования текста и графики в формате для использования в приложениях. Формат облегчает межплатформенный обмен document с другими продуктами Microsoft, что служит цели функциональной совместимости. Узнайте больше о этом формате файла[здесь](https://wiki.fileformat.com/word-processing/rtf/) . |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF или TIF, Tagged Image File Format, представляет собой растровые изображения, которые предназначены для использования на различных устройствах, соответствующих этому стандарту формата файлов. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF или TIF, Tagged Image File Format, представляет собой растровые изображения, которые предназначены для использования на различных устройствах, соответствующих этому стандарту формата файлов. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | Представляет неизвестный тип файла. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW — это формат файла службы графики Visio, который определяет потоки и хранилища, необходимые для рендеринга веб-рисунка. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/web/vdw/) . |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Любой рисунок или диаграмма, созданные в Microsoft Visio, но сохраненные в формате XML, имеют расширение .VDX. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/image/vdx/) . |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | Файлы VSD представляют собой рисунки, созданные с помощью приложения Microsoft Visio для представления различных объектов graphical и взаимосвязей между ними. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/image/vsd/) . |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | Файлы с расширением VSDM — это файлы чертежей, созданные с помощью приложения Microsoft Visio, которое поддерживает макросы. Подробнее об этом формате файла [здесь](https://wiki.fileformat.com/image/vsdm/) . |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | Файлы с расширением .VSDX представляют формат файлов Microsoft Visio, представленный в Microsoft Office 2013 и более поздних версиях. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/image/vsdx/) . |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS — это файлы шаблонов, созданные с помощью Microsoft Visio 2007 и более ранних версий. Файлы трафаретов содержат объекты drawing , которые можно включить в чертеж .VSD Visio. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/image/vss/) . |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | Файлы с расширением .VSSM — это файлы Microsoft Visio Stencil, которые поддерживают макросы. Дополнительные сведения об этом формате файлов[здесь](https://wiki.fileformat.com/image/vssm/) . |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | Файлы с расширением .VSSX представляют собой наборы элементов для рисования, созданные с помощью Microsoft Visio 2013 и более поздних версий. Подробнее об этом формате файла [здесь](https://wiki.fileformat.com/image/vssx/) . |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | Файлы с расширением VST представляют собой файлы векторных изображений, созданные с помощью Microsoft Visio, и служат шаблоном для создания дополнительных файлов. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/image/vst/) . |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | Файлы с расширением VSTM представляют собой файлы шаблонов, созданные с помощью Microsoft Visio и поддерживающие макросы. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/image/vstm/) . |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | Файлы с расширениями VSTX представляют собой файлы шаблонов чертежей, созданные с помощью Microsoft Visio 2013 и более поздних версий. Подробнее об этом формате файла [здесь](https://wiki.fileformat.com/image/vstx/) . |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | Файлы с расширением .VSX относятся к шаблонам, состоящим из рисунков и форм, которые используются для создания диаграмм в Microsoft Visio. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/image/vsx/) . |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | Файл с расширением VTX представляет собой шаблон чертежа Microsoft Visio, который сохраняется на диске в формате файла XML. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/image/vtx/) . |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP, представленный Google, представляет собой современный формат файлов растровых веб-изображений, основанный на сжатии без потерь и с потерями. Он обеспечивает такое же качество изображения при значительном уменьшении размера изображения. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/image/webp/) . |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | Файлы с расширением XLS представляют формат двоичных файлов Excel. Такие файлы могут быть созданы Microsoft Excel , а также другими подобными программами для работы с электронными таблицами, такими как OpenOffice Calc или Apple Numbers. Узнайте больше о этом формате файла[здесь](https://wiki.fileformat.com/specification/spreadsheet/xls/) . |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | Формат файла XLSB определяет формат двоичного файла Excel, который представляет собой набор записей и структур , определяющих содержимое книги Excel. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/specification/spreadsheet/xlsb/) . |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | Файлы с расширением XLSM — это тип файлов электронных таблиц, поддерживающих макросы. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/specification/spreadsheet/xlsm/) . |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX — широко известный формат документов Microsoft Excel, который был представлен Microsoft в выпуске Microsoft Office 2007. Узнайте больше об этом формате файла format [здесь](https://wiki.fileformat.com/specification/spreadsheet/xlsx/) . |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | Файлы с расширением .XLT представляют собой файлы шаблонов, созданные с помощью Microsoft Excel, который представляет собой приложение для работы с электронными таблицами , входящее в состав пакета Microsoft Office. Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/specification/spreadsheet/xlt/) . |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | Расширение файла XLTM представляет файлы, созданные Microsoft Excel, как файлы шаблонов Macro-enabled . Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/specification/spreadsheet/xltm/) . |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | Файлы с расширением XLTX представляют собой файлы шаблонов Microsoft Excel, основанные на спецификациях формата файлов Office OpenXML . Узнайте больше об этом файле format [здесь](https://wiki.fileformat.com/specification/spreadsheet/xltx/) . |

### Примечания

Этот класс предоставляет методы для получения списка всех типов файлов, поддерживаемых**GroupDocs.Водяной знак**.**Узнать больше**

* [Поддерживаемые форматы документов](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Получить поддерживаемые форматы файлов](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Получить информацию о документе](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Смотрите также

* пространство имен [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* сборка [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
