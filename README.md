# Modern E-commerce Website

A modern e-commerce website built with Flask, Jinja2, and Tailwind CSS.

## Features

- Responsive design
- Product listing by categories
- Product detail pages
- Shopping cart simulation
- Checkout flow
- Modern UI with Tailwind CSS

## Setup Instructions

1. Create and activate a Python virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install Python dependencies:
```bash
pip install -r requirements.txt
```

3. Install Node.js dependencies:
```bash
npm install
```

4. Build Tailwind CSS:
```bash
npm run build:css
```

5. Run the Flask application:
```bash
flask run
```

The application will be available at http://localhost:5000

## Development

- To watch for CSS changes during development:
```bash
npm run build:css
```

## Project Structure

```
ecommerce/
├── app.py                 # Flask application
├── data/
│   └── demo_data.py      # Demo product data
├── static/
│   ├── css/
│   │   ├── input.css     # Tailwind input
│   │   └── style.css     # Compiled CSS
│   └── images/           # Product images
├── templates/
│   ├── components/       # Reusable components
│   ├── products/         # Product templates
│   ├── cart.html
│   ├── checkout.html
│   ├── index.html
│   └── layout.html
├── package.json          # Node.js dependencies
├── requirements.txt      # Python dependencies
└── tailwind.config.js   # Tailwind configuration
```

## Note

This is a demo application with simulated cart functionality. In a production environment, you would need to:
- Implement proper session management for the shopping cart
- Add user authentication
- Connect to a real database
- Process actual payments
- Add proper form validation and CSRF protection
