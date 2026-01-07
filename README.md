# Premium Golf Simulator Website

A modern, clean website for a golf simulator business featuring booking, shop, and customer feedback functionality.

## Features

- **Home Page**: Hero section with call-to-action, features overview, and technology highlights
- **Play/Booking Page**: Hourly reservations for:
  - Full Simulator Experience ($25/hour - Opening Month Special)
  - Net & Mat Practice ($10/hour - Limited Time Offer)
  - Free Putting & Chipping (first-come, first-served)
- **Shop Page**: Product catalog with filtering by category (Clubs, Accessories, Apparel)
- **About Page**: Detailed information about Uneekor and GSPro technologies
- **Ideas Page**: Customer feedback forms for:
  - Golf attraction suggestions
  - Website/space improvement suggestions
  - Pricing questionnaire for indoor putting/chipping green

## Technology Stack

- HTML5
- CSS3 (with CSS Variables for theming)
- Vanilla JavaScript

## Getting Started

1. Open `index.html` in a web browser
2. Navigate through the pages using the navigation menu
3. Test the booking functionality on the Play page
4. Browse products on the Shop page
5. Submit feedback on the Ideas page

## File Structure

```
golf-simulator-website/
├── index.html      # Home page
├── play.html       # Booking/reservation page
├── shop.html       # Product shop page
├── about.html      # About page with technology details
├── ideas.html      # Customer feedback and questionnaire page
├── styles.css      # Main stylesheet
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Customization

### Colors
The color scheme can be customized by modifying CSS variables in `styles.css`:
- `--primary-color`: Main brand color (dark green)
- `--secondary-color`: Secondary color
- `--accent-color`: Accent/highlight color
- `--light-green`: Light green for highlights

### Pricing
Update pricing in:
- `play.html`: Booking card prices
- `script.js`: `updateTotalPrice()` function (hourly rates)

## Notes

- The booking system currently shows alerts for demonstration. In production, you would connect this to a backend API.
- Form submissions are logged to the console. In production, these should be sent to a server.
- The website is fully responsive and works on mobile, tablet, and desktop devices.

## Browser Support

Works on all modern browsers (Chrome, Firefox, Safari, Edge).
