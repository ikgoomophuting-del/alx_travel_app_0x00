# alx_travel_app_0x00
The alx_travel_app_0x00 is a Django REST Framework project that simulates a travel booking platform. It includes models for listings, bookings, and reviews, with serializers for API representation. A custom seeder command populates demo data, helping learners practice building and testing REST APIs with Django.
---

Features

Listings: Hosts can create and manage property listings.

Bookings: Guests can book properties with start and end dates, tracking booking status.

Reviews: Guests can rate and review listings they’ve booked.

Seeder: Command to populate the database with sample listings and users.

---

## Installation 

# Clone the repository
git clone https://github.com/your-username/alx_travel_app_0x00.git
cd alx_travel_app_0x00

# Create and activate virtual environment
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py makemigrations
python manage.py migrate
---

## Usage
python manage.py runserver

Visit API endpoints at:

http://127.0.0.1:8000/api/listings/

http://127.0.0.1:8000/api/bookings/

http://127.0.0.1:8000/api/reviews/
---

Database Seeding

Populate the database with sample data:

python manage.py seed


This creates a demo host user and sample listings.
---

### API Structure

Listings

GET /api/listings/ → List all listings

POST /api/listings/ → Create a new listing

Bookings

GET /api/bookings/ → List all bookings

POST /api/bookings/ → Create a new booking

Reviews

GET /api/reviews/ → List all reviews

POST /api/reviews/ → Add a review
---

## Tech Stack

Python 3

Django

Django REST Framework

SQLite (default dev database)
---

## License

This project is part of the ALX Software Engineering Curriculum and is for educational purposes.



