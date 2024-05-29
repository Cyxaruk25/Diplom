How to Setup
Clone Project
git clone https://github.com/Cyxaruk25/Diplom.git
Go To Project Directory
cd inventory-management
Create Virtual Environment
python3 -m venv venv
Active Virtual Environment
source venv/bin/activate
Install Requirements File
pip install -r requirements.txt
Migrate Database
python manage.py migrate
Create Super User
python manage.py createsuperuser
Run Project
python manage.py runserver
