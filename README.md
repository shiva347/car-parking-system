# Car Parking System

This is a web application for managing car parking system, developed using Python and Django REST framework 
in the backend and Vue.js in the frontend. PostgreSQL is used as the database for the application.


## Technologies

- Python
- Django REST framework
- Django Celery 
- PostgreSQL
- Vue.js


## Project Setup 
Clone the repository
```
git clone https://github.com/shiva347/car-parking-system.git
```

Navigate to the backend directory
```
cd car-parking-system/backend/
```

Create and activate a virtual environment
```
python -m venv myenv
```
For Windows 
```
myenv\Scripts\activate
```
For Linux or Mac
```
source myenv/bin/activate
```

# Backend 
Navigate backend project directory
```
cd car_parking
```
Install the required packages
```
pip install -r requirements.txt
```

```
python manage.py create_default_master_data
```

```
python mange.py run server
```

set periodic task (which will be run every 5 mint)

# Front End
Navigate front-end project directory
```
cd car-parking
```
Install the required packages
```
npm install
```

create .env file at project label directory(add VUE_APP_BASE_URL=<backend_url>)

```
npm run serve
```

