---
title: Preview and Print Files
---

import { ProFeature } from "@site/src/components/CommonBlocks";

The application supports previewing of many file types without the need of external viewer. It comes with the following viewer extensions:

- [3D Viewer](/extensions/3d-viewer) - 3d models in GLB, STL, OBJ format...
- [Media Player](/extensions/media-player) - WEBM, MKV, OGG, ...
- [E-Book Reader](/extensions/ebook-viewer) - EPUB
- [HTML Reader](/extensions/html-viewer) - HTML
- [Image Viewer](/extensions/image-viewer) - JPG, GIF, WEPB, TIF, TGA, ...
- [Link Opener](/extensions/url-viewer) - Bookmarks in URL, DESKTOP, WEBSITE ...
- [Markdown Reader](/extensions/md-viewer) - MD, MARKDOWN, MDOWN
- [MHTML Reader](/extensions/mhtml-viewer) - webpages in MHTML and and emails EML format
- [Mind Map Viewer](/extensions/mindmap-viewer) - Presents a MD or MARKDOWN file as mindmap
- [MSG Viewer](/extensions/msg-viewer) - Viewer for Emails in MSG format
- [PDF Viewer](/extensions/pdf-viewer) - PDF
- [RTF Viewer](/extensions/rtf-viewer) - RTF
- [Text Reader](/extensions/text-viewer) - TXT, JS, MD, ...
- [Document Viewer](/extensions/document-viewer) - DOCX
- [Slided Viewer](/extensions/slides-viewer) - Viewer for Reveal.js presentations
- [Spreadsheet Viewer](/extensions/spreadsheet-viewer) - ODS, XLSX, CSV, ...
- [ZIP Viewer](/extensions/archive-viewer) - ZIP

TagSpaces is designed with extensibility in mind so any other kind of file viewers can be easily developed and integrated.

> **Source code browser and editor** The text editor supports source code highlighting for many common programming languages. This in combination with the build in [JSON editor](/extensions/json-editor) makes the application a good source code navigator with basic editing capabilities. The intention here is not to makes TagSpaces your next IDE, but rather to give your quick overview of source code repositories.

## Assigning file viewer to file extensions

![settings tab file types](/media/settings-tab-file-types.svg)

## Printing files

The majority of the viewer extensions has tha ability to print the opened files, thanks to the build in print functionality. In the following short video, you can see how you can start the printing.

![printing files](/media/printing.gif)
