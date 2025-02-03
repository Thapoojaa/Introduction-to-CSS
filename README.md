
# **Simple Responsive One-Page Website**

**Date:** 03rd February 2025  
**Module:** Introduction to CSS  

This project is a simple, responsive one-page website built using **HTML** and **CSS**. It demonstrates the use of modern CSS features like Flexbox, Grid, animations, and media queries to create a clean and responsive design.

---

## **Features**

- **Clean Navigation Header**: A responsive navigation bar that adapts to both desktop and mobile screens.
- **Three Main Sections**:
  - **About**: A brief introduction section.
  - **Services**: A section showcasing services offered.
  - **Contact**: A simple contact form or details.
- **Fixed Footer**: A footer that stays at the bottom of the page.
- **Responsive Design**: The website is optimized for both desktop and mobile devices.
- **Simple Color Scheme and Typography**: A minimalistic design with consistent colors and fonts.
- **CSS Features**:
  - **Flexbox and Grid**: Used for layout and alignment.
  - **Hover Animations**: Subtle animations on buttons and links.
  - **Box Shadows**: Adds depth to elements like cards and buttons.
  - **Media Queries**: Ensures responsiveness across devices.
  - **CSS Variables**: Maintains consistent colors throughout the website.

---

## **Technologies Used**

- **HTML**: For structuring the content.
- **CSS**: For styling and layout, including:
  - Flexbox
  - Grid
  - Animations
  - Media Queries
  - CSS Variables

---

## **How to Use**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/simple-responsive-website.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd simple-responsive-website
   ```
3. **Open the Website**:
   - Open the `index.html` file in your browser to view the website.

---

## **Preview**

### Desktop View
![Desktop Preview](assets/desktop-preview.png) <!-- Add a screenshot if available -->
[Go Live](https://thapoojaa.github.io/Introduction-to-CSS/)

## **Code Highlights**

### **CSS Variables**
```css
:root {
  --primary-color: #3498db;
  --secondary-color: #2ecc71;
  --text-color: #333;
  --background-color: #f4f4f4;
}
```

### **Flexbox for Navigation**
```css
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem;
}
```

### **Grid for Services Section**
```css
.services {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1rem;
}
```

### **Hover Animation**
```css
.button:hover {
  transform: scale(1.05);
  transition: transform 0.3s ease;
}
```

### **Media Query for Mobile**
```css
@media (max-width: 768px) {
  .navbar {
    flex-direction: column;
  }
}
```

---

## **Contributing**

Feel free to contribute to this project! If you have any suggestions or improvements, please:
1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

---


## **Connect with Me**

- **GitHub**: [GitHub Profile](https://github.com/thapoojaa)
- **LinkedIn**: [LinkedIn Profile](https://linkedin.com/in/thapoojaa)
- **Email**: thapoojaathavanesan@gmail.com





