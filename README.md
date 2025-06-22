# Makeup Artist Website

A one-page website for a makeup artist built with Flask.

## Project Structure
```
beauty_website/
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   └── images/
├── templates/
│   └── index.html
├── app.py
└── requirements.txt
```

## Features

- Responsive design that works on mobile and desktop
- Hero section with call-to-action buttons
- About section with artist bio
- Portfolio section with category filtering
- Services and pricing section
- Client testimonials
- Booking form with validation
- Contact information and social media links
- Footer with copyright and links

## Installation

1. Make sure you have Python installed on your system.
2. Install Flask:

```
pip install -r requirements.txt
```

## Running the Application

1. Navigate to the project directory:
```
cd beauty_website
```

2. Run the application:
```
python app.py
```

3. Open your web browser and navigate to:
```
http://127.0.0.1:5000/
```

## Deployment

This website can be deployed to various platforms:

### GitHub Pages (Static Version)
For a static version, convert templates to HTML files.

### Heroku
1. Create a Heroku account
2. Install Heroku CLI
3. Create Procfile: `web: python app.py`
4. Deploy using Git

### Railway/Render
Connect your GitHub repository for automatic deployment.