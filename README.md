# Style Guide Template

A clean, modern, and theme-able HTML/CSS style guide template. This project showcases a variety of UI components and layout patterns, all controlled by a flexible CSS variable-based theming system.

## 🚀 Overview

This repository provides a comprehensive visual reference for colors, typography, and common web components. It is designed to be easily customizable, allowing you to swap themes instantly to see how different color palettes and styles affect the overall design.

## 🎨 Available Themes

The style guide includes several pre-configured themes that can be toggled using the theme switcher at the top of the page:

- **☀️ Light**: The default clean, light-colored theme.
- **🌙 Dark**: A classic dark mode for reduced eye strain.
- **🌅 Sunrise**: A vibrant theme with an orange-based color palette (formerly "Brand").
- **🇺🇸 Patriotic**: A theme using American patriotic colors (Red, White, and Blue).
- **🚜 Greenfield**: A nature-inspired theme using agricultural green and construction yellow.
- **🎃 Spooky**: A Halloween-themed dark variant with pumpkin orange and toxic green.
- **🤓 Terminal**: A retro, high-contrast, green-on-black terminal aesthetic with monospaced fonts.
- **🫙 Glass**: A modern glassmorphism theme featuring transparency and backdrop blur effects.

## 🛠 Included Components

The style guide is organized into several sections, covering a wide range of UI elements:

1.  **Color Palette**: Visualization of primary, secondary, and status colors.
2.  **Typography**: Font families, headings, body text, and inline elements.
3.  **Buttons**: Various button styles including primary, secondary, outline, and icon buttons.
4.  **Form Elements**: Inputs, textareas, selects, checkboxes, and radio buttons.
5.  **Tables**: Clean, responsive table layouts.
6.  **Cards**: Flexible card components for content organization.
7.  **Modals & Dialogs**: Examples of overlaying UI elements.
8.  **Navigation & Layout**: Menus, breadcrumbs, and layout grids.
9.  **Progress & Feedback**: Progress bars, badges, and status indicators.
10. **Notifications & Alerts**: Temporary toast-style messages.
11. **Modern Components**: Accordions, Tabs, Switches, Avatars, and Skeleton Loaders.
12. **Announcements**: Persistent banners and cards for system-wide notices and internal communication.
13. **Design Token Reference**: Documentation for the CSS variables used across the project.

## 📂 Project Structure

- `style-guide.html`: The main entry point containing the full style guide and component library.
- `themes/theme-base.css`: The core styles and layout logic, using CSS variables for theming.
- `themes/theme-*.css`: Individual theme files that override the base CSS variables.

## 📝 Usage

To use this style guide, simply open `style-guide.html` in any modern web browser. You can use the theme buttons at the top to switch between the different visual styles.

To create your own theme:
1. Create a new CSS file in the `themes/` directory (e.g., `theme-mytheme.css`).
2. Define your theme variables within the `[data-theme="mytheme"]` selector.
3. Link your new stylesheet in `style-guide.html`.
4. Add a button to the theme switcher and update the JavaScript `LABELS` mapping.

---
*This project was created as a generic template to showcase modern web styling techniques.*
