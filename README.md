# YouTube-Studio-like-Scratch-Interface


A Scratch-style video editor interface built with HTML, CSS, and JavaScript that mimics YouTube Studio's functionality. This project provides a drag-and-drop video editing experience entirely in the browser.



## ✨ Features

### 🎬 Media Library
- **Categorized Media**: Organized by video, audio, images, and text assets
- **Drag & Drop**: Easily drag media items onto the timeline
- **Visual Thumbnails**: Color-coded media types for quick identification

### ⏱️ Timeline Editor
- **Multi-track Timeline**: Separate tracks for video, audio, and text
- **Clip Manipulation**: Drag, resize, and rearrange clips on the timeline
- **Playhead Control**: Visual playhead with playback position
- **Zoom Controls**: Zoom in/out for detailed editing

### 🎨 Editing Tools
- **Video Properties**: Adjust brightness, contrast, and volume
- **Edit Tools**: Split, trim, and delete clips
- **Effects Panel**: Access filters, transitions, and captions
- **Export Settings**: Choose between 480p, 720p, and 1080p resolutions

### 🎛️ Playback Controls
- **Play/Pause**: Control video playback
- **Time Navigation**: Skip forward/backward by 5 seconds
- **Time Display**: Current time and total duration

## 🚀 Quick Start

### Option 1: Direct Use
Simply open the `index.html` file in any modern web browser.

### Option 2: Local Development
1. Clone the repository:
```bash
git clone https://github.com/yourusername/scratch-studio.git
cd scratch-studio
```

2. Open the project in your favorite code editor

3. Launch a local server (optional but recommended):
```bash
# Using Python
python -m http.server 8000

# Using Node.js with http-server
npx http-server
```

4. Open `http://localhost:8000` in your browser

## 🛠️ Technologies Used

- **HTML5**: Semantic structure and accessibility
- **CSS3**: Modern styling with Flexbox and Grid layouts
- **JavaScript (Vanilla)**: No frameworks or libraries required
- **Font Awesome**: Icon toolkit for UI elements
- **Drag & Drop API**: Native browser APIs for media manipulation

## 📁 Project Structure

```
scratch-studio/
│
├── index.html          # Main HTML file
├── README.md           # This documentation file
│
├── assets/             # (Optional) For future assets
│   ├── images/         # Screenshots and icons
│   └── fonts/          # Custom fonts
│
└── features/           # (Future expansion)
    ├── media-library.js
    ├── timeline-editor.js
    └── export-tools.js
```

## 🎮 How to Use

### Adding Media to Timeline
1. Browse media items in the left panel
2. Click and drag any media item to the timeline
3. Drop it on the desired track and position

### Editing Clips
1. **Select a clip**: Click on any clip in the timeline
2. **Adjust properties**: Use sliders in the right panel
3. **Apply effects**: Click on effects buttons for filters and transitions
4. **Edit clips**: Use split, trim, or delete tools

### Playing Your Project
1. Click the play button in the footer controls
2. Watch the preview window
3. Use rewind/forward buttons to navigate

### Exporting Your Video
1. Click the "Export Video" button in the header
2. Choose desired resolution from the right panel
3. Your video will be processed and downloaded

## 🔧 Customization

### Changing Colors
Modify the CSS variables in the `<style>` section:
```css
:root {
    --primary-color: #3da6ff;
    --danger-color: #ff0000;
    --success-color: #1db954;
    --dark-bg: #0f0f0f;
    --card-bg: #212121;
}
```

### Adding New Media Types
Extend the media library by adding new items in the HTML:
```html
<div class="media-item" data-type="transition" data-duration="2">
    <div class="media-thumbnail transition-thumb">
        <i class="fas fa-star"></i>
    </div>
    <div class="media-label">Fade Transition</div>
</div>
```

## 📱 Browser Compatibility

| Browser | Version | Status |
|---------|---------|--------|
| Chrome  | 60+     | ✅ Full Support |
| Firefox | 55+     | ✅ Full Support |
| Safari  | 12+     | ✅ Full Support |
| Edge    | 79+     | ✅ Full Support |

## 🚧 Future Enhancements

- [ ] **Real Media Upload**: Support for actual video/audio/image files
- [ ] **Cloud Save**: Save projects to cloud storage
- [ ] **Advanced Effects**: More filters and transitions
- [ ] **Audio Waveforms**: Visual audio editing
- [ ] **Keyboard Shortcuts**: Quick editing with keyboard
- [ ] **Collaboration**: Multi-user editing support
- [ ] **Export Formats**: MP4, GIF, WebM options

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines
- Follow the existing code style
- Add comments for complex logic
- Update documentation when adding features
- Test changes in multiple browsers

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by YouTube Studio and Scratch
- Icons provided by [Font Awesome](https://fontawesome.com)
- Color scheme inspired by modern video editors
- Design principles from professional NLE software

## 📞 Support

demonstration project. In a production environment, additional security measures, performance optimizations, and backend services would be implemented.*
