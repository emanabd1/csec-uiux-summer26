# CSEC ASTU Dev Summer Program 2026 — UI/UX Design Track

Repository to document my progress, daily challenges, and foundational learning throughout the self-directed summer program.

## 📈 Phase 1: Design Foundations (Weeks 1-3)

### 🎥 Video Resource Logs & Key Takeaways

I have fully reviewed the three required foundational video resources from the track spreadsheet:

1. **The Principles of Design | FREE COURSE (Envato Tuts+)**
   * **Contrast & Emphasis:** Learned how to leverage stark differences in color weight and size to draw a user's eye to primary focal points (like the primary CTA button).
   * **Repetition:** Understood how repeating shapes, text casing, and standard spacing creates harmony, professional consistency, and strong brand alignment.
   * **Whitespace:** Mastered using negative space to give design elements breathing room, preventing the user interface from looking cluttered.

2. **UI/UX Explained In 8 Minutes (Simplilearn)**
   * **UI vs. UX:** UI is the presentation, layout, and visual flavor; UX is the strategy, flow, and psychological feeling of the product.
   * **The Product Life Cycle:** Learned the chronological transition from User Research ➡️ Wireframing ➡️ Visual Design ➡️ Information Architecture ➡️ Usability Testing.

3. **Figma Wireframe Tutorial for Beginners (Aliena Cai)**
   * **The Golden Rule:** *“Don’t paint the walls while laying the bricks.”* Focused on building layout structures using grayscale frames before thinking about complex styling.
   * **Industry Standards:** Kept interactive mobile touch targets at a minimum height of 48px for perfect thumb-tapping accessibility.

---

### 🎨 Daily UI Challenges

#### Daily UI #001: Sign-Up Screen
* **Concept:** A minimalist app account creation layout.
* **Design Strategy:** Applied clean vertical hierarchy, standardized form element boxes to 48px heights, and fixed icon alignment to maximize usability based on video feedback.


---

#### Daily UI #002: Credit Card Checkout
* **Concept:** A secure checkout form integrated into the initial application user flow.
* **Design Strategy:** Applied consistent button accents, standardized text heights, and clean layout symmetry to lower user cognitive load during checkout.



---

#### Daily UI #003: Landing Page
* **Concept:** A minimalist mobile app landing page targeting tech students and developers.
* **Design Strategy:** Leveraged strong visual typography hierarchy with a prominent primary CTA button, optimized whitespace, and added localized social proof to build instant user trust.



---

#### Daily UI #004: Specialty Calculator
* **Concept:** An academic GPA and goal forecasting calculator for the personalized student productivity app.
* **Design Strategy:** Integrated established signature brand colors for key calculated metrics while maintaining design symmetry by utilizing identical input structures and aligned visual icons.







### Daily UI #005
# EMAN — Brand Identity & App Icon

A premium, human-crafted brand icon designed for full-stack software development environments, combining fluid organic geometry with clean technical precision.

## 🎨 Design Specifications

| Element | Specification | Hex Code / Value |
| :--- | :--- | :--- |
| **Primary Brand Color** | Flat Ochre Gold | `#D5A660` *(approximate)* |
| **Primary Background** | Deep Midnight Navy | `#162244` *(approximate)* |
| **Outer Frame** | Slate Charcoal | `#333842` *(approximate)* |
| **Typography** | All-Caps Sans-Serif | Tracking: `+20%` (Wide Spread) |

## 🛠️ Layer Architecture & Effects

1. **Monogram Vector (`e` + Leaf):**
   * **Effect:** Drop Shadow
   * **Settings:** `X: 0`, `Y: 4`, `Blur: 8`, `Opacity: 15%`, Color: `#000000`
2. **Typography Layer ("EMAN"):**
   * Symmetrical tracking applied for high-end baseline balance.
3. **Canvas Geometry:**
   * **Inner Frame:** Capsule pill format.
   * **Outer Frame:** Symmetrical squircle container.

## 🚀 Usage Guidelines
* **Minimum Size:** 24x24px (Ensure shadow is disabled at micro-scales to retain vector clarity).
* **Scaling:** Always lock aspect ratio to `1:1` when scaling the icon canvas.



# Personal Portfolio Dashboard

A premium, high-contrast desktop user profile dashboard designed for software engineers. This project features a custom-curated color palette, a structured multi-column layout, and modular component cards displaying professional summaries, technical stacks, and active platform profiles.

## 🎨 Color Palette & UI Architecture

This interface utilizes a sophisticated dark-themed system designed to balance modern tech aesthetics with high-impact readability:

| UI Component | Assigned Color | Hex Code | Role |
| :--- | :--- | :--- | :--- |
| **Main Canvas Background** | Deep Base | `#210440` | Immersive midnight-purple background canvas |
| **Sidebar Navigation** | Deep Base | `#210440` | Structural left-column pane framing core branding elements |
| **Topbar / Banner** | Mid-tone Structure | `#E5958E` | Muted terracotta header layout anchoring profile data |
| **Modular Content Cards** | Light Foreground Fill | `#FDB095` | Soft accent tone or container fill for textual content blocks |
| **Interactive Assets / Typography** | High-Impact Accent | `#FFBA00` | Vibrant gold utilized for custom monograms, names, and buttons |

---

## 📂 Project Structure

```text
├── assets/
│   ├── brand/
│   │   ├── e-monogram.svg        # Custom gold "e" brand monogram
│   │   └── full-signature.svg    # Gold and white typography header
│   └── images/
│       ├── profile-avatar.png    # Circular profile picture with gold border
│       └── image_9ac58b.jpg      # Layout wireframe asset reference
├── components/
│   ├── Sidebar.jsx               # Left navigation frame with persistent links
│   ├── Topbar.jsx                # Header block featuring search bar and action buttons
│   └── Card.jsx                  # Reusable, responsive container grid components
├── styles/
│   └── globals.css               # Core CSS layout rules and variable mapping
├── index.html                    # Root application entrance
└── README.md                     # Project documentation
```


# Daily UI #007: Personalization & Integration Dashboard — UI/UX Design Specification

A high-fidelity dashboard design concept engineered for the Daily UI #007 "Settings" challenge. This project explores dark-mode interface design, information architecture hierarchy, and tactile micro-interactions tailored for software engineers and competitive programmers.

---

## 🎨 Visual Design System

### 1. Color Palette & Accessibility
The interface utilizes a cohesive, cyberpunk-inspired deep purple palette. The color choices prioritize low luminosity to prevent eye strain during long-duration screen exposure, while ensuring a high contrast ratio for interactive elements.

* **Primary Canvas (`#1b053a`):** A deep, saturated midnight purple used as the main content area background. It establishes an immersive environment softer than high-contrast pure black.
* **Sidebar Navigation (`#15032d`):** A tier-darker purple variant that visually anchors the navigation menu, creating immediate structural depth.
* **Brand Accent Gold (`#ffd615`):** Reserved exclusively for active selection states, crucial toggles, and primary call-to-action triggers to capture immediate visual attention.
* **Element Orange (`#f07b65`):** Applied to secondary headings and category markers to balance the palette and establish clear line-item boundaries.
* **Muted Lavender (`#a18bb5`):** Used for helper micro-copy and descriptions to signal non-interactive text.

### 2. Typography & Hierarchical Scale
The type scale is strictly controlled to ensure clean scannability, allowing users to differentiate between system headers, line items, and contextual subtext at a glance:

* **Global Section Header:** `2.0rem` / Medium Weight — Immediate entry point confirmation.
* **Setting Group Titles:** `1.4rem` / Medium Weight — Identifies major configuration categories.
* **Component Labels:** `1.15rem` / Regular Weight — Names individual line-item settings.
* **Explanatory Micro-copy:** `0.95rem` / Light Weight — Delivers inline system instructions.

---

## 🧭 Information Architecture & Layout Strategy

### Master-Detail Split Layout
The dashboard implements a dual-panel setup that aligns with the user's established mental model for complex configuration interfaces:
* **Persistent Left Sidebar:** Houses global application modules (Personalization, API, Privacy). Standardized iconography paired with clean typography accelerates category recognition.
* **Z-Pattern Content Flow:** Settings are stacked vertically on the right panel, encouraging a natural top-to-bottom reading gravity. Horizontal division rules cleanly isolate individual control groups to eliminate cognitive overload.
* **Terminal Action Placement:** The primary "Save Changes" button is strategically anchored in the bottom-right corner. This respects standard user interaction flow, placing the final execution trigger exactly where the user's eye lands after completing form adjustments.

---

## ⚡ Interactive Component UX (Micro-interactions)

* **Tactile Capsule Toggles:** The integration sync rows utilize custom slider capsules instead of standard native checkmarks. When an active sync matrix is engaged, the button knob shifts right and triggers a high-visibility gold state change, giving the user immediate reassurance that a connection is active.
* **Segmented Button Controls:** Theme options (Light/Dark) are contained inside an inset pill frame, providing clear visual containment and clear selection boundaries.
* **Contextual Input Fields:** Dropdowns and text triggers use distinct background styling variations to separate text readouts from button clicks seamlessly.








### 📌 Day 008 — 404 Page (Error State)
*   **Concept:** A clean, brand-friendly error interface to gracefully guide lost users back to safety.
*   **Key Features:** Highly visible call-to-action buttons for support routing, a fixed 844px standard mobile screen viewport layout with content clipping, and structured tab navigation centered around a deep purple canvas.

---

## 🧰 Tools & Technologies Used
*   **Figma** — Interface blueprinting, layout architecture, and prototyping.
*   **Auto Layout & Constraints** — Rigid responsive structural control.


### 📌 Day 009 — Music Player Layout
*   **Concept:** A dark-themed mobile music playback interface built for optimal accessibility and clean hierarchy.
*   **Key Features:** Balanced horizontal media control navigation bar, distinct color-coded time tracking milestones, and scannable typographic stacks for song details.

---

## 🧰 Tools & Technologies Used
*   **Figma** — Interface blueprinting, layout architecture, and prototyping.
*   **Auto Layout & Constraints** — Rigid responsive structural control.



### 📌 Day 010 — Social Share Widget
*   **Concept:** A developer-focused profiles and project sharing hub widget designed for platform-wide cross-linking.
*   **Key Features:** Highly organized grid layout for key platform buttons (GitHub, LeetCode, Codeforces, LinkedIn), a highlighted media contribution display panel, and an accessible one-click custom repository link sharing input bar.

---

## 🧰 Tools & Technologies Used
*   **Figma** — Interface blueprinting, layout architecture, and prototyping.
*   **Auto Layout & Constraints** — Rigid responsive structural control.



### 📌 Day 011 — Flash Messages / Notifications
*   **Concept:** A live-updating pipeline and deployment log overview tracking real-time status updates for development tasks.
*   **Key Features:** Visual status alerts (Success indicators, warning states), time-relative log tags, an active tab bar navigation panel, and a high-contrast action link button layout.
