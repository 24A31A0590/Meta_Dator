# 📄 MetaExtract - File Metadata Viewer

A powerful web application that extracts and displays metadata from uploaded files, with special support for images (including EXIF data) camera information and PDFs.

![MetaExtract Demo](screenshots/demo.gif)

## ✨ Features

- **📤 File Upload**: Upload files via click or drag-and-drop
- **🖼️ Image Preview**: Thumbnail preview for images with dimensions
- **📊 Basic Metadata**: 
  - File name, size, MIME type
  - Dimensions (for images)
  - Creation/Modification date
- **📷 EXIF Data Extraction** (for images):
  - Camera model and manufacturer
  - Exposure settings (time, aperture, ISO)
  - Focal length
  - GPS coordinates (latitude, longitude, altitude)
  - Date/time photo was taken
- **📄 PDF Support**: Basic metadata extraction from PDF files
- **🎨 Modern UI**: Clean, responsive interface with Font Awesome icons
- **📱 Mobile Friendly**: Fully responsive design for all devices

## 🛠️ Technologies Used

- **HTML5** - Structure and semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **Vanilla JavaScript** - Core functionality (no frameworks)
- **File API** - Browser file handling
- **EXIF.js** - EXIF metadata extraction from images
- **Font Awesome 6** - Icon library for better UI

## 📦 Installation

### Option 1: Direct Download

1. Download the `index.html` file
2. Open it in your web browser (Chrome, Firefox, Edge, or Safari)

### Option 2: Clone Repository

```bash
git clone https://github.com/yourusername/metaextract.git
cd metaextract
