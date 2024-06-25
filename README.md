Initialise a virtual environment with:
python -m venv venv

Activate your virtual environment with:
.\venv\Scripts\activate

Then install all the necessary requirements in your environment with:
python -m pip install -r requirements.txt

To start using the application run:
python manage.py runserver

To update the api and the modified data models run:
python manage.py makemigrations
python manage.py migrate