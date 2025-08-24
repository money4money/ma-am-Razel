# 📚 Room 8 Chronicles - Teacher Portfolio Website

> Modern, interactive portfolio website for Grade 8 Social Studies educator featuring educational resources, ARAL reading program materials, and classroom management tools.

## 🎯 Live Demo
**[View Live Website](https://yourusername.github.io/repository-name)**

## 📖 About
Professional portfolio website for **Ma'am Razel**, a dedicated Social Studies teacher at San Miguel National High School, Leyte. This site serves as a comprehensive resource hub for students, parents, and educational professionals.

### 🏫 Teaching Focus
- **Grade 8 Araling Panlipunan** (Philippine Social Studies)
- **ARAL Reading Program** implementation
- **Class Phoenix** - Section adviser
- **7+ years** of teaching experience

## ✨ Features

### 🎨 **Modern Design**
- Responsive design that works on all devices
- Dark/Light theme toggle with preference saving
- Glassmorphism effects and smooth animations
- Professional gradient color schemes
- Interactive particle effects

### 📚 **Educational Resources**
- **ARAL Reading Program** materials with filtering system
- Interactive resource browser with search functionality
- Downloadable worksheets, passages, and slides
- Teaching guides and assessment rubrics
- Categorized learning materials by difficulty level

### 📅 **Classroom Management**
- Current teaching schedule display
- Class Phoenix timetable
- Professional timeline and achievements
- Contact information and consultation hours

### 🖼️ **Gallery & Media**
- Classroom photo gallery (placeholder ready)
- Student work showcase areas
- Teaching moment documentation

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with CSS Grid/Flexbox
- **Vanilla JavaScript** - Interactive functionality
- **Font Awesome** - Icon library
- **Google Fonts** - Typography (Inter, JetBrains Mono)
- **GitHub Pages** - Hosting platform

### 🎯 **Advanced Features**
- CSS Custom Properties for theming
- LocalStorage for theme persistence
- Intersection Observer for animations
- Debounced search functionality
- Smooth scrolling navigation
- Mobile-first responsive design

## 📁 Project Structure

```
teacher-portfolio/
├── index.html              # Main website file
├── images/                 # Gallery photos (add your images here)
│   ├── classroom-1.jpg     # Classroom environment
│   ├── students-1.jpg      # Student activities
│   └── teaching-1.jpg      # Teaching moments
├── resources/              # Educational materials
│   └── aral/              # ARAL program resources
│       ├── passages/       # Reading passages
│       ├── worksheets/     # Activity worksheets
│       ├── slides/         # Presentation slides
│       └── audio/          # Audio materials
└── README.md              # This file
```

## 🚀 Getting Started

### Prerequisites
- Web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS/JS (for customization)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/teacher-portfolio.git
   cd teacher-portfolio
   ```

2. **Add your images**
   ```bash
   # Create images folder and add your photos
   mkdir images
   # Copy your classroom photos to images/ folder
   ```

3. **Customize content**
   - Edit `index.html` to update personal information
   - Add your educational resources to `resources/aral/`
   - Replace placeholder content with your details

4. **Deploy to GitHub Pages**
   - Go to repository Settings → Pages
   - Select source: Deploy from a branch
   - Choose `main` branch and `/ (root)`
   - Your site will be available at: `https://yourusername.github.io/repository-name`

## 📝 Customization Guide

### 🎨 **Changing Colors**
Edit CSS custom properties in the `:root` section:
```css
:root {
  --accent-primary: #667eea;    /* Main brand color */
  --accent-secondary: #764ba2;  /* Secondary accent */
  --bg-primary: #fafafb;        /* Main background */
}
```

### 📚 **Adding Resources**
Update the `aralResources` array in JavaScript:
```javascript
{
  title: "Your Resource Title",
  category: "Category Name",
  type: "worksheet", // passage, worksheet, slides, audio
  level: "beginner", // beginner, intermediate, advanced
  subject: "Subject Area",
  tags: ["tag1", "tag2"],
  description: "Resource description",
  file: "resources/aral/your-file.pdf"
}
```

### 🖼️ **Adding Images**
Replace gallery placeholders:
```html
<!-- Replace placeholder div with: -->
<img src="images/your-photo.jpg" alt="Description">
```

## 📱 **Responsive Design**

The website is optimized for:
- 📱 **Mobile phones** (320px - 768px)
- 📱 **Tablets** (768px - 1024px)
- 💻 **Desktop** (1024px+)
- 🖥️ **Large screens** (1440px+)

## ♿ **Accessibility Features**

- Semantic HTML structure
- ARIA labels for screen readers
- Keyboard navigation support
- High contrast color ratios
- Focus indicators for interactive elements
- Alternative text for images

## 🌟 **Performance Features**

- Vanilla JavaScript (no heavy frameworks)
- Optimized CSS with minimal HTTP requests
- Lazy loading for smooth animations
- Debounced search for better UX
- Efficient DOM manipulation

## 📊 **Browser Support**

- ✅ Chrome 88+
- ✅ Firefox 85+
- ✅ Safari 14+
- ✅ Edge 88+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 **Contributing**

This is a personal portfolio project, but suggestions are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -m 'Add some improvement'`)
4. Push to branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📄 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 **Contact**

**Ma'am Razel** - Grade 8 Social Studies Teacher  
📧 Email: [razelann.anover@deped.gov.ph](mailto:razelann.anover@deped.gov.ph)  
🔗 LinkedIn: [linkedin.com/in/magicwind888](https://www.linkedin.com/in/magicwind888)  
📷 Instagram: [@magicwind888](https://www.instagram.com/magicwind888)

**School:** San Miguel National High School, Leyte, Philippines

---

## 🏆 **Achievements & Recognition**

- 7+ years dedicated teaching experience
- ARAL Reading Program implementation
- Student mentorship and guidance
- Classroom technology integration
- Professional development participant

---

## 💡 **Future Enhancements**

- [ ] Student progress tracking system
- [ ] Online quiz and assessment tools
- [ ] Parent-teacher communication portal
- [ ] Multi-language support (Filipino/English)
- [ ] Advanced resource categorization
- [ ] Student portfolio showcase

---

**Made with ❤️ for education** | **Empowering students through technology**
