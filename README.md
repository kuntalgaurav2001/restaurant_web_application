# Restaurant Web Project

## Overview
This is a Django-based web application for a restaurant, featuring a modern UI, menu browsing, table booking, feedback, and user authentication. The project is designed to be easily customizable for any restaurant business.

## Features
- Home page with promotional slider
- Menu display with categories and images
- Book a table form
- Customer feedback section
- User login/logout
- Responsive design

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd Restaurant_Web_Project/Resturant_Project
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

6. **Access the app:**
   Open your browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Using Provided Images

The following images are provided in the `restaurant-frontend/public` directory:
- `img1.png`
- `img2.png`
- `img3.png`
- `img4.png`
- `img5.png`

To use these images in your Django templates:
1. Copy the images from `restaurant-frontend/public` to your Django static images directory, e.g.:
   ```bash
   cp ../../restaurant-frontend/public/img*.png ../../Restaurant_Web_Project/Resturant_Project/Static/images/
   ```
2. Reference them in your templates using Django's static tag:
   ```django
   <img src="{% static 'images/img1.png' %}" alt="Menu Item 1">
   ```

## Screenshots

Below are the provided images for use in your project:

### Menu/Promotional Images

![img1](restaurant-frontend/public/img1.png)
![img2](restaurant-frontend/public/img2.png)
![img3](restaurant-frontend/public/img3.png)
![img4](restaurant-frontend/public/img4.png)
![img5](restaurant-frontend/public/img5.png)

> _If you want these images to show up on GitHub or other platforms, make sure the relative path is correct or copy the images to a folder tracked by git._

## License
This project is for educational and demonstration purposes. Please customize as needed for your own use. 