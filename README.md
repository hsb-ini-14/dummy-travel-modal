# Dummy Travel Modal

An animated and interactive **Travel Booking Modal** built with **React,
Vite, and Tailwind CSS**.\
This project demonstrates creative UI animations, modal interactions,
random image rotations, and a modern booking-style layout.

🔗 **Live Demo:** https://hsb-ini-14.github.io/dummy-travel-modal/

------------------------------------------------------------------------

## ✨ Features

-   ✈️ Animated "Book Your Flight" button with 3D hover effect\
-   🪟 Smooth modal open/close transitions\
-   🎲 Random rotation effect on gallery images\
-   🖼️ Interactive image gallery inside modal\
-   📋 Dynamic flight offers list\
-   🖱️ Click-outside-to-close modal behavior\
-   📱 Fully responsive layout\
-   🎨 Styled with Tailwind CSS\
-   ⚡ Built using Vite for fast development

------------------------------------------------------------------------

## 🛠️ Tech Stack

-   **React** -- UI components & state management\
-   **Vite** -- Fast build tool & dev server\
-   **Tailwind CSS** -- Utility-first styling\
-   **GitHub Pages** -- Deployment

------------------------------------------------------------------------

## 📁 Project Structure

``` text
dummy-travel-modal/
├── public/
├── src/
│   ├── assets/
│   │   ├── images/
│   │   │   ├── img-1.jpg
│   │   │   ├── img-2.jpg
│   │   │   ├── img-3.jpg
│   │   │   ├── img-4.jpg
│   │   │   └── img-5.jpg
│   │   ├── plane.png
│   │   └── cancel.png
│   ├── components/
│   │   └── BG.jsx
│   ├── data/
│   │   └── index.js
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── vite.config.js
├── package.json
└── README.md
```

------------------------------------------------------------------------

## 🚀 Getting Started

Follow these steps to run the project locally:

### 1️⃣ Clone the repository

``` bash
git clone https://github.com/hsb-ini-14/dummy-travel-modal.git
cd dummy-travel-modal
```

### 2️⃣ Install dependencies

``` bash
npm install
```

### 3️⃣ Start the development server

``` bash
npm run dev
```

Open your browser and visit:

    http://localhost:5173

------------------------------------------------------------------------

## 🌍 Deployment to GitHub Pages

This project is deployed using **gh-pages**.

### Steps used:

1.  Install gh-pages

``` bash
npm install --save-dev gh-pages
```

2.  Set base path in `vite.config.js`

``` js
export default defineConfig({
  base: "/dummy-travel-modal/",
});
```

3.  Add scripts to `package.json`

``` json
"predeploy": "npm run build",
"deploy": "gh-pages -d dist"
```

4.  Deploy

``` bash
npm run deploy
```

------------------------------------------------------------------------

## 🧩 How It Works

-   Modal visibility is controlled using React `useState`\
-   Click-outside logic is handled using `useRef` and document click
    listeners\
-   Gallery images and flight offers are stored in a central data file\
-   Random rotation is applied to images for a playful stacked-card
    effect\
-   Tailwind utility classes handle layout, animations, and transitions

------------------------------------------------------------------------

## 📸 Preview

> to be added later

------------------------------------------------------------------------

## 🙌 Acknowledgements

-   Styling powered by Tailwind CSS\
-   Build tool by Vite\
-   UI logic built with React

------------------------------------------------------------------------

## 👤 Author

**Harsh Singh Bhaduria**

-   GitHub: https://github.com/hsb-ini-14

------------------------------------------------------------------------

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub --- it
really helps! 😊
