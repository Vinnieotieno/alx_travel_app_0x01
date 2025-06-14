# alx_travel_app_0x01

## API for Listings and Bookings

This Django REST API provides endpoints to manage travel listings and bookings. It also supports automatic documentation via Swagger and ReDoc.



## Features
- CRUD operations for Listings
- CRUD operations for Bookings
- Swagger UI for easy API testing



## Setup
```bash
git clone https://github.com/YOUR_USERNAME/alx_travel_app_0x01.git
cd alx_travel_app_0x01
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```



## API Endpoints

| Method | Endpoint            | Description            |
|--------|---------------------|------------------------|
| GET    | /api/listings/      | List all listings      |
| POST   | /api/listings/      | Create a new listing   |
| GET    | /api/listings/{id}/ | Retrieve a listing     |
| PUT    | /api/listings/{id}/ | Update a listing       |
| DELETE | /api/listings/{id}/ | Delete a listing       |
| GET    | /api/bookings/      | List all bookings      |
| POST   | /api/bookings/      | Create a new booking   |
| GET    | /api/bookings/{id}/ | Retrieve a booking     |
| PUT    | /api/bookings/{id}/ | Update a booking       |
| DELETE | /api/bookings/{id}/ | Delete a booking       |



## API Docs
- Swagger: [http://localhost:8000/swagger/](http://localhost:8000/swagger/)
- ReDoc: [http://localhost:8000/redoc/](http://localhost:8000/redoc/)
