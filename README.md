# Image Slider

A responsive and interactive image slider built with vanilla HTML, CSS, and JavaScript. Features smooth transitions, navigation controls, and elegant animations.

## 🌟 Features

- **Smooth Transitions**: Elegant slide animations with CSS transitions
- **Interactive Navigation**: Previous/Next buttons for easy navigation
- **Responsive Design**: Adapts to different screen sizes
- **Multiple Images**: Supports 7 high-quality images
- **Modern UI**: Clean design with shadows and rounded corners
- **Animated Text**: Slide content appears with smooth animations
- **Hover Effects**: Interactive button hover states

## 🚀 Demo

The slider displays images in a carousel format with:
- Large main display image
- Preview thumbnails on the right
- Navigation controls at the bottom
- Animated slide content with titles and descriptions

## 📁 Project Structure

```
Image Slider/
├── index.html          # Main HTML structure
├── style.css           # Styling and animations
├── main.js            # JavaScript functionality
├── README.md          # Project documentation
└── images/            # Image assets
    ├── 1.jpg
    ├── 2.jpg
    ├── 3.jpg
    ├── 4.jpg
    ├── 5.jpg
    ├── 6.jpg
    └── 7.jpg
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling, animations, and transitions
- **JavaScript**: DOM manipulation and event handling
- **Google Fonts**: Montserrat font family
- **Iconscout**: Unicons for navigation arrows

## 🎨 Design Features

- **Typography**: Montserrat font for modern appearance
- **Color Scheme**: Dark theme with blue accent colors (#2b335a, #5867a7)
- **Animations**: CSS keyframe animations for content reveal
- **Shadows**: Depth with box-shadow effects
- **Transitions**: Smooth 1s ease-in-out transitions

## 💻 Installation & Usage

1. **Clone the repository**:
   ```bash
   git clone <your-repo-url>
   cd "Image Slider"
   ```

2. **Open in browser**:
   - Simply open `index.html` in any modern web browser
   - Or use a local server for better performance

3. **Navigate through slides**:
   - Click the left arrow (←) to go to the previous slide
   - Click the right arrow (→) to go to the next slide

## 🔧 How It Works

### JavaScript Logic
- **Next Button**: Moves the first slide to the end of the list
- **Previous Button**: Moves the last slide to the beginning of the list
- **DOM Manipulation**: Uses `appendChild()` and `prepend()` for smooth reordering

### CSS Layout
- **Positioning**: Absolute positioning for precise slide placement
- **Transforms**: 3D transforms for smooth animations
- **Nth-child Selectors**: Different styles for each slide position
- **Responsive Units**: Uses rem units for scalability

## 🎯 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🚧 Future Enhancements

- [ ] Auto-play functionality
- [ ] Touch/swipe gesture support for mobile
- [ ] Keyboard navigation (arrow keys)
- [ ] Pagination dots indicator
- [ ] Full-screen mode
- [ ] Image lazy loading
- [ ] Responsive breakpoints for mobile devices

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Selim** - Frontend Developer

---

⭐ Star this repository if you found it helpful!
