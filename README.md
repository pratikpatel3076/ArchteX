# 🏗️ ArchteX - AI-Powered Architecture & Interior Design Platform

## 📋 Project Description

**ArchteX** is a modern, AI-powered architecture and interior design platform that revolutionizes the way spaces are visualized, designed, and experienced. The platform addresses the limitations of conventional design methods by providing real-time visualization, immersive AR/VR experiences, and AI-powered design insights that make the design process more accessible, efficient, and collaborative.

Built as a static website optimized for GitHub Pages, ArchteX showcases cutting-edge design services including 3D house designs, interior design solutions for homes, offices, and restaurants, and architectural planning. The platform leverages augmented reality and virtual reality technologies to provide clients with immediate visual feedback, immersive walkthroughs, and realistic design experiences that bridge the gap between conceptual plans and finished products.

### Key Objectives
- **Accessibility**: Make professional architecture and design services accessible to everyone
- **Visualization**: Provide real-time AR/VR visualization for immediate design feedback
- **Innovation**: Leverage AI-powered insights for automated design adjustments
- **Collaboration**: Enable seamless team collaboration and client feedback
- **Efficiency**: Reduce design time and costs through modern technology

---

## 🚀 Quick Start

### Prerequisites
- Node.js 14+ (Download from [nodejs.org](https://nodejs.org/en/download/))
- npm or yarn package manager
- Modern web browser

### Installation & Running

**Option 1: Using npm**
```bash
# Install dependencies
npm install

# Start development server
npm start
```

**Option 2: Using yarn**
```bash
# Install dependencies
yarn install

# Start development server
yarn start
```

The project will be available at `http://localhost:1234` (default Parcel port).

### Building for Production

```bash
# Build for production
npm run build

# Output will be in the ./build directory
```

---

## ✨ Features

### 🎨 Design Services
- **3D House Designs**: Comprehensive 3D visualization of residential spaces
- **Interior Design**: Home, office, and restaurant interior design solutions
- **Architecture**: Full architectural planning and design services
- **Custom Solutions**: Tailored design solutions for various spaces

### 🚀 Advanced Technology
- **Real-Time Visualization**: Immediate AR feedback on design changes
- **Immersive Walkthroughs**: Detailed VR tours for realistic design experience
- **AI-Powered Insights**: Automated design adjustments and recommendations
- **Collaborative Tools**: Seamless integration for team collaboration and client feedback

### 💡 Key Advantages
- **Cost-Effective**: Reduces expensive traditional design methods
- **Time-Efficient**: Faster design iterations and modifications
- **Visual Clarity**: Easy visualization of finished products from plans
- **Client-Friendly**: Intuitive interface for non-technical users

---

## 🏗️ Technology Stack

### Frontend
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with responsive design
- **Parcel**: Fast, zero-configuration web application bundler
- **Google Fonts**: Work Sans, PT Serif, Questrial, Inter

### Development Tools
- **Parcel 2.7.0**: Build tool and development server
- **Node.js**: JavaScript runtime environment
- **npm/yarn**: Package management

### Deployment
- **GitHub Pages**: Static site hosting
- **Responsive Design**: Mobile-first approach

---

## 📁 Project Structure

```
ArchteX/
├── index.html              # Main HTML file
├── index.css               # Main stylesheet
├── global.css              # Global styles and resets
├── package.json            # Project dependencies and scripts
├── README.md               # Project documentation
├── LICENSE                 # ISC License
├── .gitignore              # Git ignore rules
├── public/                 # Public assets folder
│   ├── *.svg               # SVG graphics and icons
│   ├── *.png               # Image assets (@2x for retina displays)
│   └── *.mp4               # Video assets
├── dist/                   # Production build output (generated)
└── node_modules/           # Dependencies (generated)
```

---

## 🎯 Project Sections

### Home Page Features
1. **Hero Section**: Introduction to ArchteX platform
2. **Why Us Section**: Benefits and advantages over conventional methods
3. **Featured Projects**: Showcase of completed design projects
4. **What You Get**: Detailed feature list with AR/VR capabilities
5. **Service Categories**: 
   - Home Interior
   - Office Interior
   - Restaurant Interior
   - Architecture
   - 3D Designs
6. **Design Your Space**: Main call-to-action section
7. **AI-Powered Architecture**: Technology showcase

---

## 🔧 Configuration

### Development Server
The project uses Parcel's built-in development server with hot module replacement:
- Default port: `1234`
- Auto-reload on file changes
- Source maps enabled

### Build Configuration
Production builds are optimized with:
- Minified CSS and HTML
- Optimized images
- Tree-shaking for unused code
- Output directory: `./build`

---

## 📦 Available Scripts

```bash
# Start development server
npm start
# or
yarn start

# Build for production
npm run build
# or
yarn build
```

---

## 🌐 GitHub Pages Deployment

### Automatic Deployment
Since this repository is named `archtex.github.io`, GitHub Pages will automatically:
- Serve the site at `https://archtex.github.io`
- Deploy from the `main` branch (or `gh-pages` branch)
- Update automatically on every push

### Manual Deployment Steps
1. Build the project: `npm run build`
2. Commit and push the `build` directory to `gh-pages` branch, OR
3. Configure GitHub Pages to serve from the `build` directory

### Recommended Setup
1. Build the project locally
2. Copy build files to root directory (or configure GitHub Pages to use `/build`)
3. Commit and push to main branch
4. Enable GitHub Pages in repository settings

---

## 🎨 Design Features

### Responsive Design
- Mobile-first approach
- Optimized for all screen sizes
- Touch-friendly interface
- Retina-ready images (@2x assets)

### Visual Elements
- High-quality project images
- SVG icons and graphics
- Video demonstrations
- Interactive UI components

---

## 🔮 Future Enhancements

- **Interactive 3D Viewer**: Embedded 3D model viewer
- **AR Integration**: Live AR preview functionality
- **VR Experience**: Full VR walkthrough capability
- **Client Portal**: Login system for project management
- **Design Tool**: In-browser design customization
- **Project Gallery**: Expandable project showcase
- **Contact Form**: Integrated contact and inquiry system
- **Blog Section**: Design tips and industry insights

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Make your changes
4. Test locally with `npm start`
5. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
6. Push to the branch (`git push origin feature/AmazingFeature`)
7. Open a Pull Request

### Development Guidelines
- Follow existing code style and structure
- Ensure responsive design compatibility
- Test on multiple browsers
- Optimize images before committing
- Write clear commit messages

---

## 📝 License

This project is licensed under the ISC License - see the package.json file for details.

---

## 📞 Support & Contact

For questions, inquiries, or collaboration opportunities:
- Visit the live site: [archtex.github.io](https://archtex.github.io)
- Open an issue on GitHub for bug reports or feature requests

---

## 🙏 Acknowledgments

- **Parcel**: For the excellent build tool
- **Google Fonts**: For beautiful typography
- **GitHub Pages**: For free static site hosting
- Design inspiration from modern architecture and interior design trends

---

## 📊 Project Status

✅ **Active Development** - The project is actively maintained and updated.

**Current Version**: 1.0.0

## 🔄 Recent Updates

- Organized all assets into `public/` folder for better project structure
- Fixed aspect ratio and scaling for optimal display at 100% browser zoom
- Enhanced logo styling with improved typography
- Updated contact information
- Optimized file paths and references

---

**Built with ❤️ for architects, designers, and dreamers**