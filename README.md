# TestSampleHub

A comprehensive collection of sample test files and data for various file formats, designed for testing file processing, conversion, validation, and manipulation tools.

## 📁 Repository Structure

### 🗃️ [data/](./data)
Structured and unstructured data samples for testing data processing and parsing.

- **[json/](./data/json)** - JSON files including standard, GeoJSON, and HAR formats
- **[xml/](./data/xml)** - XML files with schemas and RSS feeds
- **[text/](./data/text)** - Plain text files of various sizes, configuration files (robots.txt, .htaccess, humans.txt)
- **[geographical/](./data/geographical)** - Geographic data formats (KML, GML, Shapefile, GeoJSON, SVG)
- **[markdown/](./data/markdown)** - Markdown documentation samples

### 📄 [documents/](./documents)
Office documents, PDFs, and ebooks for testing document processing and conversion.

#### PDF Files
- **[pdf/](./documents/pdf)** - Comprehensive PDF test samples:
  - **Basic PDFs**: simple.pdf, multi-page.pdf
  - **Security**: password-protected.pdf
  - **Interactive**: with-links.pdf, with-attachments.pdf
  - **[with-images/](./documents/pdf/with-images)** - PDFs with various image types (embedded, inline, base64, grayscale, CMYK)
  - **[with-forms/](./documents/pdf/with-forms)** - Interactive PDF forms (LaTeX, LibreOffice)
  - **[with-annotations/](./documents/pdf/with-annotations)** - PDFs with annotations and bookmarks
  - **[special-text/](./documents/pdf/special-text)** - Arabic/RTL text, multi-column layouts
  - **[special-formats/](./documents/pdf/special-formats)** - PDF/A archival format, XMP metadata

#### Office Files
- **[microsoft-office/](./documents/microsoft-office)** - Word (.doc, .docx), Excel (.xls, .xlsx), PowerPoint (.ppt, .pptx)
- **[opendocument/](./documents/opendocument)** - Writer (.odt), Calc (.ods), Impress (.odp)
- **[ebook/](./documents/ebook)** - EPUB format
- **[markdown/](./documents/markdown)** - Markdown document samples

### 🖼️ [images/](./images)
Image files in various formats, resolutions, and color modes.

- **[raster/](./images/raster)** - Raster images:
  - **[jpg/](./images/raster/jpg)** - JPEG images (standard and progressive)
  - **[png/](./images/raster/png)** - PNG images
  - **[gif/](./images/raster/gif)** - GIF images (static and animated)
  - **[webp/](./images/raster/webp)** - WebP format
  - **[tiff/](./images/raster/tiff)** - TIFF format
- **[vector/](./images/vector)** - Vector graphics:
  - **[svg/](./images/vector/svg)** - SVG images
  - **[ai/](./images/vector/ai)** - Adobe Illustrator files
- **[icons/](./images/icons)** - Favicon and Apple touch icons

### 💻 [code/](./code)
Code samples and web development files for testing code processing and syntax highlighting.

- **[web/](./code/web)** - Web technologies:
  - **[html/](./code/web/html)** - HTML files
  - **[css/](./code/web/css)** - CSS stylesheets
  - **[javascript/](./code/web/javascript)** - JavaScript files
- **[php/](./code/php)** - PHP source files
- **[markdown/](./code/markdown)** - Markdown code samples

### 🎵🎬 [media/](./media)
Audio and video files in various formats and codecs.

#### Audio Files
- **[audio/](./media/audio)** - Audio samples:
  - **Common formats**: MP3, AAC, OGG, WMA
  - **Lossless**: FLAC, WAV, AIFF
  - **Other**: AC3, AMR, AU, MIDI, MKA, RealAudio, VOC

#### Video Files
- **[video/](./media/video)** - Video samples:
  - **Common formats**: MP4, WebM, MOV
  - **Other**: AVI, FLV, MKV, MPG, SWF, WMV

### 🗜️ [archives/](./archives)
Archive and compressed file formats.

- ZIP, TAR, 7Z, RAR

## 🎯 Use Cases

- **File Format Testing** - Test file parsers, converters, and validators
- **Web Development** - Sample files for upload/download functionality testing
- **Document Processing** - Test PDF manipulation, Office document conversion
- **Media Processing** - Test audio/video encoding, image manipulation
- **Geographic Data** - Test GIS applications and mapping tools
- **SEO & Web Standards** - robots.txt, sitemap examples, favicon testing

## 📝 File Naming Conventions

- All directories use lowercase with hyphens (kebab-case)
- Generic test files are prefixed with `sample.`
- Specialized files use descriptive names (e.g., `progressive.jpg`, `animated.gif`)
- Geographic files use hyphenated names (e.g., `us-ski-areas.shp`)

## 🔗 Usage with CDN

All files are accessible via GitHub Raw CDN:

```
https://raw.githubusercontent.com/tristenWen/TestSampleHub/main/{path-to-file}
```

Example:
```
https://raw.githubusercontent.com/tristenWen/TestSampleHub/main/documents/pdf/simple.pdf
```

## 📋 Special Notes

### Password-Protected PDF
- **File**: `documents/pdf/password-protected.pdf`
- **Open Password**: `openpassword`
- **Permission Password**: `permissionpassword`

## 🤝 Contributing

This repository is designed to be a comprehensive sample file hub. Contributions of new file formats or improved samples are welcome.

## 📜 License

These files are provided for testing and development purposes. Please respect any applicable licenses for specific file formats or content.

---

**Repository**: [github.com/tristenWen/TestSampleHub](https://github.com/tristenWen/TestSampleHub)
