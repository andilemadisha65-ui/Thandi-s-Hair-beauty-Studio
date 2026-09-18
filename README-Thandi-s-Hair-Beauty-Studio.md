# Thandi's Hair & Beauty Studio

A simple static website for **Thandi's Hair & Beauty Studio**, a beauty and hair-care business website. The project provides visitors with information about the studio, available services, a visual gallery, and contact details.

## Project Overview

This website was created as a multi-page HTML/CSS website. It is designed to present the business in a clean, professional, and user-friendly way.

### Main Pages

- **Home** (`Home.html`) – Introduction to Thandi's Hair & Beauty Studio and a summary of the services offered.
- **About** (`About.html`) – Background information, business story, values, and reasons to choose the studio.
- **Services** (`Services.html`) – Beauty and hair services with descriptions and starting prices.
- **Gallery** (`Gallery.html`) – Images representing beauty, nails, skin care, lashes, hair styling, and spa services.
- **Contact** (`contact.html`) – Contact information, working hours, map, and a customer enquiry form.

## Technologies Used

- HTML5
- CSS3
- External image resources from Unsplash on the Services page
- Google Maps embedded map on the Contact page

No server-side programming or database is currently required. The project can be opened directly in a modern web browser.

## Project Structure

```text
Thandi-s-Hair-beauty-Studio/
├── Home.html
├── About.html
├── Services.html
├── Gallery.html
├── contact.html
├── README.md
├── SETUP.md
├── CSS/
│   └── style.css
├── Images/
│   ├── thandis_hair_beauty_studio_logo.png
│   ├── Salon6.jpg
│   ├── Belezza.jpeg
│   └── other gallery images
└── Documents/
    └── Document 1.pdf
```

The `.git` directory contains version-control information and is not required to run the website.

## How to Run the Website

1. Extract the ZIP file.
2. Open the `Thandi-s-Hair-beauty-Studio` folder.
3. Double-click `Home.html` to open the website in a browser.
4. Use the navigation menu to move between Home, About, Services, Gallery, and Contact.

For the best experience, use a current version of Chrome, Microsoft Edge, Firefox, or Safari.

## Contact Page

The Contact page currently displays:

- Phone: `+27 72 123 4567`
- Email: `hello@thandibeauty.co.za`
- Monday–Friday: `09:00–18:00`
- Saturday: `09:00–15:00`
- Sunday: Closed

The enquiry form is currently a front-end form only. Its `action` is set to `#`, so submissions are **not sent to a server or email address** until a back-end service or form-processing provider is connected.

## Images and External Resources

Most images are stored locally in the `Images` folder. The Services page also uses several images hosted by Unsplash through external URLs. An internet connection is therefore required for those external service-page images to load.

The Contact page includes an embedded Google Maps iframe, which also requires an internet connection.

## Styling

The main stylesheet is located at:

`CSS/style.css`

The stylesheet controls the site's:

- Colours and typography
- Navigation bar
- Page layout
- Content sections
- Buttons and forms
- Footer
- Gallery and service presentation

## Known Development Notes

The current project is a static website and can be improved further by:

- Correcting inconsistent filename capitalization in navigation links (for example, `About.html` versus `about.html`).
- Cleaning up invalid or misplaced HTML tags on some pages.
- Adding a responsive mobile navigation menu.
- Replacing placeholder/example service images with approved business images.
- Confirming that the business contact details and map location are correct before publishing.
- Adding more descriptive `alt` text to all images for accessibility.
- Removing unnecessary inline styles and moving presentation rules into `style.css`.
- Adding a favicon and appropriate SEO metadata.

## Browser Compatibility

The website uses standard HTML5 and CSS3 features and should work in modern desktop and mobile browsers.

## Credits

**Project:** Thandi's Hair & Beauty Studio  
**Student/Project Reference:** ST10521209  
**Year:** 2026

## License

No specific open-source license is included with this project. The website content, branding, and business information should be treated as project/business-owned content unless otherwise stated.
