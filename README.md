# 🖼️ ImageGen App – Next.js Setup Project

Welcome to the **ImageGen App**, a simple landing page styled with a combination of Tailwind CSS and custom global styles. This project is part of the ALX Front-End program, focused on mastering layout structuring, global styling, and component-based UI in Next.js.

---

## 📌 Project Description

The goal of this project is to implement a clean, responsive UI layout using:

- ✅ Next.js (React Framework)
- 🎨 Tailwind CSS utility-first classes
- 🧾 Custom global CSS for fine-tuned theming and layout control

The page includes:

- A header with a logo and navigation links
- A main section with an input field and button
- A styled footer section

---

## ⚙️ Technologies Used

| Technology       | Description                              |
| ---------------- | ---------------------------------------- |
| **Next.js**      | Framework for server-rendered React apps |
| **TypeScript**   | Strongly typed superset of JavaScript    |
| **Tailwind CSS** | Utility-first CSS framework              |
| **Custom CSS**   | For global styles and fallback theming   |

---

## 🎨 Styling Approach

This project leverages both Tailwind and manual CSS:

### ✅ Tailwind CSS

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### ✅ Custom Global Styles

```css
body {
  font-family: "Segoe UI", Tahoma, sans-serif;
  background-color: var(--background);
  color: var(--foreground);
}
```

Light and dark mode are supported via `prefers-color-scheme`.

---

## 🧱 Folder Structure

```
/pages
  |_ index.tsx         # Main landing page
/styles
  |_ global.css        # Global styles and Tailwind imports
/public
  |_ assets/           # Static assets and image files
```

---

## 🚀 Getting Started
