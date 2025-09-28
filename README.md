# Responsive Pricing Table Showcase

A responsive, animated pricing table component built with HTML, CSS, and minimal JavaScript.  
Highlighting the “Most Popular” plan with animations, and toggling between monthly/yearly billing.

---

## 📂 Table of Contents

- [Features](#-features)  
- [Demo / Screenshots](#-demo--screenshots)  
- [Installation / Setup](#-installation--setup)  
- [Usage](#-usage)  
- [Customisation](#-customisation)  
- [Structure](#-structure)  
- [Browser Support](#-browser-support)  
- [Contributing](#-contributing)  
- [License](#-license)  

---

## 🔍 Features

- Three pricing plans: Starter, Pro (highlighted as *Most Popular*), and Enterprise.  
- Animated highlight: scale, pulse, ribbon for the popular plan.  
- Monthly / Yearly toggle with discount logic.  
- Responsive layout: columns become stacked on smaller viewports.  
- Accessible buttons / keyboard‐friendly toggle.  

---

## 🖼 Demo / Screenshots

*(Include a screenshot or gif if possible)*  
Here is how it looks in desktop vs mobile:

[Insert screenshot / animated GIF here]

yaml
Copy code

---

## 🚀 Installation / Setup

1. Clone the repo:  
   ```bash
   git clone https://github.com/username/responsive-pricing-table.git
Navigate into the folder:

bash
Copy code
cd responsive-pricing-table
Open index.html in your browser to see it live.

(Optional) Serve with a local server (useful if you integrate with other assets):

bash
Copy code
# using Python simple server
python3 -m http.server
Then open http://localhost:8000 in your browser.

⚙️ Usage
Edit the HTML to change plan names, feature lists, and pricing values.

The pricing values are stored in data-monthly and data-yearly attributes inside .price spans.

The toggle switch (checkbox) controls whether monthly or yearly pricing is shown.

Adjust discount logic in JS if you want a different percentage for yearly.

🎨 Customisation
You can easily adapt the component:

What to change	Where to look
Colors (accent, background etc.)	CSS variables (:root)
Popular plan scale / pulse intensity	CSS --popular-scale, @keyframes popPulse
The ribbon text / style	.ribbon in HTML & CSS
Fonts / typography	In the CSS (e.g. font-family)
Breakpoints for responsiveness	CSS media queries in the stylesheet

🧱 Structure
css
Copy code
/
├── index.html         → main page HTML
├── styles.css         → CSS styles (grid, animations etc.)
├── script.js          → toggle logic (monthly/yearly)
└── assets/            → optional folder for images/screenshots
🌐 Browser Support
Tested in the latest versions of:

Chrome

Firefox

Safari

Edge

Mobile / tablet viewports also supported via responsive design.

🤝 Contributing
Contributions are welcome! If you want to:

Report bugs

Suggest improvements (UI, features, accessibility)

Fix typos

Then please open an issue or submit a pull request.

📝 License
This project is released under the MIT License. See the LICENSE file for deta
