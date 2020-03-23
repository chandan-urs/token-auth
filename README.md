## Gude:
Run the following commands:
```python
python manage.py makemigrations
'''
```python
python manage.py migrate
'''

#### To create user:
http://localhost:8000/api/profile/

### After creating the user use the following url for token generations
## VERY IMPORTANT: ENTER EMAIL ID IN USERNAME FIELD
http://localhost:8000/api/login/

Add the AUTHORIZATION token request header and create new item in the following url
## IMPORTANT: This feature only works when a valid Authorization token is added in header.
http://localhost:8000/api/feed/