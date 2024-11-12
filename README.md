# Hungry Rooster Website

This project is a website for "Hungry Rooster," a fictional restaurant and cloud kitchen. The design focuses on a clean, responsive, and user-friendly interface that emphasizes the restaurant's offerings, customer engagement, and branding.

## Design Choices

1. **Typography**:  
   The website uses Google Fonts with a combination of "Ubuntu" for general text, providing a modern and approachable look, and "Azeret Mono" for occasional stylized text accents. This combination helps balance readability with a contemporary, engaging style.

2. **Color Scheme**:  
   I chose a color scheme that reflects warmth and appetizing qualities. For example:
   - Dark red (#5B283B) for the "Hungry" part of the brand, giving a feeling of sophistication.
   - Bright red (#FE4763) for the "Rooster" part, adding a touch of energy and excitement.

3. **Hero Section**:
   - Implemented a Bootstrap carousel for the hero section with a semi-transparent overlay on captions (`caption-overlay`). The overlay ensures text readability against background images.
   - Each slide includes a call-to-action button, encouraging users to explore the menu or specials.

4. **Card Layout for Menu Items**:
   - The menu section utilizes Bootstrap’s grid system and card components, showcasing dishes in an organized, grid-based gallery. Each card scales up on hover, achieved through CSS transitions, adding an interactive feel to the browsing experience.
   - Cards are responsive and adjust to fit different screen sizes.

5. **Contact Form**:
   - Used Bootstrap’s form components for a straightforward contact form.
   - The form is centered and contained within a max-width to avoid overstretching on larger screens, ensuring a cohesive layout.

6. **Footer**:
   - Social media links are implemented with Font Awesome icons, and links are centered and spaced to give a balanced layout.
   - An additional disclaimer section is included to manage customer expectations regarding product images and branding.

## Unique Bootstrap Features and Customizations

- **Fixed Navbar**:  
  The navbar is set as `navbar-expand-sm` and `fixed-top`, providing a responsive menu that adapts on smaller screens.

- **Responsive Grid System for Menu Section**:  
  Bootstrap’s `row-cols-1 row-cols-md-3 row-cols-lg-4` classes were used to manage the number of visible cards based on screen size, making the layout adapt to various devices without additional media queries.

- **Carousel**:  
  The hero section leverages Bootstrap's carousel functionality with additional custom styling for overlay captions. Each carousel slide has a different call-to-action, engaging visitors to explore the site.

- **Interactive Cards with Custom CSS**:  
  Each card has a hover effect with a CSS `transform: scale(1.05)` transition to make the menu section feel dynamic and interactive.

## Additional Features

- **Smooth Scrolling**:  
  Implemented smooth scrolling across sections to improve the user experience when navigating within the same page.

- **Image Adaptation with Media Queries**:  
  Adjusted carousel images to maintain height based on the viewport, improving mobile responsiveness.

---

## Live Link

https://aesthetic-bublanina-29053c.netlify.app

This README provides a quick overview of the design choices and custom features, explaining how Bootstrap was leveraged and customized for a unique look and feel.
