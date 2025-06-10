# Animated Portfolio

A modern, animated, and interactive developer portfolio built with Next.js, React, TypeScript, Tailwind CSS, Framer Motion, and Three.js.  
This project is designed to showcase professional skills, experience, and personality through engaging visuals and thoughtful UI/UX.

---

## ✨ Features

- **Animated Hero Section**: Dynamic introduction with spotlight effect, animated text, and smooth call-to-action.
- **Bento Grid About Section**: Data-driven, responsive grid layout for skills, bio, and highlights; supports interactive Lottie animations.
- **Approach Section**: Animated cards (using Framer Motion) clearly presenting work methodology.
- **3D Globe Visualization**: Interactive, animated globe (Three.js/@react-three/fiber) representing global reach or connections.
- **Floating Navigation Bar**: Persistent, smooth-scrolling navigation for quick access to all sections.
- **Dark/Light Mode**: Theming with seamless transitions via next-themes.
- **Fully Responsive**: Looks and works great on all devices.

---

## 🛠️ Tech Stack

- **Framework**: [Next.js](https://nextjs.org/) (App Router)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Animations**: [Framer Motion](https://www.framer.com/motion/), [Lottie](https://airbnb.io/lottie/)
- **3D/Visualization**: [Three.js](https://threejs.org/), [@react-three/fiber](https://docs.pmnd.rs/react-three-fiber/getting-started/introduction)
- **Theming**: [next-themes](https://github.com/pacocoursey/next-themes)
- **Icons**: [React Icons](https://react-icons.github.io/react-icons/)

---

## 📁 Project Structure

```
app/
  layout.tsx            # App-wide layout, theming, font
  page.tsx              # Main page composition (all sections)
  provider.tsx          # Theme provider setup
components/
  Hero.tsx              # Animated hero/intro section
  Grid.tsx              # About/skills grid section
  Approach.tsx          # Work methodology section
  ui/
    BentoGrid.tsx       # Grid and grid items
    Globe.tsx           # 3D globe core logic
    GridGlobe.tsx       # Globe configuration and display
    FloatingNav.tsx     # Floating navigation bar
  ...                   # Other modular components
public/
  ...                   # Static assets, images, icons
```

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/drxv3/Animated-Portfolio.git
   cd Animated-Portfolio
   ```

2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the development server:**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open [http://localhost:3000](http://localhost:3000) to view the app.**

---

## 📝 Customization

- Update content in the `components/` and `data/` directories to personalize the portfolio.
- Adjust colors, themes, and layout via `tailwind.config.js` and component styles.
- Add or remove sections by editing `app/page.tsx`.

---

## 📸 Demo

![Animated Portfolio Screenshot](https://github.com/drxv3/Animated-Portfolio/raw/main/public/demo.png)

---

## 👤 Author

- **Dhruv Kundu**
- [GitHub](https://github.com/drxv3)
- [LinkedIn](https://www.linkedin.com/in/dhruv-kundu-4b6a371b1/)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
