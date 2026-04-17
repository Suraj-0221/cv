# Suraj's Portfolio - Studio Ghibli Edition

A beautifully designed, modern CV/portfolio website inspired by the aesthetic of Studio Ghibli films. Built with Tailwind CSS and crafted for a premium, immersive user experience.

## 🎨 Design Philosophy

This portfolio follows **"The Living Sketchbook"** design system—a nostalgic, pastoral aesthetic that feels more like a premium art gallery than a generic template. The design breaks traditional web constraints through:

- **Intentional Asymmetry**: Content drifts organically across the screen
- **Tonal Transitions**: Boundaries defined by color shifts, not harsh lines
- **Organic Typography**: Newsreader serif pairs with Plus Jakarta Sans for editorial elegance
- **Glassmorphism**: Soft, blurred overlays create depth without visual harshness
- **Gentle Animations**: Breathing effects, soft scaling, and smooth transitions

## 📁 Project Structure

```
cv-main/
├── index.html              # Main portfolio page (Hero + About + Skills)
├── Contact-me.html         # Contact section with form
├── Images/                 # Profile images
├── stitch_serene_path_portfolio/  # Design reference files
│   ├── arrival_hero/
│   ├── forest_of_abilities_skills/
│   ├── the_cottage_about/
│   ├── the_workshop_projects/
│   └── wind_swept_canvas/
└── README.md              # This file
```

## 🎯 Pages

### **index.html - Main Portfolio**
- **Hero Section**: Full-screen introduction with profile image
- **About Section (The Cottage)**: Education timeline with breathing animations
- **Skills Section (The Forest)**: Visual skill bars with gradients
- **Navigation**: Smooth scrolling between sections

### **Contact-me.html - Contact Page**
- Contact info cards (phone, email, location)
- Modern contact form with email submission
- Consistent design with main portfolio

## 🎨 Design System

### Colors
```
Primary:      #406845 (Forest Green)
Primary Dim:  #345c3a (Dark Green)
Primary Container: #c0eec1 (Light Green)
Secondary:    #366671 (Sky Blue)
Tertiary:     #6b5f1d (Warm Gold)
Surface:      #fef9f0 (Warm Cream)
```

### Typography
- **Headlines**: Newsreader (Serif) - Editorial, elegant
- **Body**: Plus Jakarta Sans (Sans-serif) - Clean, readable
- **Material Symbols**: Google's icon library

### Key Rules
- ✅ No 1px solid borders (use tonal transitions)
- ✅ Soft ambient shadows (40px+ blur, 4-8% opacity)
- ✅ Minimum sm (0.5rem) rounded corners
- ✅ Generous whitespace for gallery aesthetic
- ✅ Slow, drifting animations (600ms+)

## 🚀 Getting Started

### View Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/Suraj-0221/cv.git
   cd cv-main
   ```

2. Open in browser:
   ```bash
   # On Windows
   start index.html
   
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   ```

### Or Use a Local Server
```bash
# Python 3
python -m http.server 8000

# Then visit http://localhost:8000
```

## 🎭 Animations

- **Breathing**: Slow Y-axis translation (4-6px over 4s) on timeline items
- **Hover Scale**: 1.02 scale on interactive elements
- **Fade & Slide**: 600ms+ entrance animations
- **Blur Transition**: Focus state changes use backdrop blur instead of harsh colors

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints for:
- **Mobile**: Full-width stacked layout
- **Tablet** (md): Side navigation + main content
- **Desktop** (lg): Optimized multi-column layouts

## ✨ Features

- 🎨 Modern, premium design system
- 📱 Fully responsive and mobile-friendly
- ⚡ Built with Tailwind CSS (no build step required)
- 🎭 Smooth animations and transitions
- 💌 Working contact form
- ♿ Accessible markup and semantics
- 🎯 Fast loading with CDN resources

## 🛠️ Technologies

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first styling with custom theme
- **Google Fonts**: Newsreader & Plus Jakarta Sans
- **Material Symbols**: Icon library
- **Vanilla JavaScript**: Minimal, for future enhancements

## 📝 Content Sections

### About Me
- Education timeline (10th, 12th, WBJEE, B.Tech)
- Personal passions (Reading, Writing, Creative Thinking)
- Student at GCECT, 3rd year Computer Science

### Skills
- **Technical**: Python, Web Development
- **Creative**: Writing, Photography
- Visual progress bars with color gradients

### Contact
- Direct contact info
- Email contact form
- Links to social profiles (ready for expansion)

## 🔧 Customization

### Update Your Information
Edit the content in `index.html` and `Contact-me.html`:
- Replace "Suraj" with your name
- Update the tagline and descriptions
- Modify skills and education details
- Add/remove sections as needed

### Modify Colors
Edit the Tailwind config in the `<script>` section:
```javascript
colors: {
  "primary": "#406845",
  // Update these hex values
}
```

### Add New Sections
Use the existing section structure:
```html
<section id="section-name" class="w-full py-20 md:py-32 px-6 md:px-12 relative">
  <div class="max-w-5xl mx-auto">
    <!-- Your content -->
  </div>
</section>
```

## 📊 Performance

- Lightweight: No build process required
- CDN-delivered resources (Tailwind, Fonts, Icons)
- Optimized image sizes
- Minimal JavaScript

## 🎓 Learning Resources

- [Tailwind CSS Documentation](https://tailwindcss.com)
- [Material Symbols Guide](https://fonts.google.com/metadata/icons)
- [Studio Ghibli Inspiration](https://www.studio-ghibli.com)

## 📄 License

This portfolio is open source and available for personal use and modification.

## 🤝 Contributing

Feel free to fork, modify, and create your own version! This design system is flexible and can be adapted to any professional field.

## 📧 Contact

- **Email**: surajjaman0221@gmail.com
- **Phone**: 4258693442
- **Portfolio**: https://suraj-0221.github.io/cv

---

**Made with ❤️ and inspired by the serene aesthetics of Studio Ghibli films.**

*"The most intelligent thing we can do with our lives is to learn." - The Wind Rises*