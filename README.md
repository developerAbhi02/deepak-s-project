# Moon Creation Films - Professional Website

A modern, responsive website for Moon Creation Films Agency built with Next.js, TypeScript, and Tailwind CSS.

## 🎬 About

Moon Creation Films is a professional film direction and video production agency specializing in:
- Film Direction & Video Production
- Creative Direction
- Pre-Wedding & Event Shoots
- Concept Development & Branding
- Website Design & Digital Marketing
- Social Media Marketing & Google Ads/SEO

## ✨ Features

### 🎯 Core Features
- **Responsive Design**: Mobile-first approach with seamless experience across all devices
- **Modern UI/UX**: Beautiful animations and smooth transitions using Framer Motion
- **SEO Optimized**: Meta tags, Open Graph, and structured data for better search visibility
- **Fast Performance**: Optimized images, lazy loading, and efficient code structure
- **Contact Integration**: WhatsApp integration, contact forms, and click-to-call functionality

### 📱 Sections
1. **Header**: Navigation with smooth scrolling and mobile menu
2. **Hero**: Compelling tagline "From Vision to Viral" with key statistics
3. **Services**: Detailed showcase of all offered services
4. **About**: Company story, vision, and team information
5. **Portfolio**: Filterable work showcase with categories
6. **Testimonials**: Client feedback carousel with ratings
7. **Contact**: Comprehensive contact form and information
8. **Footer**: Quick links, social media, and company details

### 🎨 Design Features
- **Gradient Text Effects**: Eye-catching gradient text animations
- **Hover Animations**: Interactive elements with smooth hover effects
- **Scroll Animations**: Elements animate as they enter the viewport
- **Custom Color Palette**: Professional color scheme with primary and dark themes
- **Typography**: Inter and Poppins fonts for modern readability

## 🚀 Tech Stack

- **Framework**: Next.js 14 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Scroll Detection**: react-intersection-observer
- **Deployment**: Vercel/Netlify ready

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd moon-creation-films-website
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🛠️ Project Structure

```
moon-creation-films-website/
├── app/
│   ├── globals.css          # Global styles and Tailwind directives
│   ├── layout.tsx           # Root layout with metadata
│   └── page.tsx             # Home page component
├── components/
│   ├── Header.tsx           # Navigation header
│   ├── Hero.tsx             # Hero section
│   ├── Services.tsx         # Services showcase
│   ├── About.tsx            # About section
│   ├── Portfolio.tsx        # Portfolio with filters
│   ├── Testimonials.tsx     # Client testimonials
│   ├── Contact.tsx          # Contact form and info
│   └── Footer.tsx           # Footer with links
├── public/                  # Static assets
├── tailwind.config.js       # Tailwind configuration
├── next.config.js           # Next.js configuration
├── tsconfig.json            # TypeScript configuration
└── package.json             # Dependencies and scripts
```

## 🎨 Customization

### Colors
The color scheme is defined in `tailwind.config.js`:
- **Primary**: Blue gradient (`primary-500` to `primary-700`)
- **Dark**: Dark theme colors (`dark-800` to `dark-900`)
- **Gradients**: Purple and blue combinations

### Content
Update content in respective component files:
- **Services**: Modify `services` array in `components/Services.tsx`
- **Portfolio**: Update `portfolioItems` in `components/Portfolio.tsx`
- **Testimonials**: Edit `testimonials` array in `components/Testimonials.tsx`
- **Contact Info**: Update contact details in `components/Contact.tsx`

### Images
Replace placeholder images in the `public/` directory:
- Logo images
- Portfolio thumbnails
- Team photos
- Background images

## 📱 Responsive Breakpoints

- **Mobile**: < 640px
- **Tablet**: 640px - 1024px
- **Desktop**: > 1024px

## 🚀 Deployment

### Vercel (Recommended)
1. Push code to GitHub
2. Connect repository to Vercel
3. Deploy automatically

### Netlify
1. Build the project: `npm run build`
2. Upload `out/` directory to Netlify

### Manual Deployment
```bash
npm run build
npm run start
```

## 📞 Contact Information

- **Phone**: +91 8435071267
- **Email**: info@mooncreationfilms.com
- **Location**: Mumbai, Maharashtra, India
- **Website**: [mooncreationfilms.com](https://mooncreationfilms.com)

## 🔧 Environment Variables

Create a `.env.local` file for environment-specific configurations:
```env
NEXT_PUBLIC_SITE_URL=https://mooncreationfilms.com
NEXT_PUBLIC_GOOGLE_ANALYTICS_ID=your-ga-id
```

## 📈 Performance Optimization

- **Image Optimization**: Next.js Image component for automatic optimization
- **Code Splitting**: Automatic code splitting by Next.js
- **Lazy Loading**: Images and components load as needed
- **Minification**: Automatic CSS and JS minification

## 🔍 SEO Features

- **Meta Tags**: Comprehensive meta tags for all pages
- **Open Graph**: Social media sharing optimization
- **Structured Data**: JSON-LD schema markup
- **Sitemap**: Automatic sitemap generation
- **Robots.txt**: Search engine crawling instructions

## 🎯 Future Enhancements

- [ ] Blog section for content marketing
- [ ] Admin panel for content management
- [ ] Booking calendar integration
- [ ] Newsletter subscription functionality
- [ ] Multi-language support
- [ ] Dark mode toggle
- [ ] Advanced portfolio filtering
- [ ] Video background in hero section

## 📄 License

This project is proprietary to Moon Creation Films. All rights reserved.

## 🤝 Contributing

For internal development and updates, please follow the established coding standards and component structure.

---

**Built with ❤️ by Moon Creation Films Team** # deepak-s-project
