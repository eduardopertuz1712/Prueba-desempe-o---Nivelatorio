## introduction
RiwiTalk 2025 is a web platform designed to showcase conferences and events related to IT talent transformation. The project includes a main landing page, login, and registration systems with a clean, modern UI.

**Eduardo pertuz del clan macondo**

## Project Structure

```
app/
├── style/
│   ├── main.css          # Styles for authentication pages (login/register)
│   └── home.css          # Styles for the main website
├── views/
│   ├── login.html        # Login page
│   └── register.html     # Registration page
├── img/                  # Image assets
index.html                # Main landing page
```

## Features

### Authentication System
- Clean, responsive login and registration forms
- Form validation with error messages
- Animated UI elements (buttons, inputs)
- Secure password fields

### Main Website
- Responsive navigation header with search
- Conference showcase section
- Contact information footer
- Mobile-friendly design

## Technical Details

### CSS Architecture
- Uses CSS variables for consistent theming
- Modular component-based styling
- Responsive breakpoints for all devices
- Animation effects for better UX

### Dependencies
- Google Fonts (Roboto)
- Font Awesome icons
- Modern CSS features (flexbox, grid)

## Development Notes

1. **Responsive Breakpoints**:
   - 480px (mobile)
   - 768px (tablet)
   - 992px (small desktop)

2. **Browser Support**:
   - Modern browsers (Chrome, Firefox, Safari, Edge)
   - IE11 not supported

## Getting Started

1. Clone the repository
2. Open `index.html` in a browser to view the main page
3. Access `/app/views/login.html` for the login page
4. Access `/app/views/register.html` for registration

## Future Improvements
- Add JavaScript functionality for form handling
- Implement conference registration system
- Add user dashboard after login
- Enhance accessibility features
