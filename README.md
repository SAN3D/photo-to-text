# Photo to Text Converter

A modern web application that converts text from images using OCR technology. This application uses advanced image preprocessing and Tesseract.js for accurate text extraction from images.

## 🌟 Features

- **Image Upload**
  - Drag & drop functionality
  - File browser support
  - Support for JPG, PNG, GIF formats

- **Advanced Processing**
  - Grayscale conversion
  - Contrast enhancement
  - Image sharpening
  - Number optimization mode

- **User-Friendly Interface**
  - Real-time progress indicator
  - Modern, responsive design
  - Instant copy to clipboard
  - Download extracted text
  - Processing options panel

## 🚀 Live Demo

Visit the live application: [Photo to Text Converter](https://your-username.github.io/photo-to-text/)

## 💻 Technologies Used

- HTML5 & Modern JavaScript
- Tailwind CSS for styling
- Tesseract.js v5 for OCR
- Font Awesome icons
- Google Fonts (Poppins)

## 📋 Usage Guide

1. **Upload Image**
   - Drag and drop an image onto the upload area, or
   - Click "Browse Files" to select an image

2. **Configure Processing** (Optional)
   - Enable/disable grayscale conversion
   - Adjust contrast enhancement
   - Toggle number optimization
   - Enable image sharpening

3. **Convert**
   - Click "Convert to Text"
   - Wait for processing to complete
   - View extracted text

4. **Manage Results**
   - Copy text to clipboard
   - Download as text file
   - Clear and start over

## 🛠️ Development

This project uses GitHub Actions for automated deployment to GitHub Pages. The deployment workflow is configured in `.github/workflows/deploy.yml`.

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/photo-to-text.git
   cd photo-to-text
   ```

2. Serve the files locally:
   ```bash
   python3 -m http.server 8000
   ```

3. Open `http://localhost:8000` in your browser

## 📝 License

MIT License - feel free to use this project for personal or commercial purposes.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📬 Contact

If you have any questions or suggestions, please open an issue in the GitHub repository.