# django_bgRemoverML

A Machine Learning Project integrated with Django to Remove Background from Image. 

## Installation:
(used python 3.7)
- git clone https://github.com/FarjaalAhmad/django_bgRemoverML
- cd django_bgRemoverML
- python3 -m pip install -r requirements.txt
- bash setup.sh
- python3 manage.py migrate
- python3 manage.py runserver

### Supported OS:

- macOS 

### For API Usage:

Make a POST request to http://localhost:8000/upload with the Following parameters.
image=[BASE64 ENCODED IMAGE HERE]

