
# QIU AI Video Innovation Challenge 2026 – Landing Page

A highly interactive, sci-fi-themed single-page promotional platform developed for the  **Quest International University (QIU) AI Video Innovation Challenge 2026**.

This repository contains the complete frontend architecture designed to encourage student participation in a 14-day virtual sprint where cinematic storytelling intersects with generative artificial intelligence.

## 🚀 Key Architectural Features

-   Cyberpunk Grid & Particle Background: An interactive HTML5 rendering real-time, dynamic node connections with custom physics, responding fluidly to viewport scale modifications.
    
-   **Sequential Autoplay Timeline:**  A progress track mapping the event roadmap from the opening briefing to the winner announcements. Features automated step interpolation and stylized typewriter effect components.
    
-   **Dual-View Interactive Evaluation Metrics Matrix:**  Includes a synchronized state system allowing users to explore scoring indicators through a standard 2D vector donut chart or toggle to a 3D stacked cylinder model utilizing SVG transformations.
    
-   **Immersive Custom HTML5 Video Player:**  A custom-skinned media canvas utilizing native JavaScript event mapping for playback metrics, custom seek bars, and an integrated sci-fi Head-Up Display (HUD) system status readout.
    
-   **Adaptive Layout Optimization:**  Implements advanced  `@media`  breakpoint logic optimizing viewport performance across split-screen displays, standard desktop configurations, and mobile devices via horizontal scroll snapping carousels.
    

## 🛠️ Design System & Technical Specifications

The landing page relies strictly on modern web APIs, omitting heavy framework dependencies to prioritize fast loading times and smooth execution.

### Tech Stack

-   **Structure:**  Semantic HTML5 Markup
    
-   **Styling:**  Native CSS3 featuring Custom Variable Properties (`:root`), Flexbox grid matrices, and hardware-accelerated animations (`will-change`).
    
-   **Interactivity:**  Vanilla ECMAScript 6 (ES6+) Canvas, Intersection Observer, and pointer boundary interaction models.
    
-   **Typography:**  Apple Design Ecosystem sans-serif hierarchy based on the  _Inter_  font superfamily.
    

### Core Variable Infrastructure

```css
:root {
  --neon-blue: #00f0ff;
  --neon-pink: #ff007f;
  --neon-violet: #b44fff;
  --bg-dark: #01040f;
  --bg-card: rgba(6, 12, 32, 0.75);
  --border-glow: rgba(0, 240, 255, 0.2);
  --text-primary: #f1f5f9;
  --text-muted: #94a3b8;
  --grid-line: rgba(0, 240, 255, 0.04);
}

```

## 📈 Platform Anatomy & Component Modules

```
 ┌────────────────────────────────────────────────────────┐
 │                   Header Navigation Matrix              │
 ├────────────────────────────────────────────────────────┤
 │                                                        │
 │  [01 Hero Showcase]   --> Virtual Sprint Overview      │
 │                                                        │
 │  [02 Core Purpose]    --> Introduction & SDG Goals     │
 │                                                        │
 │  [03 Media Showcase]  --> Custom HTML5 Theater Player  │
 │                                                        │
 │  [04 Project Roadmap] --> Typewriter-Driven Timeline   │
 │                                                        │
 │  [05 Sprint Themes]   --> Category Selection Grid      │
 │                                                        │
 │  [06 Metric Analysis] --> 2D Donut / 3D Cylinder Morph │
 │                                                        │
 │  [07 Regulations]     --> Regulatory Guardrails        │
 │                                                        │
 │  [08 Portal Entry]    --> Registration & Payout Info   │
 │                                                        │
 └────────────────────────────────────────────────────────┘

```

### Module Descriptions

1.  **Hero Showcase:**  Initial point of entry. Displays a high-frequency ticker element, foundational tournament analytics, and core interaction entry buttons.
    
2.  **About / Purpose Module:**  Details the underlying pedagogical alignment with United Nations Sustainable Development Goals (SDGs 4, 8, and 9) alongside cross-faculty eligibility parameters.
    
3.  **Media Theater:**  A highly stylized local playback environment utilizing custom SVG transport control iconography.
    
4.  **Sequential Timeline:**  Driven by a frame-accurate  `requestAnimationFrame`  loop that seamlessly syncs milestone documentation with physical track progress.
    
5.  **Competition Themes:**  Explores target vectors (Campus Infrastructure, Day-in-the-Life Chronicles, Peer Support Networks, and Cultural Harmony).
    
6.  **Interactive Evaluation Grid:**  Integrates SVG path length calculation algorithms (`getTotalLength`) to update a programmatic cyberpunk orthogonal vector connection path leading directly to active assessment cards.
    
7.  **Regulations:**  Outlines strict guardrails, including team structures and a mandate requiring a minimum of 80% AI-generated content.
    
8.  **Registration Dashboard:**  Implements localized asset paths for enrollment mapping alongside specific institutional funding remarks regarding tuition fee deductions.
    

## 📂 Deployment Configuration

To mount the directory to a production or development environment locally, clone the structure and verify that relative paths align with your static asset pipeline:

```bash
# Clone the repository structure
git clone https://github.com/your-username/qiu-ai-challenge.git

# Navigate into the deployment folder
cd qiu-ai-challenge

# Spin up a localized web server (e.g., via Python)
python3 -m http.server 8080

```

Ensure the following localized system assets are correctly mapped within your root directory to allow complete DOM processing:

-   `./Logo.png`  — Main brand asset.
    
-   `./trailer.mp4`  — High-definition video showcase file.
    
-   `./QR Code.png`  — Target link matrix vector.
    

## ⚖️ Motion & Accessibility Standards

The interface includes a comprehensive hardware-accelerated fallback matrix utilizing the CSS media query  `prefers-reduced-motion`. When a user enables reduced motion at the operating system level:

-   The interactive particle engine terminates execution frames loop.
    
-   The continuous marquee-scrolling ticker falls back to a structural block layout.
    
-   Transform matrices, scale adjustments, and path-shifting animations adjust to instant value modification steps to ensure structural accessibility.
