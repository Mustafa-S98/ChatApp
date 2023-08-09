# Chat Application

# Features:
- User Signup
- User Login
- Admin panel
- Sockets for live chatrooms
- List of online users

# Installation Process
To install this app please follow this below steps:
### Run Backend
```
1. Create a virtual environment `virtualenv venv` or `python -m venv venv`
2. Activate the virtualenv created above using the command: `source venv/bin/activate`(for ubuntu) `venv\Scripts\activate`(for windows)
3. Install the required modules using the command `pip install -r requirements.txt` from root directory
4. Create the migrations using the command: `python mnage.py makemigrations`
5. Migrate to database `python manage.py migrate`
6. Now run the server `python manage.py runserver`
```