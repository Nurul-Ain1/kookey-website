# 🍪 Kookey — Freshly Baked Cookies Made With Love

Kookey is a single-page website for a cookie brand, built to showcase products, share the brand story, and let customers get in touch — all in one smooth scrolling experience.

This project was built with the help of **Claude (Anthropic)** using a vibe-coding approach — describing the desired look, feel, and functionality in natural language and iterating with AI-assisted development.

---

## ✨ Features

- **Hero Section** – Eye-catching landing area introducing the Kookey brand
- **About Us** – The brand's story, mission, and key stats (customers served, flavors offered, years of experience, etc.)
- **Products** – Browsable product grid with category filters (Best Sellers, Chocolate, Classic, Premium)
- **Shopping Cart** – Add products to cart, adjust quantities, and view running totals
- **Why Choose Us** – Highlights of Kookey's value proposition (quality, freshness, delivery, pricing)
- **Testimonials** – Customer reviews and feedback
- **Gallery** – Visual showcase of Kookey's cookies
- **FAQ** – Answers to frequently asked questions
- **Contact Form** – A form for customers to send inquiries or messages
- **Multi-language Support** – Switch between English, Malay, Tamil, and Chinese
- **Responsive Design** – Optimized for both desktop and mobile viewing

---

## 🛠️ Built With

- **HTML5** – Page structure and content
- **CSS3** – Styling, layout, and responsive design
- **JavaScript (Vanilla)** – Interactivity, cart logic, language switching, and form handling
- **Claude (Anthropic)** – AI pair-programmer used to generate and refine the codebase

---

## 📂 Project Structure

```
├── index.html      # Main website file (structure, styles, and scripts)
├── images/         # Images used across the website (hero, products, gallery, etc.)
└── README.md       # Project documentation
```

---

## 🚀 Getting Started

Since this is a static single-file website, no build tools or installations are required.

1. Clone this repository:
   ```bash
   git clone https://github.com/Nurul-Ain1/kookey-website.git
   ```
2. Open `index.html` in your browser.

That's it — the website will run directly in your browser.

---

## ⚠️ Current Limitations

- The **Contact Form** currently only validates and displays a success message on submission — it does not yet send data to an email, database, or backend service. Submitted details are not stored anywhere.
- Product and cart data reset on page refresh, as there is no backend or persistent storage connected yet.

---

## 🔮 Future Work

- [ ] Connect the Contact Form to an email service (e.g. Formspree, EmailJS) or a custom backend so customer inquiries are actually received
- [ ] Add a backend and database to store orders, products, and customer messages
- [ ] Implement real checkout and payment gateway integration
- [ ] Add user accounts and order history
- [ ] Improve accessibility (ARIA labels, keyboard navigation)
- [ ] Add automated testing for cart and form logic
- [ ] Deploy the website with a custom domain

---

## 📄 License

This project is open for personal learning and portfolio purposes. Feel free to fork and build upon it.

---

## 🙋‍♀️ Author

Built and maintained by **Nurul Ain** — feel free to reach out via GitHub Issues for any feedback or suggestions.
