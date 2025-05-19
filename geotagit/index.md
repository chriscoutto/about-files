---
layout: plain
title: GeoTagit
---

# GeoTagIt

A modern, privacy-focused web application that extracts and displays GPS coordinates from your photos, built with React and TypeScript.

![Photo GeoTagger Screenshot](https://images.pexels.com/photos/1051075/pexels-photo-1051075.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2)

## Features

- 📍 Extract GPS coordinates from JPEG images
- 📅 Toggle date and time information with live preview
- 🖼️ Batch process multiple images
- 💾 Download individual, selected, or all processed images
- 🔍 Interactive image viewer with zoom and pan
- 🗺️ Draggable mini-map preview
- 🔒 Client-side processing (no data uploaded to servers)
- 📱 Responsive design for all devices
- 🖱️ Drag and drop file upload support

## Technology Stack

- React 18
- TypeScript
- Tailwind CSS
- Vite
- EXIF.js for image metadata extraction
- JSZip for batch downloads

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Usage

1. Click "Select Photos" to choose JPEG images
2. Or drag and drop your photos directly into the upload area
3. Toggle "Show Date/Time" to include timestamp information
4. Click "Process Images" to extract GPS data
5. View, zoom, and interact with processed images
6. Download individual images or use "Download All" for a ZIP file
7. Use the checkbox to select multiple images for batch download

## Privacy & Security

- All processing happens in your browser
- No data or images are uploaded to any server
- Images are cleared from memory after download
- No persistent storage or cookies used
- No external API calls except for embedded Google Maps preview
- All image processing is done locally using native JavaScript APIs

## Browser Compatibility

Tested and working in:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Technical Details

- Maximum file upload: 50 files at once
- Maximum file size: 10MB per JPEG image
- Supported format: JPEG images with GPS EXIF data
- No local storage or cookies used
- Memory management: Images are processed one at a time and cleared after download
- Image viewer features:
  - Double-click to zoom in/out
  - Mouse wheel for smooth zooming
  - Click and drag to pan

## License

MIT License - feel free to use this project for personal or commercial purposes.

## Creator

Created by [brewedbychris](mailto:brewedbychris@gmail.com)
