# Super Design

A cutting-edge creative design agency website built with Next.js, featuring modern animations, a vibrant orange and black color scheme, and an impressive component library.

## 🎨 Overview

Super Design is a modern, visually striking website showcasing AI-powered product design capabilities. The site features bold typography, smooth animations powered by Framer Motion, and a comprehensive UI component library built on shadcn/ui.

## ✨ Features

- **Modern Design**: Eye-catching orange (#FF4D00) and black color scheme
- **Smooth Animations**: Powered by Framer Motion for engaging user interactions
- **Responsive Layout**: Fully responsive design that works on all devices
- **Component Library**: Extensive collection of shadcn/ui components
- **TypeScript**: Full TypeScript support for type safety
- **Tailwind CSS**: Utility-first CSS framework for rapid styling
- **Dark/Light Theme**: Theme support with next-themes

## 🚀 Tech Stack

- **Framework**: Next.js 16.0.10
- **Language**: TypeScript
- **Styling**: Tailwind CSS 4.1.9
- **Animations**: Framer Motion 12.26.2
- **UI Components**: shadcn/ui + Radix UI
- **Icons**: Lucide React
- **Forms**: React Hook Form + Zod validation
- **Analytics**: Vercel Analytics

## 📦 Components

### Core Components

- **Navbar**: Sticky navigation with smooth scroll
- **Hero**: Bold typography hero section with animated elements
- **MarqueeSection**: Scrolling marquee for dynamic content
- **Services**: Service showcase with interactive cards
- **Footer**: Comprehensive footer with links and information

### UI Components Library

The project includes 50+ pre-built UI components:

- Accordion, Alert, Avatar, Badge, Button, Card
- Carousel, Chart, Checkbox, Dialog, Dropdown
- Form components, Input, Navigation, Pagination
- Table, Tabs, Tooltip, and many more

## 🛠️ Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/senapati484/super-design.git
   cd super-design
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Set up environment variables**

   ```bash
   cp .env.example .env.local
   ```

   Add your environment variables as needed.

4. **Run the development server**

   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📁 Project Structure

```
super-design/
├── app/                    # Next.js app directory
│   ├── page.tsx           # Main page component
│   └── layout.tsx         # Root layout
├── components/            # React components
│   ├── ui/               # shadcn/ui components (50+)
│   ├── hero.tsx          # Hero section
│   ├── navbar.tsx        # Navigation
│   ├── services.tsx      # Services section
│   └── footer.tsx        # Footer
├── lib/                  # Utility functions
├── hooks/                # Custom React hooks
├── styles/               # Global styles
└── public/               # Static assets
```

## 🎯 Key Features

### Hero Section

- Bold, oversized typography with custom font styling
- Animated scroll indicators
- Responsive design with mobile-first approach
- Eye-catching orange background with black text

### Animations

- Smooth scroll-based animations
- Hover effects and micro-interactions
- Component entrance animations
- Loading states and transitions

### Responsive Design

- Mobile-first approach
- Breakpoint-specific layouts
- Touch-friendly interactions
- Optimized performance across devices

## 🧪 Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

### Component Development

The project uses a component-based architecture with:

- **TypeScript** for type safety
- **Tailwind CSS** for styling
- **Framer Motion** for animations
- **shadcn/ui** for consistent UI components

### Adding New Components

1. Create component in `components/` directory
2. Follow TypeScript conventions
3. Use Tailwind for styling
4. Add animations with Framer Motion if needed
5. Export and import in pages as needed

## 🎨 Customization

### Color Scheme

The primary color scheme uses:

- Primary: `#FF4D00` (Orange)
- Secondary: `#000000` (Black)
- Text: Black on orange, white on dark backgrounds

### Typography

- **Headings**: Custom serif fonts with bold weights
- **Body**: System fonts for optimal performance
- **Code**: Monospace fonts for technical content

### Animations

Customize animations by modifying Framer Motion variants in component files.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Android Chrome)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Show Your Support

Give a ⭐️ if this project helped you!

## 📞 Contact

- **GitHub**: [@senapati484](https://github.com/senapati484)
- **Project Link**: [https://github.com/senapati484/super-design](https://github.com/senapati484/super-design)

---

Built with ❤️ using Next.js and modern web technologies
