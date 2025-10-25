# 🌸 Kiminini Nuru Women Website

A **responsive, modern website** for **Kiminini Nuru Women** — a community-based organization empowering visually impaired women in Kiminini, Kenya through **vocational training, life skills**, and **community inclusion**.

---

## 🌟 Project Overview

This project consists of a complete multi-page website built using **Bootstrap 5** with a **mobile-first approach**.  
It features a cohesive design system, accessibility features, and **multi-language support**.

---

## 📁 Project Structure

kiminini-nuru-women/
│
├── index.html # Homepage
├── about.html # About Us page
├── work.html # Our Work page
├── getInvolved.html # Get Involved page
│
├── assets/
│ ├── images/ # All website images
│ │ ├── nurulogo.png
│ │ ├── cover.jpg
│ │ └── team-photos/
│ └── css/
│ └── custom.css # Additional custom styles
│
└── README.md

markdown
Copy code

---

## 🎨 Design Features

### 🎨 **Color Scheme**
| Role | Color | Description |
|------|--------|-------------|
| Primary | `#e81a50` | Vibrant pink/red |
| Secondary | `#000000` | Black |
| Light | `#f8f9fa` | Light gray |
| Dark | `#333333` | Dark gray |
| White | `#ffffff` | White |

### ✍️ **Typography**
- **Font Family:** [Poppins (Google Fonts)](https://fonts.google.com/specimen/Poppins)  
- **Font Weights:** 300, 400, 500, 600, 700

### 🧩 **Key Components**
- Sticky navigation with logo and responsive menu  
- Cards with hover effects  
- Bootstrap 5 grid system  
- Accessibility tools (font size, contrast, text spacing)  
- Multi-language support (English, German, French)

---

## 🚀 Features

### 🖥️ **Core Functionality**
✅ Fully responsive design (mobile-first)  
✅ Sticky navigation header  
✅ Donation modal with form  
✅ Image carousels and galleries  
✅ Expandable team sections  
✅ Animated statistics counters  
✅ Contact and social links  

### ♿ **Accessibility Features**
✅ Adjustable font size (Normal, Large, Extra Large)  
✅ High contrast mode  
✅ Text spacing options  
✅ Keyboard navigation  
✅ Screen reader friendly  

### 🌐 **Language Support**
✅ English (default)  
✅ German  
✅ French  
✅ Language persistence with `localStorage`

---

## 🛠️ Technologies Used

- **HTML5** – Semantic markup  
- **CSS3** – Custom properties, flexbox, grid  
- **Bootstrap 5** – Responsive framework  
- **Bootstrap Icons** – Vector icons  
- **Google Fonts** – Poppins family  
- **JavaScript** – Dynamic interactivity  
- **GSAP** – Scroll animations  

---

## 📱 Responsive Breakpoints

| Device | Width |
|---------|--------|
| Mobile | `< 576px` |
| Tablet | `576px - 768px` |
| Desktop | `768px - 992px` |
| Large Desktop | `> 992px` |

---

## 🎯 Pages Description

### 🏠 **Homepage (`index.html`)**
- Hero section with impactful imagery  
- Focus areas using cards  
- Animated statistics  
- Call-to-action sections  
- Beneficiary testimonials  

### 👩‍🦯 **About Us (`about.html`)**
- Mission and vision statements  
- Growth timeline  
- Team member profiles (expandable)  
- Impact metrics and future goals  

### 🛠️ **Our Work (`work.html`)**
- Vocational training programs  
- Community initiatives  
- Impact metrics  
- Photo galleries and success stories  

### 🤝 **Get Involved (`getInvolved.html`)**
- Volunteer and partnership info  
- Donation options and forms  
- Contact section  
- Ways to support  

---

## 🔧 Installation & Setup

1. **Clone or download** this repository.  
   ```bash
   git clone https://github.com/yourusername/kiminini-nuru-women.git
Ensure all file paths are correct for your server.

Upload to a web server or open locally in a browser.

Test all forms and modals.

🗂️ File Path Requirements
Logo images in same directory as HTML files

Team photos properly referenced in about.html

Bootstrap CDN links must be accessible

⚙️ Customization Guide
✏️ Updating Content
Text: Edit directly in the .html files

Images: Replace images in /assets/images/

Colors: Modify CSS custom properties in :root

Team: Update cards in about.html

🌍 Adding New Languages
Use data attributes for translations:

html
Copy code
<span data-en="English Text" data-de="German Text" data-fr="French Text">English Text</span>
Then, add the language option and flag in the language switcher panel.

🎨 Modifying Color Scheme
Edit in custom.css:

css
Copy code
:root {
  --primary: #e81a50;
  --secondary: #000000;
  --light: #f8f9fa;
  --dark: #333333;
  --white: #ffffff;
}
🌐 Browser Support
✅ Chrome (latest)
✅ Firefox (latest)
✅ Safari (latest)
✅ Edge (latest)
✅ Mobile browsers (iOS & Android)

📞 Contact & Support
Developer: Benard Oloo Ochieng
📞 +254 722 839 617
📧 ben@opendesk.co.ke
🌍 opendesk.co.ke

📄 License
This project was developed for Kiminini Nuru Women.
All rights reserved.

🔄 Version History
Version	Date	Notes
v1.0	October 2024	Initial release with complete functionality: responsive design, multi-language support, accessibility tools, interactive UI.

Built with ❤️ by Benard Oloo Ochieng for Kiminini Nuru Women
