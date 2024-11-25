# Assignment 13 - Responsive Website

## Overview
This project is a responsive website created as part of Assignment 13. The site demonstrates a range of web development techniques, including responsive design, media queries, and a dropdown menu. It features four distinct pages and is hosted on GitHub Pages.

---

## Required Techniques

### **1. At Least 4 Pages**
- **Implementation**: 
  - The site includes the following pages: `index.html` (Home), `about.html` (About), `services.html` (Services), and `contact.html` (Contact).
  - Each page follows a cohesive theme with consistent design and structure.

### **2. Responsive Design**
- **Implementation**:
  - The layout uses CSS Flexbox for the navigation menu and global layout.
  - Relative units (`%, rem, em`) are used for spacing and sizing.
  - A mobile-friendly design ensures the site looks good on various devices (desktop, tablet, and mobile).

### **3. Media Queries**
- **Implementation**:
  - Adjustments are made for screens smaller than 768px using media queries in `styles.css`:
    ```css
    @media (max-width: 768px) {
        nav ul {
            flex-direction: column;
        }
    }
    ```
  - These changes ensure the navigation and layout adapt to smaller screen sizes.

### **4. Navigation Menu**
- **Implementation**:
  - A user-friendly navigation menu is included in the `<header>` of each page.
  - Links to all four pages are provided for easy access.

### **5. Dropdown Menu**
- **Implementation**:
  - A dropdown menu is added to the "Services" link in the navigation bar. 
  - The menu contains links to subsections such as "Web Design" and "SEO."
  - The dropdown functionality is implemented with CSS and appears when the user hovers over the "Services" link.

---

## Setup Instructions
1. Clone the repository or download the files.
2. Open the `index.html` file in your browser to view the site locally.
3. To make changes:
   - Edit the HTML files (`index.html`, `about.html`, `services.html`, `contact.html`).
   - Update styles in `styles.css`.
4. Push changes to your GitHub repository to update the hosted site.
