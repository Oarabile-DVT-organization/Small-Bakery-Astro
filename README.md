# 🥐 The Golden Crust
 
A small static bakery website built with Astro, Tailwind CSS, and DaisyUI.
 
## 🛠️ Tech Stack
 
- [Astro](https://astro.build/) — Static site generator
- [Tailwind CSS](https://tailwindcss.com/) — Utility-first CSS framework
- [DaisyUI](https://daisyui.com/) — Tailwind CSS component library
- [TypeScript](https://www.typescriptlang.org/) — Type safety
 
## 📄 Pages
 
- **Home** — Hero section, features, and call to action
- **Menu** — Bakery menu items loaded from a local JSON file
 
## 📁 Project Structure
 
```
src/
├── assets/          # Images and SVGs
├── components/      # Reusable components (Navbar, Footer)
├── data/
│   └── menu.json    # Menu items data
├── layouts/
│   └── Layout.astro # Base layout with Navbar and Footer
├── pages/
│   ├── index.astro  # Home page
│   └── menu.astro   # Menu page
└── styles/
    └── global.css   # Global styles and Tailwind/DaisyUI imports
```
 
## 🚀 Getting Started
 
### Prerequisites
 
- Node.js 18+
- npm
 
### Installation
 
1. Clone the repository:
```bash
git clone <your-repo-url>
cd the-golden-crust
```
 
2. Install dependencies:
```bash
npm install
```
 
3. Start the development server:
```bash
npm run dev
```
 
4. Open your browser at `http://localhost:4321`
 
## 🏗️ Build for Production
 
```bash
npm run build
```
 
The output will be in the `dist/` folder, ready to deploy.
 
## 🌍 Deployment
 
This site can be deployed for free on:
- [Netlify](https://netlify.com)
- [Vercel](https://vercel.com)
- [GitHub Pages](https://pages.github.com)
 
## 📦 Adding Menu Items
 
Menu items are stored in `src/data/menu.json`. To add a new item:
 
```json
{
  "id": 6,
  "name": "Your Item",
  "price": "R00",
  "calories": "000kcal",
  "image": "https://your-image-url.com"
}
```
 
## 🎨 Theme
 
This project uses the **cupcake** DaisyUI theme, set in `src/layouts/Layout.astro`:
 
```astro
<html data-theme="cupcake">
```
## Pictures

<img width="1680" height="1050" alt="Screenshot 2026-03-20 at 15 53 11" src="https://github.com/user-attachments/assets/457fef8c-7e16-4331-92ba-437540f2fbc3" />
<img width="1680" height="1050" alt="Screenshot 2026-03-20 at 15 59 54" src="https://github.com/user-attachments/assets/430bfe74-7e18-4e78-90d3-4f355ee6ec13" />




 
