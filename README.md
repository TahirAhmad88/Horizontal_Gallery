# Horizontal Scroll Image Gallery:
A sleek, interactive image gallery with horizontal scrolling and smooth navigation

# Features:
* Horizontal Scrolling - Navigate images left to right
* Dual Navigation - Use the mouse wheel or the arrow buttons
* Interactive Effects - Images transition from grayscale to color on hover
* Zoom Effect - Images scale up slightly for better viewing
* Responsive Design - Works on all screen sizes
* Clean Interface - Minimal dark theme focuses on content

# Live Demo:
https://tahirahmad88.github.io/Horizontal_Gallery/

# ScreenShot:
<img width="1302" height="564" alt="gallery" src="https://github.com/user-attachments/assets/5bb22b15-94ab-4e65-89dd-d75e5c4ebd05" />

# Quick Start
1. Clone the repository

bash
git clone https://github.com/TahirAhmad88/Horizontal_Gallery.git

2. Open HorizontalScrollImageGallery.html in your browser

That's it! No dependencies or installation needed.

# Project Structure
text
Horizontal_Gallery/
├── HorizontalScrollImageGallery.html   # Main HTML file
├── HorizontalScrollImageGallery.css    # Styles & animations  
├── HorizontalScrollImageGallery.js     # Navigation logic

└── images/                            # Image assets
    ├── image-1.png to image-6.png     # Gallery images
    ├── back.png                       # Back button
    └── next.png                       # Next button
# How to Use
  **Method	          Action**
* Mouse Wheel	    Scroll up/down to move horizontally
* Back Button	    Click to move 900px left
* Hover Image	    See it in color with zoom effect

# Built With
* HTML5 - Structure
* CSS3 - Styling, animations, responsiveness
* JavaScript - Interactivity & navigation

# Customization
* Change scroll distance
javascript
// In HorizontalScrollImageGallery.js
scrollContainer.scrollLeft += 900; // Adjust this number

* Change image grid layout
css
/* In HorizontalScrollImageGallery.css */
.grid-template-columns: auto auto auto; /* Change columns */

* Adjust grayscale effect
css
.gallery div img {
    filter: grayscale(100%); /* 0-100% */
}
# Troubleshooting
  **Issue**	                      **Solution**
Images not loading	          Check images/ folder and file names
Gallery not scrolling	      Verify JavaScript is linked correctly
Layout breaks on mobile	      Adjust .gallery width in CSS

# Contributing
1. Fork the repository
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some amazing feature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

# 👤 Author
Tahir Ahmad

# GitHub: @TahirAhmad88

 # If you find this project useful, consider giving it a star!
