# 🚀 AI Website Prompt Generator

A comprehensive web application that generates detailed AI prompts for creating custom websites. This tool helps users create specific, tailored prompts that can be used with AI assistants like ChatGPT, Claude, or any other AI to generate complete, functional websites.

## ✨ Features

### 🎯 **Detailed Prompt Generation**
- Creates comprehensive, structured prompts for AI website generation
- Includes business information, technical specifications, and design requirements
- Generates prompts ready to copy-paste into any AI assistant

### 🌍 **Bilingual Support**
- **English** (default)
- **Spanish** (Español)
- Complete interface translation with language switcher

### 📋 **Comprehensive Form Fields**
- **Business Information**: Name, description, industry, target audience
- **Website Type**: Business, e-commerce, portfolio, blog, landing page, etc.
- **Sections**: Home, About, Services, Products, Portfolio, Contact, FAQ, etc.
- **Special Features**: Contact forms, newsletters, booking systems, live chat, etc.
- **Design & Style**: Modern, minimalist, professional, color schemes, layouts
- **Technical Requirements**: Responsive design, SEO optimization, accessibility
- **Additional Requirements**: Custom specifications and inspiration references

### 🔧 **Advanced Functionality**
- ✅ Auto-save form data to localStorage
- ✅ One-click copy to clipboard
- ✅ Fully responsive design (mobile & desktop)
- ✅ Real-time form validation
- ✅ Smooth animations and transitions
- ✅ Modern, professional UI/UX

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No server required - runs entirely in the browser

### Installation
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start generating AI prompts!

```bash
# Clone the repository
git clone [repository-url]

# Navigate to the project directory
cd ai-website-prompt-generator

# Open index.html in your browser
# No build process required!
```

## 📖 How to Use

1. **Open the Application**: Launch `index.html` in your web browser
2. **Choose Language**: Select English or Spanish using the language switcher
3. **Fill the Form**: Complete the form fields based on your website requirements
4. **Generate Prompt**: Click "Generate AI Prompt" to create your custom prompt
5. **Copy & Use**: Copy the generated prompt and paste it into your preferred AI assistant

### Example Workflow
```
1. Enter business name: "TechStart Solutions"
2. Select website type: "Business/Corporate"
3. Choose sections: Home, About, Services, Contact
4. Select features: Contact form, Newsletter signup
5. Set design style: "Modern"
6. Generate prompt → Copy to clipboard
7. Paste into ChatGPT/Claude → Get your website!
```

## 🎨 Generated Prompt Structure

The generated prompts include:

- **Business Information**: Complete business details and target audience
- **Website Type & Structure**: Layout preferences and required sections
- **Design & Visual Style**: Color schemes, design aesthetics, and responsive requirements
- **Features & Functionality**: Special features, SEO, and accessibility requirements
- **Technical Specifications**: HTML5, CSS3, JavaScript implementation details
- **Content Requirements**: Guidelines for realistic, professional content

## 📁 Project Structure

```
ai-website-prompt-generator/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality and translations
└── README.md          # Project documentation
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and form structure
- **CSS3**: Modern styling, grid/flexbox layouts, animations
- **JavaScript (ES6+)**: Dynamic functionality, translations, localStorage
- **Google Fonts**: Inter font family for modern typography

## 🌟 Key Components

### Language System
- Complete bilingual support (English/Spanish)
- Dynamic content translation
- Persistent language preference

### Form Management
- Auto-save functionality using localStorage
- Real-time validation
- Comprehensive input types (text, select, checkbox, textarea)

### Prompt Generation
- Template-based prompt creation
- Dynamic content insertion
- Structured, professional output

### User Experience
- Responsive design for all devices
- Smooth animations and transitions
- Intuitive interface with clear visual hierarchy

## 🎯 Use Cases

- **Web Developers**: Generate client website specifications
- **Business Owners**: Create detailed requirements for their websites
- **Designers**: Generate comprehensive briefs for AI-assisted design
- **Students**: Learn about website planning and structure
- **Agencies**: Streamline client onboarding and requirement gathering

## 🔧 Customization

### Adding New Industries
Edit the `industryOptions` object in `script.js`:

```javascript
const industryOptions = {
    en: {
        'new-industry': 'New Industry Name',
        // ... existing options
    },
    es: {
        'new-industry': 'Nombre de Nueva Industria',
        // ... existing options
    }
};
```

### Adding New Languages
1. Extend the `translations` object in `script.js`
2. Add new language button in HTML
3. Update the `switchLanguage()` function

### Modifying Prompt Templates
Edit the `promptTemplates` object in the `generatePrompt()` function to customize the output format.

## 📱 Browser Compatibility

- ✅ Chrome 70+
- ✅ Firefox 65+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Performance Features

- Lightweight (no external dependencies)
- Fast loading times
- Efficient DOM manipulation
- Optimized for mobile devices
- Progressive enhancement

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Google Fonts for the Inter font family
- Modern CSS techniques for responsive design
- JavaScript ES6+ features for enhanced functionality

## 📞 Support

If you encounter any issues or have questions:
1. Check the browser console for any errors
2. Ensure JavaScript is enabled in your browser
3. Try refreshing the page to reload saved form data
4. Clear localStorage if experiencing data persistence issues

---

**Made with ❤️ to help create better websites with AI assistance.**
