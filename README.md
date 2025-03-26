# A&R Services - Static Website

A professional static website for A&R Mechanical Services, Inc., showcasing the company's services, history, and facilitating client communication.

![A&R Services Logo](assets/images/ARlogo.png)

## Overview

This is a static website built for A&R Mechanical Services, a construction and mechanical services company founded in 1925. The website includes information about the company's services, history, news, and contact information.

## Features

- Responsive design that works across desktop, tablet, and mobile devices
- Clean, professional UI with intuitive navigation
- Service showcase with detailed information about each offering
- Contact form integration via Formspree
- Company news and updates section
- About page featuring company history and values

## Technology Stack

- HTML5
- CSS3
- JavaScript
- jQuery for DOM manipulation
- Responsive grid system
- Formspree for form handling
- Google Fonts (Oswald)

## Project Structure

```
ar-services-website/
├── index.html                # Homepage
├── about.html                # Company information and history
├── services.html             # Services offered
├── newsroom.html             # News and updates
├── contact.html              # Contact information and form
├── css/
│   └── main.css              # Main stylesheet
├── js/
│   ├── main.js               # Main JavaScript file
│   ├── slideShow.js          # Homepage slideshow functionality
│   ├── jquery.min.js         # jQuery library
│   ├── browser.min.js        # Browser compatibility
│   ├── breakpoints.min.js    # Responsive breakpoints
│   └── util.js               # Utility functions
└── assets/
    └── images/               # Image assets
        ├── ARlogo.png        # Company logo
        ├── slide1.jpeg       # Slideshow images
        ├── slide2.jpg
        └── ...
```

## Setup and Deployment

### Local Development

1. Clone this repository
2. Navigate to the project folder
3. Open any HTML file in your browser to view

### Formspree Integration

The contact form uses Formspree for processing submissions:

1. Create an account at [Formspree](https://formspree.io/)
2. Set up a new form and get your form ID
3. Replace `yourformid` in the contact form action attribute with your actual form ID:
   ```html
   <form action="https://formspree.io/f/yourformid" method="POST" class="contact-form">
   ```

### Deployment

This is a static website that can be deployed on various hosting platforms:

- **GitHub Pages**: Push to a GitHub repository and enable GitHub Pages
- **Netlify**: Connect your repository or drag and drop the folder
- **Vercel**: Import your repository and deploy
- **Traditional hosting**: Upload files via FTP to any web hosting service

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

## Credits

- Design: [Carter Schmidt](https://www.linkedin.com/in/carter-schmidt-242a99259/)
- Original template: Halcyonic
- Icons and imagery from various licensed sources

## License

All rights reserved. This project and its contents are proprietary to A&R Mechanical Services, Inc.

---

© 2024 A&R Services, Inc.
