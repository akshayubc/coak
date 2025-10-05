# Co.ak - Voice-Enhanced Code Runner

A modern, voice-controlled web-based code runner that supports HTML, CSS, and JavaScript with real-time preview. Features voice commands for rapid code generation and a beautiful, responsive interface.

## Features

### Voice Commands
- **HTML Commands**: "HTML basic", "HTML body", "Paragraph", "Heading", "Button"
- **CSS Commands**: "CSS style", "Clear CSS"
- **JavaScript Commands**: "JavaScript function", "Clear JavaScript"
- **Panel Control**: "Switch to HTML/CSS/JavaScript/Output"
- **Clear Commands**: "Clear HTML/CSS/JavaScript"

### Modern UI
- Beautiful gradient backgrounds and glassmorphism effects
- Responsive design that works on all devices
- Smooth animations and hover effects
- Professional code editor styling with syntax highlighting fonts

### Real-time Preview
- Instant HTML/CSS/JavaScript execution
- Live preview in the output panel
- Automatic updates as you type

## Quick Start

### Option 1: GitHub Pages (Recommended)
1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from a branch" and choose `main`
4. Your app will be available at `https://yourusername.github.io/coak`

### Option 2: Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/coak.git
   cd coak
   ```
2. Open `index.html` in your browser
3. Start coding with voice commands!

### Option 3: Netlify Deployment
1. Push your code to GitHub
2. Connect your repository to Netlify
3. Deploy automatically with zero configuration

## Voice Commands Reference

| Command | Action |
|---------|--------|
| "HTML basic" | Inserts complete HTML5 document structure |
| "HTML body" | Adds HTML body template |
| "Paragraph" | Adds a paragraph element |
| "Heading" | Adds a heading element |
| "Button" | Adds a button element |
| "CSS style" | Inserts comprehensive CSS styling |
| "JavaScript function" | Adds JavaScript function template |
| "Clear HTML" | Clears HTML panel |
| "Clear CSS" | Clears CSS panel |
| "Clear JavaScript" | Clears JavaScript panel |
| "Switch to HTML" | Focuses HTML panel |
| "Switch to CSS" | Focuses CSS panel |
| "Switch to JavaScript" | Focuses JavaScript panel |
| "Switch to Output" | Shows output panel |

## Technical Details

### APIs Used
- **Web Speech API**: Built-in browser voice recognition (FREE)

### Browser Compatibility
- ✅ Chrome/Chromium (Full support)
- ✅ Edge (Full support)
- ✅ Safari (Limited support)
- ⚠️ Firefox (Limited support)

### Dependencies
- jQuery 3.4.1 (included)
- jQuery UI (included)
- No external CDN dependencies

## Customization

### Adding New Voice Commands
1. Add your command to the `processVoiceCommand()` function
2. Create a corresponding function to handle the action
3. Update the voice templates modal

### Styling
- Modify `style.css` for visual changes
- All styles use CSS custom properties for easy theming
- Responsive design with mobile-first approach

## Development

### File Structure
```
coak/
├── index.html          # Main application file
├── style.css           # Styling and animations
├── jquery.min.js       # jQuery library
├── README.md           # This file
└── coak/              # Original files (backup)
```

### Key Features Implementation
- **Voice Recognition**: Uses Web Speech API with fallback handling
- **Real-time Preview**: iframe-based sandboxed execution
- **Responsive Design**: CSS Grid and Flexbox layouts
- **Accessibility**: Keyboard shortcuts and screen reader support


## 🔒 Security & Privacy

- **No data collection**: All processing happens locally
- **No external requests**: Works offline after initial load
- **Voice data**: Processed locally by browser, not sent to servers
- **Code execution**: Sandboxed in iframe for security

## Troubleshooting

### Voice Recognition Not Working
1. Ensure you're using HTTPS (required for voice recognition)
2. Check browser permissions for microphone access
3. Try refreshing the page
4. Use Chrome/Edge for best compatibility

### Code Not Updating
1. Check browser console for JavaScript errors
2. Ensure all files are properly loaded
3. Try clearing browser cache

### Styling Issues
1. Check if all CSS files are loaded
2. Verify font imports are working
3. Test in different browsers

## Mobile Support

- Responsive design works on all screen sizes
- Touch-friendly interface
- Voice commands work on mobile browsers
- Optimized for both portrait and landscape orientations

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Web Speech API for voice recognition
- jQuery for DOM manipulation
- Modern CSS techniques for beautiful UI
- Community feedback and suggestions

---

