# EVP Whitepaper Landing Page

**Live URL**: [To be deployed on Netlify]

## 📋 Project Overview
Professional landing page voor Recruitin's EVP (Employee Value Proposition) whitepaper download campagne.

## ✨ Features
- 🎨 Modern, responsive design gebaseerd op Recruitin design system
- 📱 Mobile-first responsive layout
- 🔗 Pipedrive form integratie voor lead capture
- ⚡ Performance optimized met loading states
- ♿ Accessibility compliant (WCAG guidelines)
- 📊 Analytics ready (Google Analytics/Tag Manager)
- 🎯 Conversion optimized UX/UI

## 🛠 Tech Stack
- **Frontend**: HTML5, CSS3 (Custom Properties), Vanilla JavaScript
- **Forms**: Pipedrive Web Forms integration
- **Fonts**: Google Fonts (Inter)
- **Hosting**: Netlify (recommended)
- **Analytics**: Google Analytics/Tag Manager ready

## 🎨 Design System
- **Primary Colors**: Recruitin brand colors (#1B365D, #4A90A4, #F47C3C)
- **Typography**: Inter font family
- **Spacing**: Consistent spacing system
- **Shadows**: Layered shadow system for depth
- **Borders**: Rounded corners for modern feel

## 🚀 Deployment
- **Method**: GitHub → Netlify auto-deploy
- **Branch**: `main` (production)
- **Build**: Static site (no build process required)

## 📈 Performance Targets
- Lighthouse Score: 95+
- First Contentful Paint: <1s
- Mobile Friendly: 100%
- Accessibility: A+

## 🔧 Configuration
### Pipedrive Form
Update the form URL in `index.html`:
```html
<div class="pipedriveWebForms" 
     data-pd-webforms="YOUR_PIPEDRIVE_FORM_URL">
```

### Analytics
Uncomment and configure Google Analytics in `index.html`:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
```

## 📱 Responsive Breakpoints
- **Desktop**: 1024px+
- **Tablet**: 768px - 1023px
- **Mobile**: 480px - 767px
- **Small Mobile**: <480px

## 🎯 Conversion Elements
- Compelling headline with social proof statistics
- Clear value proposition
- Trust indicators
- Single-column form for reduced friction
- Prominent CTA buttons
- Professional whitepaper preview

## 📊 Analytics Events
- Page view tracking
- Form interaction tracking
- Conversion tracking
- Performance monitoring

## 🔒 Security & Privacy
- HTTPS only
- Privacy-compliant form handling
- No sensitive data collection
- GDPR-ready structure

## 📞 Contact
Voor vragen of aanpassingen: Recruitin team

---
*Ontwikkeld voor Recruitin's lead generation campagne*