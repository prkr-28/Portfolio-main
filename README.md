# Portfolio Website 🚀

A modern, interactive full-stack developer portfolio website built with React, featuring smooth animations, responsive design, and advanced interactivity. Showcases projects, skills, and provides easy contact options.

## ✨ Features

- **Dynamic Hero Section** - Animated headline with typing effect and tech stack ticker
- **Smooth Scrolling** - Lenis-powered smooth scroll experience
- **Advanced Animations** - GSAP animations with scroll triggers for engaging transitions
- **Skills Showcase** - Categorized skills with animated progress bars
- **GitHub Integration** - Real-time GitHub contribution calendar
- **Interactive Terminal** - Custom terminal component for additional information
- **Project Portfolio** - Showcase of featured full-stack projects with live links
- **Contact Form** - Email integration with EmailJS for direct communication
- **Location Map** - MapLibre integration showing location
- **Dark Theme** - Modern dark UI with green accent colors
- **Fully Responsive** - Mobile-first design that works on all devices
- **Social Links** - Connected social media profiles

## 🛠️ Tech Stack

### Frontend

- **React 19.2** - UI library
- **Vite** - Build tool and dev server
- **Tailwind CSS 4** - Utility-first CSS framework
- **Shadcn UI** - High-quality component library
- **GSAP** - Professional-grade animation library
- **Lenis** - Smooth scrolling library
- **Framer Motion** - Animation for React components

### Animations & Effects

- **GSAP SplitText** - Text animation plugin
- **ScrollTrigger** - Scroll-based animations
- **React Infinite Ticker** - Scrolling ticker component
- **React GitHub Calendar** - GitHub contributions visualization

### Features & Utilities

- **EmailJS** - Email sending from client-side
- **MapLibre GL** - Interactive maps
- **React Icons** - Icon library
- **Lucide React** - Beautiful icons
- **JavaScript Terminal** - Custom terminal UI
- **Axios** - HTTP client (for projects)
- **Redux Toolkit** - State management (for projects)

### Development Tools

- **Babel** - JavaScript transpiler
- **ESLint** - Code quality tool
- **TypeScript** - Type safety

## 📦 Installation

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn package manager

### Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/prkr-28/Portfolio-main.git
   cd Portfolio-main
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Configure environment variables**

   Create a `.env` file in the root directory with:

   ```env
   VITE_EMAILJS_SERVICE_ID=your_emailjs_service_id
   VITE_EMAILJS_TEMPLATE_ID=your_emailjs_template_id
   VITE_EMAILJS_PUBLIC_KEY=your_emailjs_public_key
   ```

4. **Start the development server**

   ```bash
   npm run dev
   ```

   The application will be available at `http://localhost:5173`

## 🚀 Build & Deployment

### Build for production

```bash
npm run build
```

This creates an optimized build in the `dist` directory.

### Preview the build locally

```bash
npm run preview
```

### Deploy

The portfolio can be deployed to:

- **Vercel** - Zero-config deployment
- **Netlify** - Git-connected deployment
- **GitHub Pages** - Free hosting
- **Any static host** - Just serve the `dist` directory

## 📁 Project Structure

```
Portfolio/
├── src/
│   ├── components/
│   │   ├── Navbar.jsx          # Navigation component
│   │   ├── Footer.jsx          # Footer component
│   │   ├── GithubCalendar.jsx  # GitHub contributions
│   │   ├── CustomTerminal.jsx  # Interactive terminal
│   │   └── ui/
│   │       ├── button.jsx      # Custom button
│   │       └── map.jsx         # Map component
│   ├── pages/
│   │   ├── Home.jsx            # Hero section
│   │   ├── About.jsx           # About & skills
│   │   ├── Project.jsx         # Projects showcase
│   │   └── Contact.jsx         # Contact form
│   ├── constant/
│   │   ├── projectData.js      # Featured projects
│   │   └── ContactData.jsx     # Contact information
│   ├── assets/
│   │   └── images/             # Images and icons
│   ├── lib/
│   │   └── utils.js            # Utility functions
│   ├── App.jsx                 # Main component
│   ├── App.css                 # Global styles
│   └── main.jsx                # Entry point
├── public/
│   ├── favicon/                # Favicon files
│   └── themes/                 # Theme configurations
├── index.html                  # HTML template
├── package.json                # Dependencies
├── vite.config.js              # Vite configuration
├── eslint.config.js            # ESLint rules
└── components.json             # Component library config
```

## 🎨 Sections Overview

### 1. **Home** (Hero Section)

- Animated headline with gradient text
- Tech stack ticker
- Call-to-action buttons
- Status badge (Open to Work)
- Terminal-style prompt

### 2. **About** (Skills & Info)

- Professional card with avatar and bio
- Interactive skill bars (Frontend, Backend, Frameworks, Tools)
- JSON-style information panel
- Custom terminal with commands (`help`, `hobbies`, `certificates`)
- GitHub contribution calendar
- Feature cards (Frontend Dev, Backend Dev, Database, UI/UX)

### 3. **Projects** (Portfolio)

Features 6 showcase projects:

- **CivicPulse** - AI-powered community reporting (MERN + Gemini API)
- **Quizly** - Quiz & flashcard platform (Next.js + Grok AI)
- **ResumeXpert** - Resume builder (React + HTML2Canvas)
- **Vybe** - Social media platform (MERN + Socket.io)
- **TastyBytes** - Food delivery app (React + Swiggy API)
- **LinkedIn Clone** - Social network (MERN + Socket.io)

Each project card includes:

- Project image/screenshot
- Description
- Technology stack
- Live demo link
- GitHub repository link
- Project type badge
- Timestamp

### 4. **Contact** (Get in Touch)

- Contact information cards (Email, Phone, Location, LinkedIn, GitHub)
- Interactive contact form
- Email validation
- Loading states
- Success toast notifications
- Location map (MapLibre)
- Response time indicator

## 🚦 Development

### Available Scripts

```bash
# Development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview

# Lint code
npm run lint
```

### Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints:

- **Mobile**: < 640px (sm)
- **Tablet**: 640px - 1024px (md, lg)
- **Desktop**: > 1024px (xl, 2xl)

All components adapt gracefully to different screen sizes.

## 🎯 Performance Optimizations

- **Image Lazy Loading** - Images load on demand
- **Code Splitting** - Vite handles automatic code splitting
- **CSS Optimization** - Tailwind purges unused styles
- **Animation Performance** - GSAP optimized for 60fps
- **Smooth Scrolling** - Lenis for better scroll performance

## 🔐 Security

- **Environment Variables** - Sensitive keys stored in `.env`
- **Email Validation** - Client-side form validation
- **CORS Handling** - EmailJS handles cross-origin requests safely
- **Input Sanitization** - Form inputs are trimmed and validated

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest features
- Submit pull requests

## 📞 Contact

- **Email**: [priyanshu402muz@gmail.com]
- **GitHub**: [@prkr-28](https://github.com/prkr-28)
- **LinkedIn**: [@prkr28](https://www.linkedin.com/in/prkr28/)
- **Twitter**: [@prkr](https://x.com/prkr)
- **Instagram**: [@prkr](https://www.instagram.com/prkr/)

## 🙏 Acknowledgments

- Built with [React](https://react.dev/)
- Styled with [Tailwind CSS](https://tailwindcss.com/)
- Animated with [GSAP](https://greensock.com/gsap/)
- Components from [Shadcn UI](https://ui.shadcn.com/)
- Smooth scrolling with [Lenis](https://lenis.darkroom.engineering/)
- Deployed with [Vercel](https://vercel.com/)

---

**Made with ❤️ by Priyanshu**
