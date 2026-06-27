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
