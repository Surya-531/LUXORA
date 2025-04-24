## LUXORA - E-Commerce Web Application

LUXORA is a responsive, modern front-end prototype for an online apparel store. Built with vanilla HTML, CSS, and JavaScript, this project demonstrates core web development concepts such as responsive navigation, product listing and search filtering, and a contact form.

---

## 🔍 Project Overview

- **Purpose:** Provide a seamless and modern shopping experience with multiple page navigation, responsive design, and interactive features.
- **Users:** Shoppers browsing products and submitting queries.
- **Pages:** Home, Collections, Contact.

---

## 🛠️ Approach

1. **User Interface & Design**
   - **Responsive Layout:** Uses CSS Flexbox and media queries to adapt to desktop, tablet, and mobile screens.
   - **Navigation:** A top navbar for desktop and a collapsible side navbar for mobile for easy access to all pages.
   - **UI Components:** Hero section, service highlights, product grids, search bar, and footer with social links.

2. **Core Functionality**
   - **HTML Structure:** Semantically organized pages:
     - `INDEX.html` – Homepage with hero, service section, featured/new arrival/most wanted products, and newsletter signup.
     - `collections.html` – Grid of products with live search filtering.
     - `contact.html` – Contact form collecting name, email, phone, and message.
   - **Styling:** `style.css` defines global styles, component layouts, and responsive adjustments.
   - **Interactivity:**
     - `script.js` manages showing/hiding the side navigation bar.
     - `collections.js` listens for `keyup` events on the search input and filters product boxes in real time.

3. **Development Workflow**
   - **Clone & Serve:** Simple local server (e.g., `http-server`) or direct file opening in browser.
   - **Modify:** Update HTML for content changes, adjust CSS for styles, and enhance JS for interactivity.

---

## 🗂️ File Structure

```plaintext
LUXORA/
├── INDEX.html        # Homepage: Hero, services, featured & new arrival sections
├── collections.html  # Collections page: Product grid + live search
├── contact.html      # Contact page: User inquiry form
├── style.css         # Global styles: layout, colors, responsive rules
├── script.js         # Navbar toggle: show/hide side navigation
└── collections.js    # Product filter: search input handling
```

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/LUXORA.git
   cd LUXORA
   ```
2. **Open in browser**
   - Double-click `INDEX.html`, or
   - Serve via a local server:
     ```bash
     npx http-server .
     ```
   - Visit `http://localhost:8080`.
3. **Test Features**
   - Navigate pages via navbar.
   - Use search box on Collections to filter products.
   - Submit dummy entries via Contact form (front-end only).

---

## 🚀 Features

- **Responsive Navigation:** Top navbar + mobile sidebar toggle.
- **Dynamic Collections:** Live search filtering of products.
- **Contact Form:** Collect user queries (front-end simulated).
- **Consistent Footer:** Shared across pages with social icons.

---

## 💻 Technologies

- **HTML5** – Semantic page structure.
- **CSS3** – Flexbox, Grid, media queries for responsiveness.
- **JavaScript** – DOM manipulation for UI interactivity.
- **Google Fonts & Font Awesome** – Typography & icons.

---

## 🤝 Contributing

1. Fork this repo
2. Create a branch: `git checkout -b feature/YourFeature`
3. Commit changes: `git commit -m "Add YourFeature"`
4. Push branch: `git push origin feature/YourFeature`
5. Open a Pull Request

---

## 📄 License

This project is licensed under MIT. See [LICENSE](LICENSE.md) for details.

---

## 📬 Contact

- **Maintainer:** Your Name
- **GitHub:** [Surya-531](https://github.com/Surya-531)
- **Site:** luxora-surya.netlify.com

