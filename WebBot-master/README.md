# Setup
```bash
cd WebBot
pip install -r requirements.txt
```

# Initialize
```bash
python manage.py makemigrations
python manage.py migrate
```

# Create Super User
```bash
python manage.py createsuperuser
```

# Run server
```bash
python manage.py runserver
```

# In Brouser
open http://localhost:8000



### Note:-
update `CONTACT_FROM` and `CONTACT_TO` in settings.py
```python
CONTACT_FROM = 'from_email@domain.com'
CONTACT_TO = ['to_email@domain.com']
```
