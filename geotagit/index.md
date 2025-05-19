---
layout: plain
title: GeoTagit
---

# GeoTagIt

A modern, privacy-focused web application that extracts and displays GPS coordinates from your photos, built with React, TypeScript, and Tailwind CSS.

![Photo GeoTagger Screenshot](https://images.pexels.com/photos/1051075/pexels-photo-1051075.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2)

## Features

- 📍 Extract GPS coordinates from JPEG images
- 📅 Toggle date/time information with live preview and instant reprocessing
- 🖼️ Batch process multiple images
- 💾 Download individual, selected, or all processed images
- 🔍 Interactive image viewer with zoom and pan
- 🗺️ Fixed-position mini-map with Google Maps integration
- 🔒 Client-side processing (no data uploaded to servers)
- 📱 Responsive design for all devices
- 🖱️ Drag and drop file upload support
- 🎨 Modern UI with Fira Code font
- 🔄 Real-time upload progress indicators
- 🗑️ Easy file management with clear all/individual remove
- 🔍 Detailed error handling and user feedback
- 📝 Built-in privacy policy and help documentation

## Technology Stack

- React 18 with TypeScript
- Tailwind CSS for styling
- Vite for development and building
- Lucide React for icons
- EXIF.js for image metadata extraction
- JSZip for batch downloads
- Google Maps for location preview

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
2. Drag and drop photos directly into the upload area
3. Monitor upload progress for each file
4. Toggle "Show Date/Time" to include timestamp information
5. Click "Process Images" to extract GPS data
6. View, zoom, and interact with processed images
7. Use checkboxes to select multiple images for batch download
8. Download individual images or use "Download All" for a ZIP file
9. Click the help icon for usage instructions
10. View privacy policy for data handling details

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

Want to request additional features or report bugs? Use the form at the bottom of the page to get in touch.

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
  - Fixed-position mini-map with Google Maps integration (browser viewing only)
  - Open location in Google Maps 

## Contact
Have feedback or a question? [Click here to reach out](https://tally.so/r/mDyX2l)

## Support the Project

If you find this tool useful, you can [buy me a brew](https://www.buymeacoffee.com/chriscoutto) to support development!
