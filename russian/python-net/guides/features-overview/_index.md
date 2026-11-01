---
title: "Обзор функций"
linkTitle: "Features overview"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "GroupDocs.Watermark for Python via .NET добавляет, ищет и удаляет текстовые и графические водяные знаки через единый, независимый от формата API — с размещением, специфичным для формата, редактированием древовидного содержимого, блокировкой и растеризацией."
type: docs
url: /ru/python-net/guides/features-overview/
is_root: false
weight: 30
---


GroupDocs.Watermark for Python via .NET добавляет, ищет и удаляет водяные знаки в широком спектре [поддерживаемых форматов документов](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/). Каждая операция следует единому рабочему процессу: откройте документ с помощью [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/), вызовите `add()`, `search()` или `remove()`, затем `save()` результат обратно в его исходный формат. Ниже перечисленные возможности могут свободно комбинироваться в одном проходе.

## Text and image watermarks

Добавляйте стилизованные текстовые или графические водяные знаки с полным контролем над шрифтом, цветом, непрозрачностью, вращением, выравниванием и размером. Графические водяные знаки могут загружаться из файла или потока. См. [Добавить текстовые водяные знаки](/watermark/python-net/guides/add-text/) и [Добавить графические водяные знаки](/watermark/python-net/guides/add-image/).

## Customization and tiling

Разместите водяной знак с помощью абсолютных координат или выравнивания и отступов относительно родителя, масштабируйте его относительно страницы, вращайте и заполняйте всю страницу повторяющимся узором. См. [Настройка водяных знаков](/watermark/python-net/guides/customize/), [Добавление повторяющихся водяных знаков](/watermark/python-net/guides/adding-repeated-watermarks/), и [Добавление текстовых водяных знаков](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/).

## Format-specific placement

Размещайте водяные знаки, используя параметры, подходящие для каждого формата — артефакты PDF, аннотации и только печатные аннотации; слайды презентаций, шаблоны, макеты и заметки; листы электронных таблиц, фоны и колонтитулы; страницы Visio; а также заблокированные разделы и страницы Word. См. [Добавление водяных знаков в PDF‑документы](https://docs.groupdocs.com/watermark/python-net/add-watermarks-to-pdf-documents/) и другие темы форматов в [Руководстве разработчика](https://docs.groupdocs.com/watermark/python-net/adding-watermarks/).

## Searching, modifying, and removing

Найдите водяные знаки, уже присутствующие в документе — включая добавленные сторонними инструментами — по точному тексту, регулярному выражению, сходству изображений или форматированию текста, и комбинируйте критерии с помощью `and_`/`or_`/`not_`. После обнаружения замените их текст или изображение, либо удалите их. См. [Поиск водяных знаков](/watermark/python-net/guides/searching-watermarks/), [Изменение найденных свойств водяных знаков](https://docs.groupdocs.com/watermark/python-net/modifying-found-watermark-properties/), и [Удаление найденных водяных знаков](https://docs.groupdocs.com/watermark/python-net/removing-found-watermarks/).

## Working with existing content

`Watermarker.get_content()` предоставляет дерево содержимого, специфичное для формата, чтобы вы могли просматривать и редактировать существующие фигуры, PDF XObjects/артефакты/аннотации, вложения, фоновые изображения и колонтитулы — а также наносить водяной знак на изображения, встроенные в документ, с помощью `get_images()`. См. [Adding watermark to images inside a document](https://docs.groupdocs.com/watermark/python-net/adding-watermark-to-images-inside-a-document/).

## Tamper resistance

Сделайте водяные знаки трудно удаляемыми, блокируя их, защищая документы Word, добавляя только для печати PDF‑аннотации или растеризуя страницы PDF, чтобы водяной знак нельзя было удалить. См. [Locking watermark in word processing document](https://docs.groupdocs.com/watermark/python-net/locking-watermark-in-word-processing-document/) и [Rasterize document or page](https://docs.groupdocs.com/watermark/python-net/rasterize-document-or-page/).

## Document inspection

Получайте тип файла документа, количество страниц и размер без его изменения, а также перечисляйте все форматы файлов, поддерживаемые библиотекой. См. [Get document info](/watermark/python-net/guides/get-document-info/) и [Get supported file formats](/watermark/python-net/guides/get-supported-file-formats/).

## On-premise

GroupDocs.Watermark для Python через .NET полностью работает на вашей собственной инфраструктуре — ваши документы никогда не покидают вашу среду. Пакет представляет собой автономный wheel, который включает всё необходимое, поэтому не требуется установка Microsoft Office, OpenOffice или отдельного runtime. См. [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) для поддерживаемых платформ и нативных зависимостей.
