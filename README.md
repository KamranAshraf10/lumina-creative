# 🌟 Lumina Creative - Portfolio Website

Lumina Creative is a fully responsive, multi-page creative portfolio website built using HTML, CSS, and JavaScript. It is perfect for showcasing design, photography, or development work with a clean gallery, team section, and contact form.

---

## 🚀 Features

- ✅ Multi-page layout: Home, About, and Contact
- 🖼️ Lightbox gallery for showcasing portfolio images
- 🌐 Fully responsive with mobile-first design
- 🎨 Stylish and modern design with Google Fonts
- 📷 Font Awesome icons for social media
- 📧 Contact form design (static; backend not included)

---

## 📁 Folder Structure

```
lumina-creative/
│
├── index.html            # Homepage with gallery
├── about.html            # About page with services and team
├── contact.html          # Contact form and details
│
├── css/
│   └── styles.css        # Main stylesheet
│
├── images/
│   ├── favicon.ico
│   ├── logo.png
│   ├── portfolio1.jpg to portfolio9.jpg
│   ├── image1.jpg to image9.jpg         # Full-size lightbox images
│   └── team1.jpg to team3.jpg           # Team section photos
```

---

## 📦 Dependencies (via CDN)

- [Lightbox2](https://lokeshdhakar.com/projects/lightbox2/) – Image lightbox feature
- [Font Awesome](https://fontawesome.com/) – Social media icons
- [Google Fonts](https://fonts.google.com/) – Montserrat, Open Sans, Poppins
- [jQuery](https://jquery.com/) – Required by Lightbox2

---

## 🔧 How to Use

1. **Live Demo**

   ```bash
   https://theluminacreatives.netlify.app/
   ```

2. **Download or Clone Repository**

   ```bash
   git clone https://github.com/KamranAshraf10/lumina-creative.git
   ```

3. **Open in Browser**

   - Open `index.html` in your preferred browser.

4. **Customize**
   - Replace images in the `images/` folder with your own.
   - Update text content in `about.html` and `contact.html`.
   - Adjust styles in `css/styles.css` as needed.

---

## 💡 Customization Tips

- To add more portfolio items, duplicate a `.gallery-item` block in `index.html`.
- To connect the contact form to a backend (e.g., PHP or Formspree), update the `<form>` action and method accordingly.
- Update social links by replacing `#` with actual URLs in the `<footer>`.

---

## 📝 License

This project is free to use for personal and educational purposes.

---

> Designed with 💙 by Kamran
