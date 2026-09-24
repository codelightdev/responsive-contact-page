# 📬 Simple Contact Page — HTML & CSS

A modern, responsive **Contact Page UI** built from scratch using **HTML and CSS**.

This project focuses on creating a clean and visually engaging contact section with a dark aesthetic, glassmorphism effects, gradient lighting, responsive layouts, custom typography, and Bootstrap Icons — all without JavaScript or CSS frameworks.

> 🎥 This project was created as part of a frontend development tutorial on the **Code Light** YouTube channel.

---

## 📺 Tutorial

Watch the full tutorial on YouTube:

**▶️ [Build a Modern Contact Page with HTML & CSS](https://youtu.be/YLjWt4uoEXM)**

In this tutorial, you'll learn how to build the contact page from scratch and understand how the different HTML and CSS techniques work together to create the final design.

---

## ✨ Preview

The project features a modern dark interface with:

- 🖤 Dark background
- 💜 Purple gradient lighting
- 🪟 Glassmorphism contact information card
- ✨ Frosted-glass navigation
- 📝 Contact form
- 📍 Contact information section
- 🎨 Outlined typography
- 🔘 Interactive navigation items
- 🎯 Focus states for form fields
- 📱 Responsive flexbox layout
- 🎭 Subtle hover and interaction effects

---

## 🚀 Features

### Navigation

The project includes a simple navigation bar containing:

- Home
- About
- Services
- Contact

The navigation uses a glass-like appearance created with CSS gradients, transparency, borders, shadows, and `backdrop-filter`.

---

### Contact Information

The contact information section displays different ways users can get in touch.

It includes:

- 📍 Location
- ✉️ Email
- ☎️ Phone
- 💬 WhatsApp
- 📸 Instagram

Bootstrap Icons are used to visually represent each contact method.

---

### Contact Form

The contact form contains:

- Full Name input
- Email input
- Message textarea
- Submit button

The form also includes custom focus states to make the interaction feel more polished.

> **Note:** This project focuses on the frontend interface. The form does not currently have a backend or form-processing system connected to it.

---

## 🎨 Design

The design is built around a dark and modern visual style.

### Color Palette

| Variable | Color | Purpose |
|---|---|---|
| `--main` | `#d27af1` | Primary purple |
| `--sub-main` | `#bb75d3` | Secondary purple |
| `--black` | `#333` | Dark gray |
| `--dark` | `#000` | Main background |
| `--white` | `#fff` | Text and highlights |

The purple tones are combined with a black background to create the project's overall visual identity.

---

## 🪟 Glassmorphism

One of the main visual elements of this project is the glassmorphism effect.

The contact information card uses:

```css
background: linear-gradient(
    135deg,
    rgba(255, 255, 255, 0.12),
    rgba(255, 255, 255, 0.035) 45%,
    rgba(180, 100, 220, 0.08)
);

backdrop-filter: blur(25px) saturate(140%);