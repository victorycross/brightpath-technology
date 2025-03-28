# BrightPath Technology Website - Deployment Instructions

## Overview
This package contains all the files needed to deploy the BrightPath Technology website to your Squarespace account. The website has been custom-designed based on your requirements and includes all the sections, content, and functionality you requested.

## Package Contents
- `index.html`: The main HTML file containing the website structure
- `css/`: Directory containing all CSS stylesheets
- `js/`: Directory containing JavaScript functionality
- `images/`: Directory containing all optimized images for the website

## Deployment Instructions for Squarespace

### Option 1: Using Code Injection (Recommended for Header/Footer Elements)

1. Log in to your Squarespace account at https://account.squarespace.com/domains/managed/brightpathtechnology.io/website
2. Navigate to Settings > Advanced > Code Injection
3. In the "Header" section, add the link to your CSS file:
   ```html
   <link rel="stylesheet" href="/s/styles.css">
   ```
4. In the "Footer" section, add the link to your JavaScript file:
   ```html
   <script src="/s/main.js"></script>
   ```

### Option 2: Using Custom HTML Blocks (For Page Content)

1. Log in to your Squarespace account
2. Navigate to the page where you want to add custom HTML
3. Add a "Code" block to the page
4. Copy and paste the relevant HTML sections from the index.html file
5. Save your changes

### Option 3: Full Site Replacement (For Complete Custom Site)

For a complete replacement of the Squarespace template with this custom website:

1. Log in to your Squarespace account
2. Navigate to Settings > Advanced > Import/Export
3. Select "Import" and upload a zip file of this entire deployment folder
   - Note: You may need to contact Squarespace support for assistance with a full site import

### Uploading Files to Squarespace

To upload the CSS, JavaScript, and image files:

1. Navigate to Settings > Advanced > Custom CSS
2. Click on "Manage Custom Files"
3. Upload all files from the css, js, and images directories
4. Make sure to maintain the same directory structure

## Additional Notes

- The website is fully responsive and has been tested on various screen sizes
- The contact form is set up but will need to be connected to your Squarespace form handling
- All images are optimized for web performance
- The website includes JavaScript functionality for smooth scrolling, testimonial sliders, and form validation

## Support

If you need any assistance with the deployment or have questions about customizing the website further, please don't hesitate to reach out.

---

Thank you for choosing our services for your BrightPath Technology website!
