# Assignment 2: Advanced Layouts with Flexbox and CSS Grid

## Introduction
Welcome to my second web design assignment! For this project, I focused on mastering modern CSS layout techniques by building a structured, responsive webpage from scratch. The main goal was to explore the practical differences and powerful capabilities of **Flexbox** and **CSS Grid** through distinct, real-world layout sections.

## Project Structure
Here is how my project files are organized:
- **`index.html`**: The core HTML5 document containing semantic elements divided into 5 clear task sections.
- **`style.css`**: The stylesheet where all the layout logic, Flexbox alignments, Grid definitions, colors, and hover transitions live.
- **`images/`**: A dedicated folder storing the visual assets (`img1.png`, `img2.png`, `img3.png`) used across the project cards, galleries, and portfolio showcases.

## What I Built (Task Breakdown)

### 1. Navigation Bar (Flexbox)
- Built using a flexible box layout (`display: flex`) with `justify-content: space-between` to keep the brand logo neatly separated from the navigation links.
- Styled with a clean, dark-themed background (`#333`) and balanced padding for a professional look.

### 2. Project Cards (Flexbox)
- Designed a flexible row container holding three individual project cards side-by-side.
- Each card incorporates a clean border, custom images styled with `object-fit: cover` to prevent distortion, descriptive text, and an interactive "View" button featuring a smooth `translateY` hover effect.

### 3. Structural Page Layout (CSS Grid)
- Implemented a complex macro-layout using **CSS Grid** and explicit `grid-template-areas`.
- Structured a responsive grid containing a distinct Header, a sidebar (`sidebar`), a central Main Content Area, and a Footer, all neatly aligned into a two-column layout (`250px 1fr`).

### 4. Image Gallery (CSS Grid)
- Created a balanced, multi-column photo grid using `grid-template-columns: repeat(3, 1fr)`.
- Added smooth scale-up transitions on hover to make the gallery interactive and visually engaging.

### 5. Personal Portfolio Layout (Grid & Flexbox)
- Combined CSS Grid and Flexbox to build a polished personal portfolio section.
- Features an "About Me" informational sidebar on the left highlighting my background as a Computer Science student and my core technical skills (HTML & CSS, Flexbox & Grid, Git & GitHub), paired with a dedicated project showcase grid on the right.

## Technologies Used
- **HTML5 & CSS3** (Semantic tags, Flexbox, CSS Grid)
- **Visual Studio Code** (Development environment)
- **Git & GitHub** (Version control and tracking)

---
*Created with dedication as part of my Computer Science coursework.*