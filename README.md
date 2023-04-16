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
git clone https://github.com/shivaFero/car_parking_system/
```

# Backend 
```
pip install -r requirements.txt
```

```
paython manage.py create_default_master_data
```

```
python mange.py run server
```

set periodic task (which will be run every 5 mint)

# Front End
create .env file at project label directory(add VUE_APP_BASE_URL=<backend_url>)
```
npm run serve
```

