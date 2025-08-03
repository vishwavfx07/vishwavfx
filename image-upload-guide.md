# Image Upload Guide

## Quick Steps to Add Images:

### 1. Prepare Your Image
- Resize to appropriate dimensions (800x600px for projects)
- Optimize file size (under 500KB)
- Save as .jpg or .png format

### 2. Add to Website
1. Navigate to: `E:\Cursor\Website\assets\images\projects\`
2. Copy your image file to this folder
3. Use a descriptive filename (e.g., `volumetric-clouds.jpg`)

### 3. Add to HTML
Copy this template and update the details:

```html
<div class="project-card">
    <img src="assets/images/projects/your-image-name.jpg" alt="Your Project Description">
    <div class="project-label">Your Project Name</div>
</div>
```

### 4. Update Filter (if needed)
If adding a new category, update the filter buttons in the HTML.

## Image Requirements:
- **Format**: JPG, PNG, or WebP
- **Size**: Under 500KB
- **Dimensions**: 800x600px or 1200x800px
- **Naming**: Use hyphens, no spaces (e.g., `fire-simulation.jpg`)

## Folder Structure:
```
assets/images/
└── projects/     # Project showcase images
``` 