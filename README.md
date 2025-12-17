# 🍸 Cocktail Menu Website

A modern, animated cocktail menu website built with **React + Vite** and styled using **Tailwind CSS**. The site features a smooth slider-style cocktail menu, interactive navigation, and clean UI animations for an engaging user experience.

---

## 🚀 Features

* ⚛️ Built with **React (Vite)** for fast performance
* 🎨 Styled using **Tailwind CSS**
* 🧭 Interactive cocktail slider with previous/next navigation
* 🖱️ Clickable tabs to switch between cocktails
* 📱 Responsive design (desktop & mobile friendly)
* ✨ Smooth UI animations

---

## 🛠️ Tech Stack

* **React**
* **Vite**
* **Tailwind CSS**
* **JavaScript (ES6+)**

---

## 📂 Project Structure

```
├── public/
│   └── images/            # Static images (cocktails, arrows, leaves)
├── src/
│   ├── components/        # Reusable UI components
│   ├── constants/         # Cocktail data
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. **Navigate to the project folder**

   ```bash
   cd your-repo-name
   ```

3. **Install dependencies**

   ```bash
   npm install
   ```

4. **Start the development server**

   ```bash
   npm run dev
   ```

5. Open your browser and visit:

   ```
   http://localhost:5173
   ```

---

## 🖼️ Image Handling

Cocktail images are stored in the `public/images` directory and referenced like this:

```jsx
<img src={currentCocktail.image} alt={currentCocktail.name} />
```

Example data object:

```js
{
  id: 1,
  name: "Mojito",
  image: "/images/mojito.png"
}
```

---

## ♿ Accessibility

* Uses semantic HTML elements
* `aria-label` and `aria-labelledby` for navigation
* Screen-reader–only headings for better accessibility

---

## 📦 Build for Production

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

---

## 📌 Future Improvements

* Add backend / CMS for dynamic cocktail data
* Add dark/light theme toggle
* Improve animations with GSAP
* Add filtering by category or ingredients

---

## 👤 Author

**Binay Meche**
Frontend Developer in progress 🚀
Learning React, JavaScript, and modern web development

---

## 📄 License

This project is for learning and personal use.

---

⭐ If you like this project, feel free to star the repo!
