# Ochi Agency Clone

This project is a high-fidelity, responsive clone of the Ochi Design Agency website. It serves as an advanced portfolio piece designed to demonstrate technical proficiency in modern frontend development, specifically focusing on complex animations, smooth scrolling mechanics, and responsive design patterns.

## 🚀 Key Features

* Fluid Parallax Scrolling: Utilizes `locomotive-scroll` to create smooth, performant parallax effects that provide a premium, agency-grade user experience.
* Complex Motion Design: Leveraged `framer-motion` for scroll-triggered entrance animations, infinite marquee loops, and interactive hover states[cite: 1].
* Pixel-Perfect Design: Replicated custom design components like typography maskers, staggered section overlaps, and unique layout structures[cite: 1].
* Responsive Architecture: A mobile-first design approach using Tailwind CSS to ensure a consistent experience across devices ranging from mobile phones to high-resolution desktops[cite: 1].

## 🛠️ Technical Stack

* Framework: [React](https://react.dev/) with [Vite](https://vitejs.dev/)[cite: 1]
* Styling: [Tailwind CSS](https://tailwindcss.com/)[cite: 1]
* Animation: [Framer Motion](https://www.framer.com/motion/)[cite: 1]
* Scrolling Mechanics: [Locomotive Scroll](https://locomotivemtl.github.io/locomotive-scroll/)[cite: 1]
* Icons: [React Icons](https://react-icons.github.io/react-icons/)[cite: 1]

## 📂 Project Structure

The project follows a clean, modular structure to ensure maintainability[cite: 1]:

```text
ochi-clone/
├── public/            
├── src/
│   ├── components/    
│   │   ├── Navbar.jsx
│   │   ├── LandingPage.jsx
│   │   ├── Marquee.jsx
│   │   ├── About.jsx
│   │   ├── Eyes.jsx
│   │   ├── Cards.jsx
│   │   └── Footer.jsx
│   ├── App.jsx        
│   ├── index.css      
│   └── main.jsx       
├── tailwind.config.js 
└── package.json