# EELU Medical Clinic Website

A modern, responsive website for a medical clinic allowing patients to browse doctors, view specialties, check availability, and book appointments.

## Features

- **Doctor Directory**: Browse available doctors with detailed profiles including specialty, experience, ratings, and availability status
- **Specialty Filtering**: Filter doctors by medical specialty (General Surgery, Cardiology, Pediatrics, Ophthalmology, Dentistry, Dermatology)
- **Doctor Details Modal**: Click on any doctor card to view detailed information and book appointments
- **User Profile**: Display user information in the navigation bar
- **Responsive Design**: Optimized for desktop and mobile devices
- **Dark Theme**: Modern dark UI with blue accents

## Pages

- **Home (index.html)**: Main landing page
- **About (about.html)**: Information about the clinic
- **Doctors (mine/index.html)**: Doctor selection and filtering page
- **Services (services.html)**: Clinic services
- **Booking (booking.html)**: Appointment booking
- **Dashboard (dashboard.html)**: Patient dashboard

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Styling with modern features like CSS Grid, Flexbox, backdrop-filter, and animations
- **JavaScript**: Interactive filtering and modal functionality
- **Font Awesome**: Icons for UI elements
- **Google Fonts**: IBM Plex Sans Arabic for Arabic text

## Project Structure

```
eelu-project/
├── index.html          # Home page
├── about.html          # About page
├── doctors.html        # Doctors page
├── services.html       # Services page
├── booking.html        # Booking page
├── dashboard.html      # Patient dashboard
├── mine/
│   ├── index.html      # Doctor selection page (duplicate/alternative)
│   └── style.css       # Main stylesheet
├── assets/             # Images and assets
└── README.md           # This file
```

## How to Run

1. Clone or download the repository
2. Open any HTML file in a modern web browser
3. Navigate between pages using the navigation menu

## Styling Features

- Gradient backgrounds and backdrop blur effects
- Smooth animations and transitions
- Drop shadows and glowing effects for interactive elements
- Expanding underlines on navigation hover
- Responsive grid layout for doctor cards

## Recent Styling Updates

The following enhancements have been added to improve visual appeal:

- **User Profile Avatar**: Added drop shadow effect (`box-shadow: 0 6px 18px rgba(0, 0, 0, 0.6);`)
- **Navigation Links**: Implemented expanding underline animation on hover and active states
- **Active Navbar Page**: Added glowing text shadow (`text-shadow: 0 2px 4px rgba(56, 189, 248, 0.6);`)
- **Active Filter Chips**: Added glowing box shadow (`box-shadow: 0 4px 12px rgba(56, 189, 248, 0.4);`)