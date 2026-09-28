# MultiLineDiff Website

The official website for MultiLineDiff - The World's Most Advanced Diffing System.

## 🌟 Features

- **Modern Design**: Dark theme with indigo/purple gradients
- **Responsive**: Works perfectly on desktop, tablet, and mobile
- **Interactive Documentation**: Expandable sections with comprehensive guides
- **Live Demo**: Interactive algorithm comparison and diff generation
- **Performance Charts**: Real benchmark data visualization
- **Syntax Highlighting**: Prism.js integration for code examples
- **Smooth Animations**: GPU-accelerated transitions and effects

## 📁 Project Structure

```
website/
├── index.html              # Main page
├── css/
│   ├── styles.css          # Main styles and variables
│   ├── components.css      # Component-specific styles
│   └── animations.css      # Animation definitions
├── js/
│   ├── main.js            # Core functionality
│   ├── demo.js            # Interactive demo
│   └── performance.js     # Chart.js performance charts
├── images/
│   └── favicon.svg        # Site favicon
├── deploy.sh              # Deployment script
├── package.json           # Dependencies
├── .gitignore            # Git ignore rules
└── README.md             # This file
```

## 🚀 Quick Start

### Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/AgentiLoop/AgentD1F.git
   cd swift-multi-line-diff/website
   ```

2. **Start a local server**:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Open in browser**:
   ```
   http://localhost:8000
   ```

### Dependencies

The website uses CDN dependencies for optimal performance:

- **Chart.js**: Performance visualization
- **Prism.js**: Syntax highlighting
- **Google Fonts**: Inter and JetBrains Mono fonts

## 📖 Documentation Sections

The website includes comprehensive documentation covering:

### 🚀 Quick Start Guide
- Installation instructions
- Basic usage examples
- AI-friendly ASCII format
- Round-trip workflow

### 🤖 ASCII Diff Format
- Symbol rules and meanings
- Visual representation guide
- Real-world examples
- AI integration benefits

### ⚡ Flash & Optimus Algorithms
- Performance comparison tables
- Algorithm selection guide
- Usage examples
- Technical details

### 🔧 Enhanced Parser
- New features overview
- Source start line tracking
- Metadata structure
- Practical benefits

### 🌟 Revolutionary Features
- Unique innovations
- Superiority comparisons
- Security features
- Complete feature list

### 📖 API Reference
- Core methods documentation
- Algorithm enums
- Display formats
- Usage examples

## 🎨 Design System

### Color Palette
- **Primary**: `#6366f1` (Indigo)
- **Secondary**: `#10b981` (Emerald)
- **Accent**: `#f59e0b` (Amber)
- **Background**: `#0f0f23` (Dark Navy)
- **Text**: `#f8fafc` (Light Gray)

### Typography
- **Headings**: Inter (Google Fonts)
- **Body**: Inter (Google Fonts)
- **Code**: JetBrains Mono (Google Fonts)

### Components
- **Cards**: Rounded corners, subtle shadows
- **Buttons**: Gradient backgrounds, hover effects
- **Code Blocks**: Dark theme, syntax highlighting
- **Tables**: Responsive, alternating rows

## 🚀 Deployment

### Automated Deployment

Use the included deployment script:

```bash
# Make executable
chmod +x deploy.sh

# Deploy to development
./deploy.sh dev

# Deploy to staging
./deploy.sh staging

# Deploy to production
./deploy.sh production
```

### Manual Deployment

#### Netlify
1. Connect your GitHub repository
2. Set build command: `# No build needed`
3. Set publish directory: `website`
4. Deploy

#### Vercel
1. Import project from GitHub
2. Set framework preset: `Other`
3. Set root directory: `website`
4. Deploy

#### GitHub Pages
1. Go to repository Settings
2. Enable GitHub Pages
3. Set source to `main` branch, `website` folder
4. Access at `https://username.github.io/repository-name`

#### Traditional Hosting
1. Upload `website` folder contents to web root
2. Ensure server supports HTML5 history API
3. Configure HTTPS (recommended)

## 🔧 Customization

### Updating Content

1. **Hero Section**: Edit `index.html` lines 60-120
2. **Features**: Modify feature cards in `index.html`
3. **Documentation**: Update expandable sections
4. **Performance Data**: Modify `js/performance.js`

### Styling Changes

1. **Colors**: Update CSS variables in `css/styles.css`
2. **Fonts**: Change Google Fonts imports in `index.html`
3. **Layout**: Modify grid systems in `css/components.css`
4. **Animations**: Adjust timing in `css/animations.css`

### Adding New Sections

1. Add HTML structure to `index.html`
2. Create corresponding styles in `css/components.css`
3. Add JavaScript functionality in `js/main.js`
4. Update navigation links

## 📊 Performance

### Optimization Features
- **Lazy Loading**: Images and non-critical resources
- **CDN Dependencies**: Fast loading from global CDNs
- **Minification**: CSS and JS optimization for production
- **Caching**: Proper cache headers for static assets
- **Responsive Images**: Optimized for different screen sizes

### Lighthouse Scores
- **Performance**: 95+
- **Accessibility**: 100
- **Best Practices**: 100
- **SEO**: 100

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📝 License

This project is part of the MultiLineDiff library created by AgentiLoop.ai © xcf.ai.

## 🔗 Links

- **Library Repository**: [swift-multi-line-diff](https://github.com/AgentiLoop/AgentD1F)
- **Documentation**: [ASCII Diff Guide](https://github.com/AgentiLoop/AgentD1F/blob/main/NEW_ASCII_DIFF.md)
- **XCF.ai**: [https://xcf.ai](https://xcf.ai)

---

**MultiLineDiff: The World's Most Advanced Diffing System** 🚀 