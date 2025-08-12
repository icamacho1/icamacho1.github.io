# Iker Camacho - Portfolio Website

A modern, responsive portfolio website built with **Astro** and **React**, featuring the beautiful **Catppuccin** color scheme.

## 🚀 Features

- **Modern Design**: Beautiful Catppuccin Mocha color scheme
- **Responsive**: Works perfectly on all devices
- **Fast Performance**: Built with Astro for optimal loading speeds
- **Interactive**: Smooth animations with Framer Motion
- **Professional**: Clean, modern layout showcasing skills and experience

## 🛠️ Tech Stack

- **Framework**: Astro
- **UI Library**: React
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Icons**: React Icons
- **Deployment**: GitHub Pages

## 🎨 Design Features

- **Catppuccin Theme**: Warm, eye-friendly colors
- **Gradient Text**: Beautiful gradient effects for headings
- **Card Layout**: Modern card-based design
- **Smooth Animations**: Staggered animations and hover effects
- **Custom Scrollbar**: Themed scrollbar matching the design

## 📁 Project Structure

```
src/
├── components/          # React components
│   ├── Navbar.tsx      # Navigation bar
│   ├── Hero.tsx        # Hero section
│   ├── Skills.tsx      # Skills & technologies
│   ├── Experience.tsx  # Work experience & education
│   └── Footer.tsx      # Footer with links
├── layouts/            # Astro layouts
│   └── Layout.astro    # Main layout component
├── pages/              # Astro pages
│   └── index.astro     # Home page
└── styles/             # Global styles
    └── global.css      # Catppuccin theme & custom styles
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd astro-portfolio
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and visit `http://localhost:4321`

### Building for Production

```bash
npm run build
```

The built files will be in the `dist/` directory.

## 🎯 Key Sections

### Hero Section
- Animated introduction with your name and title
- Call-to-action buttons for GitHub and LinkedIn
- Smooth scroll indicator

### Skills & Technologies
- Organized by categories (Languages, Backend, Frontend, Cloud)
- Highlighted current technologies
- Interactive skill tags with hover effects

### Experience
- Professional work experience
- Open source contributions
- Education and certifications

### Footer
- Contact information
- Quick navigation links
- Social media links

## 🎨 Customization

### Colors
The site uses the Catppuccin Mocha color palette:
- Background: `#1e1e2e` to `#181825` gradient
- Text: `#cdd6f4` (soft white)
- Accents: `#cba6f7` (lavender), `#b4befe` (blue)
- Highlights: `#f5c2e7` (pink), `#a6e3a1` (green)

### Content
Update the content in the respective component files:
- `Skills.tsx`: Modify the skills array
- `Experience.tsx`: Update the LISTS array
- `Navbar.tsx`: Change contact information
- `Hero.tsx`: Update personal description

## 📦 Deployment

### GitHub Pages

1. Push your code to GitHub
2. Create a new repository named `astro-portfolio`
3. The site will be available at `https://icamacho1.github.io/astro-portfolio`

### Other Platforms

The site can be deployed to any static hosting platform:
- Netlify
- Vercel
- Cloudflare Pages
- AWS S3

## 🔧 Development

### Adding New Components

1. Create a new `.tsx` file in `src/components/`
2. Import and use it in `src/pages/index.astro`
3. Add `client:load` directive for interactive components

### Styling

- Use Tailwind CSS classes for styling
- Custom styles are in `src/styles/global.css`
- Follow the Catppuccin color scheme for consistency

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

Built with ❤️ using Astro and the Catppuccin theme
