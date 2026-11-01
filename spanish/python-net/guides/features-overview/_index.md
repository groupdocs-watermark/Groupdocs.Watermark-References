---
title: "Resumen de características"
linkTitle: "Features overview"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "GroupDocs.Watermark para Python a través de .NET agrega, busca y elimina marcas de agua de texto e imagen mediante una única API independiente del formato — con colocación específica por formato, edición del árbol de contenido, bloqueo y rasterización."
type: docs
url: /es/python-net/guides/features-overview/
is_root: false
weight: 30
---


GroupDocs.Watermark para Python a través de .NET agrega, busca y elimina marcas de agua en una amplia gama de [formatos de documento compatibles](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/). Cada operación sigue el mismo flujo de trabajo: abre un documento con [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/), llama a `add()`, `search()` o `remove()`, y luego `save()` el resultado de nuevo a su formato original. Las capacidades a continuación pueden combinarse libremente en una sola pasada.

## Text and image watermarks

Agrega marcas de agua de texto o imagen con estilo con control total sobre la fuente, el color, la opacidad, la rotación, la alineación y el tamaño. Las marcas de agua de imagen pueden cargarse desde un archivo o un flujo. Consulta [Agregar marcas de agua de texto](/watermark/python-net/guides/add-text/) y [Agregar marcas de agua de imagen](/watermark/python-net/guides/add-image/).

## Customization and tiling

Posiciona una marca de agua con coordenadas absolutas o alineación y márgenes relativos al contenedor, escálala en relación con la página, gírala y repítela en toda la página en un patrón repetitivo. Consulta [Personalizar marcas de agua](/watermark/python-net/guides/customize/), [Agregar marcas de agua repetidas](/watermark/python-net/guides/adding-repeated-watermarks/), y [Agregar marcas de agua de texto](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/).

## Format-specific placement

Coloca marcas de agua usando las opciones que se ajustan a cada formato — artefactos PDF, anotaciones y anotaciones solo de impresión; diapositivas de presentación, maestros, diseños y notas; hojas de cálculo, fondos y encabezados/pies de página; páginas de Visio; y secciones y páginas de Word bloqueadas. Consulta [Agregar marcas de agua a documentos PDF](https://docs.groupdocs.com/watermark/python-net/add-watermarks-to-pdf-documents/) y los demás temas de formato en la [Guía del desarrollador](https://docs.groupdocs.com/watermark/python-net/adding-watermarks/).

## Searching, modifying, and removing

Encuentra marcas de agua ya presentes en un documento — incluidas las añadidas por herramientas de terceros — mediante texto exacto, expresión regular, similitud de imagen o formato de texto, y combina criterios con `and_`/`or_`/`not_`. Una vez encontradas, reemplaza su texto o imagen, o elimínalas. Consulta [Buscar marcas de agua](/watermark/python-net/guides/searching-watermarks/), [Modificar propiedades de marcas de agua encontradas](https://docs.groupdocs.com/watermark/python-net/modifying-found-watermark-properties/), y [Eliminar marcas de agua encontradas](https://docs.groupdocs.com/watermark/python-net/removing-found-watermarks/).

## Working with existing content

`Watermarker.get_content()` expone un árbol de contenido específico de formato para que puedas inspeccionar y editar formas existentes, PDF XObjects/artifacts/annotations, adjuntos, fondos y encabezados/pies de página — y puedes aplicar marca de agua a las imágenes incrustadas dentro de un documento con `get_images()`. Ver [Adding watermark to images inside a document](https://docs.groupdocs.com/watermark/python-net/adding-watermark-to-images-inside-a-document/).

## Tamper resistance

Haz que las marcas de agua sean difíciles de eliminar bloqueándolas, protegiendo documentos Word, añadiendo anotaciones PDF solo de impresión, o rasterizando páginas PDF para que la marca de agua no pueda ser editada. Ver [Locking watermark in word processing document](https://docs.groupdocs.com/watermark/python-net/locking-watermark-in-word-processing-document/) y [Rasterize document or page](https://docs.groupdocs.com/watermark/python-net/rasterize-document-or-page/).

## Document inspection

Lee el tipo de archivo, el recuento de páginas y el tamaño de un documento sin modificarlo, y enumera todos los formatos de archivo que la biblioteca admite. Ver [Get document info](/watermark/python-net/guides/get-document-info/) y [Get supported file formats](/watermark/python-net/guides/get-supported-file-formats/).

## On-premise

GroupDocs.Watermark para Python a través de .NET se ejecuta completamente en tu propia infraestructura — tus documentos nunca abandonan tu entorno. El paquete es una rueda auto‑contenida que incluye todo lo que necesita, por lo que no es necesario instalar Microsoft Office, OpenOffice o un tiempo de ejecución separado. Ver [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) para las plataformas compatibles y dependencias nativas.
