Cinema Paradiso
Cinema-Paradiso in React & Redux + Django
# Cinema-Paradiso, with a frontend built in React & Redux and a backend built in Django API.
Live Demo
This App uses a Replit free plan, so I am afraid that it takes time to load the pages.
Check out [FRONTEND LIVE](https://cinemaparadiso-frontend.saniulmallik.repl.co/) DEMO here!!
Check out [API LIVE](https://cinemaparadiso-backend.saniulmallik.repl.co/) DEMO here!!
Tech used
* Frontend : React & Redux
* Backend : Django

How to Install
Git Clone
git clone 
Backend setting
cd backend
Python -m venv env
(For Mac) source env/bin/activate
(For Windows) env/Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
# Open http://127.0.0.1:8000/posts/

# To have dummy data for testing run:
python manage.py fixtures/dummy-data.json
Frontend setting
cd frontend
npm install
npm start
# Open http://127.0.0.1:3000/
..
