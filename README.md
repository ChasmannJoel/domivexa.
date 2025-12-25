# Domivexa - Digital Marketing Website

Professional digital marketing website for Domivexa Ltd.

## 🌐 Domain
domivexa.co.uk

## 📁 Structure

```
domivexa.co.uk/
├── index.html          # Home page
├── about.html          # About Us
├── services.html       # Services
├── contact.html        # Contact
├── blog.html           # Blog/Resources
├── faq.html            # Frequently Asked Questions
├── terms.html          # Terms & Conditions
├── privacy.html        # Privacy Policy
├── cookies.html        # Cookie Policy
├── legal.html          # Legal Notice
├── styles.css          # Main stylesheet
├── sitemap.xml         # Sitemap for search engines
├── robots.txt          # Robots file
└── vercel.json         # Vercel configuration
```

## 🚀 Deployment to Vercel

### Method 1: Using Vercel CLI

1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Navigate to your project directory:
```bash
cd "c:\Users\joelc\OneDrive\Escritorio\domivexa.co.uk"
```

3. Deploy:
```bash
vercel
```

4. Follow the prompts and link to your Vercel account

### Method 2: Using Git and Vercel Dashboard

1. Initialize Git repository:
```bash
git init
git add .
git commit -m "Initial commit"
```

2. Create a repository on GitHub

3. Push to GitHub:
```bash
git remote add origin YOUR_GITHUB_REPO_URL
git push -u origin main
```

4. Go to [Vercel Dashboard](https://vercel.com/dashboard)
5. Click "Add New Project"
6. Import your GitHub repository
7. Deploy

## 🔧 DNS Configuration

After deploying to Vercel, configure your DNS:

1. Go to your domain registrar (where you bought domivexa.co.uk)
2. Add these DNS records:

```
Type: A
Name: @
Value: 76.76.21.21

Type: CNAME
Name: www
Value: cname.vercel-dns.com
```

3. In Vercel dashboard:
   - Go to your project settings
   - Click "Domains"
   - Add "domivexa.co.uk" and "www.domivexa.co.uk"
   - Verify DNS configuration

## ⚠️ Important: Update Required Information

Before going live, replace the following placeholders in ALL files:

### Business Information to Update:
- `[Your Business Address]` - Your complete registered business address
- `[Your Phone Number]` - Your business phone number
- `[Your Company Number]` - UK Companies House registration number
- `[Your VAT Number]` - VAT registration number
- `[Your ICO Registration Number]` - ICO data protection registration
- `[Director Name(s)]` - Company directors (required by UK law)
- `[Your Insurance Provider]` - Professional indemnity insurance details
- `[Professional Association 1/2]` - Any professional memberships
- `[Your Facebook/Twitter/LinkedIn/Instagram URL]` - Social media links

### Files to Update:
- index.html
- about.html
- contact.html
- services.html
- blog.html
- faq.html
- terms.html
- privacy.html
- cookies.html
- legal.html

## ✅ Meta Verification Checklist

This website includes all requirements for Meta Business verification:

- ✅ Clear business presentation
- ✅ About Us page with team information
- ✅ Complete contact information
- ✅ Terms & Conditions
- ✅ Privacy Policy (GDPR compliant)
- ✅ Cookie Policy with banner
- ✅ Legal Notice with company registration
- ✅ Services description
- ✅ FAQ page
- ✅ Blog with original content
- ✅ Sitemap.xml
- ✅ Robots.txt
- ✅ SSL ready (Vercel provides HTTPS automatically)

## 🔐 Security Features

- HTTPS (automatic with Vercel)
- Security headers configured in vercel.json
- Cookie consent banner
- GDPR compliant privacy policy
- Data protection measures

## 📱 Features

- Fully responsive design
- Mobile-friendly navigation
- Cookie consent banner
- Contact form with validation
- SEO optimized
- Fast loading (static HTML/CSS)
- No images for quick deployment

## 🛠 Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript (minimal, for cookie banner)
- Static hosting (Vercel)

## 📞 Support

For questions or issues, contact:
- Email: info@domivexa.co.uk
- Website: https://domivexa.co.uk

## 📄 License

© 2025 Domivexa Ltd. All rights reserved.

---

**Note:** This is a professional business website. Ensure all legal information is accurate and up-to-date before launching.