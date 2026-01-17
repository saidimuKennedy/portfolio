### Kennedy Saidimu - Interactive Developer Portfolio

This repository contains the source code for my personal portfolio website. It's a single-page application designed to showcase my projects, technical skills, and unique professional journey as a Biomedical Engineer and Web Developer.

The portfolio is built with a focus on interactivity, animations, and a clean, modern aesthetic to create an engaging user experience.

### ✨ Live Demo

You can view the live version of the portfolio here: **[https://your-live-url.com](https://your-live-url.com)**

_(Don't forget to replace `https://your-live-url.com` with your actual deployment link!)_

### 🚀 Key Features

- **Project Showcase:** An interactive carousel to display recent work with titles, descriptions, and technology stacks.
- **Interactive Tech Stack:** A dynamic, draggable network graph that visualizes my technical skills and their relationships. Users can drag nodes around, and hovering over a skill highlights its connections.
- **Animated Career Roadmap:** A scroll-driven SVG path animation that reveals my career and learning trajectory, from core foundations to future goals in DevSecOps and cloud architecture.
- **"Dual Engine" Philosophy:** A unique section that connects my background in Biomedical Engineering (systems thinking, fault tolerance) with my software development practices.
- **Responsive Design:** A fully responsive layout for optimal viewing on all devices. The roadmap section gracefully degrades to a horizontal scroll on mobile for a better user experience.
- **Modern Aesthetics:** Utilizes glassmorphism, subtle glows, and smooth animations to create a polished and professional look.

### 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Styling:**
  - **Tailwind CSS:** For rapid, utility-first UI development.
  - **Custom CSS:** For complex animations, the network graph, and the roadmap styling.
- **Libraries & Fonts:**
  - **Font Awesome:** For icons.
  - **Google Fonts:** For the "Poppins" typeface.

### 📂 Project Structure

The entire portfolio is contained within a single `portfolio.html` file.

- **`<head>`**: Contains metadata, CDN links for Tailwind CSS, Google Fonts, and Font Awesome, and all the custom CSS within `<style>` tags.
- **`<body>`**: Contains the HTML structure for all sections of the portfolio.
- **`<script>`**: A single script tag at the end of the body contains all the JavaScript logic for:
  - The project carousel.
  - The draggable tech stack network graph and line drawing.
  - The scroll-based animation for the career roadmap.
  - Intersection Observer for animating elements on scroll.
