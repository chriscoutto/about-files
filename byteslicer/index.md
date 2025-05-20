

# ByteSlicer

A powerful, browser-based PDF splitting tool that runs entirely in your browser. No server uploads, no data transmission - just pure client-side magic.

![ByteSlicer Screenshot](https://images.pexels.com/photos/7376/startup-photos.jpg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2)

## Features

- 🚀 **Pure Browser Magic**: All processing happens locally in your browser
- 🔒 **Privacy First**: No file uploads, no server communication
- ⚡ **Lightning Fast**: Split PDFs instantly without waiting for uploads/downloads
- 📦 **Smart Chunking**: Automatically splits PDFs into size-specific chunks
- 🎯 **Precise Control**: Set exact maximum file sizes for your chunks
- 📱 **Responsive Design**: Works seamlessly on desktop and mobile devices

## How to Use

1. Open ByteSlicer in your browser
2. Drag & drop your PDF file (or click to select)
3. Set your desired maximum chunk size (in MB)
4. Click "slice it" and watch the magic happen
5. Download your split PDF files as a ZIP archive

## Technical Details

ByteSlicer leverages modern web technologies to provide a seamless PDF splitting experience:

- PDF processing with `pdf-lib`
- ZIP file creation with `jszip`
- File handling with native File System API
- Real-time progress monitoring
- Efficient memory management

## Privacy & Security

ByteSlicer is designed with privacy in mind:
- All processing happens locally in your browser
- No files are ever uploaded to any server
- No data is stored or transmitted
- Works offline after initial page load

## Browser Support

Supports all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

## Development

To run ByteSlicer locally:

```bash
npm install
npm run dev
```

## License

MIT © [brewedbychris]

## Credits

Created with ❤️ by brewedbychris
